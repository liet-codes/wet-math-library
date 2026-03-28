# RULES.md — Library Submission Standards

## Core Principle
Every document in this library follows a **tiered summary structure** for efficient context loading by both humans and AI agents. No document is stored as a raw dump.

## Required Files Per Document

```
<work-slug>/
  source.*              # Original file (PDF, LaTeX, etc.) — preserved as-is
  full-text.md          # Complete text in markdown, broken by chapter/section
  L2-summary.md         # Detailed summary — 10-30% of full text length
  L1-summary.md         # Structural overview — 500-800 words
  L0-abstract.md        # One-sentence + one-paragraph abstract — ~100 tokens
  metadata.yaml         # Structured metadata (see below)
  figures/              # Extracted figures and diagrams (if any)
```

## Tier Definitions

### L0 — Abstract (~100 tokens)
- **One sentence**: What is this document?
- **One paragraph**: Why does it matter? What are the key claims?
- Purpose: Entry point. An agent reads this to decide whether to load L1.

### L1 — Structural Overview (500-800 words)
- Title, author, date, context of writing
- Section/chapter structure with one-line descriptions
- Main thesis and 3-5 key ideas (1-2 sentences each)
- Key objects, definitions, or constructions introduced
- Connections to other works and fields
- Purpose: Planning. An agent reads this to decide which sections to pull from L2 or full text.

### L2 — Detailed Summary (10-30% of original length)
- Section-by-section treatment
- Core arguments, claims, and proofs (compressed but precise)
- Key definitions and constructions preserved verbatim when possible
- Important conjectures and open questions
- Notable formulations and quotes
- Mathematical notation preserved (LaTeX)
- Purpose: Working reference. For most tasks, L2 is sufficient without reading the full text.

### Full Text (full-text.md)
- Complete document converted to markdown
- Section headers preserved as markdown headers
- Mathematical notation in LaTeX
- Page breaks marked with `---`
- Figures referenced by path: `![description](figures/fig-name.png)`
- Purpose: Deep reading. Loaded only when L2 is insufficient.

## Metadata Schema (metadata.yaml)

```yaml
title: "Full title of the work"
author: "Author name(s)"
date: "YYYY or YYYY-MM or YYYY-MM-DD"
language: "en" | "fr" | "de" | etc.
type: "manuscript" | "paper" | "book" | "letter" | "lecture-notes" | "thesis"
source_url: "URL where the original was obtained"
word_count: 19167  # of full-text.md
pages: 41          # of original document

# Content classification
tags:
  - algebraic-geometry
  - category-theory
  - homotopy-theory

# Relevance to our research (optional but encouraged)
relevance:
  groovy-commutator: "brief note on connection"
  wet-math: "brief note on connection"
  scale-geometry: "brief note on connection"

# Provenance
extracted_by: "tool or person that did the extraction"
extraction_date: "YYYY-MM-DD"
extraction_method: "pymupdf-text | ocr-surya | ocr-marker | manual"
summary_model: "model used for L1/L2 generation"
verified: false  # Has a human checked the extraction quality?
```

## Ingestion Pipeline

### Step 1: Parse Source
- **Text-layer PDFs**: Extract with pymupdf (PyMuPDF)
- **Scanned PDFs**: OCR with Surya (best open-source for math/multilingual) or Marker (PDF→markdown with layout preservation)
- **LaTeX source**: Convert with pandoc, preserve math environments
- **Output**: `full-text.md` with section structure preserved

### Step 2: Extract Figures
- Extract embedded images from PDF
- For scanned docs, detect and crop figure regions
- Save to `figures/` with descriptive names
- Insert markdown image references in full-text.md

### Step 3: Verify LaTeX
- Post-processing pass to validate LaTeX formulas
- Common OCR errors: `l` vs `1`, `O` vs `0`, broken fraction bars
- Agent or human review of mathematical expressions
- Flag low-confidence extractions with `<!-- VERIFY: ... -->`

### Step 4: Generate Summaries
- **L2**: Agent skill — reads full-text.md section by section, produces compressed summary preserving mathematical precision
- **L1**: Agent skill — reads L2, produces structural overview
- **L0**: Agent skill — reads L1, produces one-sentence + one-paragraph abstract
- Each summary records the model used in metadata.yaml

### Step 5: Index
- Add entry to library INDEX.md
- Update any tag-based or topic-based indexes

## Quality Standards

- **Mathematical precision**: Never paraphrase a theorem incorrectly. When in doubt, quote verbatim.
- **Provenance**: Always record how text was extracted and who/what generated summaries.
- **Supersession**: If a better extraction or summary is produced, mark the old one as superseded, don't delete it.
- **Language**: Summaries should be in the same language as the source. For non-English sources, add English glosses for key terms in L1.
- **Verification**: Flag unverified OCR extractions. A `verified: false` document is still useful but should be treated with appropriate caution.

## OpenViking Compatibility

This structure is designed to be compatible with OpenViking's L0/L1/L2 tiered context loading:
- L0 (~100 tokens) = `.abstract` file
- L1 (~2K tokens) = `.overview` file  
- L2 (full content) = document content

If we adopt OpenViking as infrastructure, these files map directly to its filesystem paradigm.

## Tools

| Tool | Purpose | Status |
|------|---------|--------|
| `parse_pdf.py` | PDF → markdown extraction (text + OCR) | TODO |
| `extract_figures.py` | Figure detection and extraction | TODO |
| `verify_latex.py` | LaTeX formula validation | TODO |
| `summarize_l2.md` | Agent skill for L2 generation | TODO |
| `summarize_l1.md` | Agent skill for L1 generation | TODO |
| `summarize_l0.md` | Agent skill for L0 generation | TODO |
| `ingest.py` | Full pipeline: parse → extract → verify → summarize → index | TODO |
