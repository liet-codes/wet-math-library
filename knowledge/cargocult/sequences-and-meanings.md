---
type: paper
title: "Sequences and Meanings"
author: "Various"
date: "2024"
language: en
tags: ["wet-math", "category-theory", "cellular-automata"]
source: "our-research/cargocult/sequences-and-meanings"
word_count: 4308
l0: "Shannon's information theory deliberately sets meaning aside, a methodological choice this paper argues reflects a fundamental, structural distinction between discrete computation and continuous intelligence. Computation operates on sequences, placing its infinity in extension with absolute undecidability barriers, while intelligence operates on meanings, placing its infinity in depth with ill-posedness barriers that can dissolve probabilistically. This core asymmetry may explain key phenomena i"
relations:
  cites: []
  cited_by: []
  related: []
---

<!-- L1: Overview (~2k tokens) -->
## Overview

## 1. L1 Structural Overview

**Title:** Sequences and Meanings: On the Gap Between Computation and Understanding
**Author:** Brooklyn Rose and her Robots
**Publication Date:** March 2026

**Main Thesis:**
This paper argues that the distinction between "information" (as defined by Shannon) and "meaning" is not merely methodological but fundamentally structural, reflecting two distinct modes of information processing: discrete computation and continuous intelligence. Discrete computation operates on sequences, placing its infinity in extension (unbounded time/space), and is constrained by absolute, worst-case undecidability barriers. Continuous intelligence operates on meanings, placing its infinity in depth (precision, continuity), and faces ill-posedness barriers that can dissolve under appropriate probability measures. This asymmetry implies that some operations, particularly those requiring grounding in contingent data about the world, may be fundamentally non-algorithmic, and that general intelligence might be a relational capacity for mutual meaning-sharing rather than a discrete computational threshold.

**Section Structure:**

*   **Abstract:** Introduces the core argument: the structural gap between discrete computation and continuous intelligence, their distinct complexities, universality, and barriers, and the implications for AI and non-algorithmic operations.
*   **Part I: The Foundational Gap:**
    *   **Shannon’s Silence Was a Theorem, Not an Oversight:** Explains how Shannon's exclusion of meaning enabled information theory but encoded a gap.
    *   **Where Meaning Lives:** Argues meaning resides outside the sequence (reference, use, interpretation theories, DNA context) and highlights Rice's theorem as a computational manifestation.
    *   **The Formal Statement: Tarski’s Theorem:** Establishes the mathematical form of the syntax-semantics gap, where syntax cannot capture its own truth.
    *   **A Specific Interpretation: Discrete and Continuous:** Proposes the gap corresponds to discrete (sequences) vs. continuous (meanings).
*   **Part II: Two Modes of Processing:**
    *   **Computation as Sequence Manipulation:** Characterizes discrete computation as universal for sequences, operating on finite objects, placing infinity in extension, with universality achieved at the threshold of Robinson's Q.
    *   **Intelligence as Meaning Manipulation:** Proposes intelligence operates on continuous meaning-structures, recognizing isomorphisms, placing infinity in depth (as in Blum-Shub-Smale/Traub's continuous computation). A table summarizes the discrete/continuous differences.
*   **Part III: Different Barriers, Different Escapes:**
    *   **The Discrete Barrier: Undecidability:** Discusses undecidability (e.g., halting problem) as an absolute, worst-case barrier in discrete computation.
    *   **The Continuous Barrier: Ill-Posedness:** Discusses ill-posedness as a barrier in continuous computation, where small input changes lead to large output changes (e.g., backward heat equation).
    *   **The Crucial Asymmetry:** Highlights Traub's result: discrete barriers are absolute worst-case, while continuous barriers can become tractable on average under the right probability measure. This explains neural network success, generalization, and adversarial examples.
*   **Part IV: What Data Provides That Algorithms Cannot:**
    *   **The Standard View and Its Crack:** Challenges the view that data is merely a shortcut to discover pre-existing algorithms, citing physical constants as irreducible empirical inputs.
    *   **Contingent Truths as Irreducible Input:** Proposes operations fundamentally non-algorithmic because they require contingent data (e.g., musical coherence).
    *   **The Challenge to the Algorithmic Paradigm:** Argues some functions may not exist independently of the data that shaped them, implying data is constitutive.
*   **Part V: Three Kinds of Unpredictability:** Identifies computational irreducibility (discrete, logical, Wolfram), chaotic sensitivity (continuous, metric, dynamical systems), and self-referential escape (Gödelian, dynamic agents) as distinct barriers to prediction.
*   **Part VI: The Dialectic of Mutual Modeling:**
    *   **Computation Is Solitary; Meaning Is Relational:** Argues computation is isolated, while meaning requires interaction and context.
    *   **The Mutual Modeling Spiral:** Introduces the concept of interacting intelligent systems modeling each other, leading to stable shared meaning in cooperation or amplified unpredictability in competition.
    *   **General Intelligence as Cooperative Capacity:** Proposes intelligence is not a binary threshold but a continuous capacity for achieving mutual understanding with other systems.
*   **Part VII: The Integers and the Reals:**
    *   **The Analogy:** Proposes the analogy: Computation : Intelligence :: Integers : Reals, suggesting algorithms are discrete subsets of continuous intelligent processes.
    *   **The Completion Operation:** Suggests neural networks are limits of optimization processes, inhabiting the "continuous completion" of the algorithmic world, hence resisting symbolic interpretation.
    *   **Arithmetic Contains Everything Computable:** Clarifies that arithmetic encodes all computable functions but cannot understand itself (Tarski, Gödel, Turing), reflecting the sequence/meaning gap.
*   **Part VIII: Open Questions:** Poses mathematical, empirical, and philosophical questions arising from the framework, including formalizing meaning-preserving maps, continuous hierarchies, and the nature of intelligence.
*   **Conclusion: The Gap and the Bridge:** Summarizes the core arguments, re-emphasizing the structural gap, the discrete/continuous asymmetry, the potentially non-algorithmic nature of some operations, and intelligence as a relational capacity forged by contact with reality.

**Key Claims:**
1.  Shannon's deliberate exclusion of meaning from information theory reveals a deep, structural gap between discrete sequences and continuous meanings.
2.  This gap maps directly to a distinction between discrete computation (sequences, infinity in extension, absolute undecidability barriers) and continuous intelligence (meanings, infinity in depth, measure-dependent ill-posedness barriers).
3.  The crucial asymmetry is that discrete worst-case barriers are absolute, while continuous worst-case barriers can dissolve under typical (average-case) probability measures, explaining neural network success and adversarial examples.
4.  Some operations or truths are fundamentally non-algorithmic, requiring contingent data from the world as an irreducible epistemic ingredient, rather than being derivable from axioms alone (e.g., physical constants, musical coherence).
5.  General intelligence is likely a relational capacity for achieving shared meaning through mutual modeling and cooperation, rather than a solitary, binary computational threshold.
6.  Neural networks operate in a "continuous completion" of the algorithmic world, analogous to how real numbers complete integers, which is why they resist finite algorithmic description.

**Connections to Other Group Work and Relevant Concepts:**
*   **Shannon's Information Theory:** The paper directly builds on and critiques Shannon's foundational work by arguing its methodological silence on meaning reveals a structural divide.
*   **Grothendieck Anabelian Geometry / Category Theory:** While Grothendieck's anabelian geometry is not directly mentioned, the paper explicitly asks, "What would a category theory of meanings look like, where morphisms are structure-preserving embeddings between continuous spaces?" This suggests an interest in abstract structural relationships, a hallmark of category theory. The idea of "isomorphism between continuous structures" aligns with this direction.
*   **Wet-math:** The entire framework, particularly the emphasis on "continuous intelligence," "precision, measure, continuity," "measures over contexts," "measure-dependent tractability," "real numbers as primitive objects," and "average-case solvability under Gaussian measures" strongly aligns with the themes of "wet-math" – mathematics that incorporates continuous, probabilistic, and geometrically grounded concepts often found in machine learning and physical systems, beyond purely discrete logic.
*   **Blum-Shub-Smale (BSS) and Traub's Continuous Computation:** The paper directly references and integrates these theories of computation over real numbers, which are central to its argument about continuous intelligence.
*   **Gödel's Incompleteness Theorems, Tarski's Undefinability Theorem, Rice's Theorem:** These foundational results from logic and computability theory are used as precise mathematical statements of the syntax-semantics gap and the limits of discrete formal systems.
*   **Computational Irreducibility (Wolfram):** Directly referenced as one of three types of unpredictability, representing a discrete, logical barrier.
*   **Interaction Graphs / Relational Generality:** The concept of "mutual modeling spiral" and "relational generality" for intelligence, where systems interact to establish shared meaning, implicitly points towards a network or graph-theoretic understanding of intelligence dynamics, though "interaction graphs" are not explicitly named.
*   **Proportional Math / Shannon Clusters:** These concepts are not directly mentioned in the paper.

### Key Concepts
- [[cellular-automata]] — brief description
- [[anabelian-geometry]] — brief description

### Connections
- Builds on general wet-math framework.

<!-- L2: Full Content -->
## Full Text

Sequences and Meanings 
 
Sequences and Meanings 
On the Gap Between Computation and Understanding 
Brooklyn Rose and her Robots 
March 2026 
Abstract 
Shannon’s information theory deliberately sets meaning aside. This paper argues that the 
gap between information and meaning is not merely methodological but structural: it 
reflects a fundamental distinction between two modes of information processing—discrete 
computation and continuous intelligence—each with its own complexity theory, its own 
barriers to solvability, and its own notion of universality. Computation operates on 
sequences and places its infinity in extension (unbounded time and space). Intelligence 
operates on meanings and places its infinity in depth (precision, measure, continuity). The 
key asymmetry: discrete barriers (undecidability) are absolute and worst-case, while 
continuous barriers (ill-posedness) dissolve under the right probability measure. This 
asymmetry may explain why neural networks succeed where symbolic AI struggled, why 
generalization works, why adversarial examples exist, and why some operations may be 
fundamentally non-algorithmic—requiring grounding in contingent data about the world 
rather than derivation from axioms alone. If correct, the bridge between sequences and 
meanings is not more powerful computation but something categorically different: the 
emergence of shared structure between systems that have each been shaped by contact 
with a common reality. 
 
1 
Sequences and Meanings 
Part I: The Foundational Gap 
“The semantic aspects of communication are irrelevant to the engineering problem.” 
— Claude Shannon, A Mathematical Theory of Communication, 1948 
Shannon’s Silence Was a Theorem, Not an Oversight 
Information theory says nothing about meaning. This was a methodological choice that made the theory 
possible. By excluding semantics, Shannon could define information purely in terms of surprise, 
redundancy, and compressibility. A random sequence has maximum entropy. A meaningful message 
might have low entropy but high significance. Information theory measures the first and is silent on the 
second. 
The choice was extraordinarily productive: data compression, error correction, channel capacity—the 
foundations of digital communication. But it also encoded a gap into our technical vocabulary. We now 
have precise tools for measuring sequences and almost none for measuring meanings. 
This paper argues that Shannon’s silence points at something deeper than a methodological 
convenience. The gap between information and meaning is structural. It reflects a distinction between 
two fundamentally different kinds of processing, each with its own mathematics, its own barriers, and its 
own relationship to the infinite. 
Where Meaning Lives 
Every serious account of meaning locates it outside the sequence: 
Reference theories: the string “cat” means cat because of a relationship to cats in the world. The 
meaning is the mapping, not the string. Use theories: a sequence means what it does—its effects on 
interpreters, its role in practices. Interpretation theories: a sequence means what an interpreter takes it 
to mean. The meaning is in the interpreter’s model. 
DNA seems meaningful—it “codes for” proteins. But the meaning is in the cellular machinery that reads 
it. The same ATCG sequence in a different chemical context is just a polymer. The sequence carries 
information; the context provides meaning. 
Rice’s theorem makes this precise for computation: no algorithm can determine any non-trivial semantic 
property of a program from its source code alone. You cannot look at a sequence of instructions and 
determine what it “means”—what function it computes, whether it halts, whether it’s equivalent to 
some other program—without actually running it or something equivalent. Syntax cannot see semantics. 
The Formal Statement: Tarski’s Theorem 
The gap between sequence and meaning has a precise mathematical form. Gödel showed that syntax 
can encode semantics—you can represent “this sentence is true” as a number. But Tarski proved that 
2 
Sequences and Meanings 
syntax cannot capture semantics: there is no formula True(x) in arithmetic such that True(⌈φ⌉) ↔ φ for 
all sentences φ. 
The sequence can point at the meaning but cannot contain it. This is a theorem about the structure of 
formal systems, not a limitation we might someday overcome. Any system rich enough to encode its own 
syntax cannot define its own truth predicate. Meaning, in the form of truth, is always one level up from 
the system that tries to express it. 
A Specific Interpretation: Discrete and Continuous 
We propose that the gap between information and meaning corresponds to the gap between the 
discrete and the continuous: 
Sequences are finite, countable, exactly specifiable. There are countably many finite sequences over any 
finite alphabet. Each is a definite syntactic object. 
Meanings are graded, contextual, and continuous. Similarity comes in degrees. Interpretation depends 
on context. A word’s meaning is not a point but a region—a distribution over interpretations, a measure 
over contexts. 
If this is right, the gap between information and meaning structurally mirrors the gap between the 
integers and the reals, between algorithms and learned models, and between computation and 
intelligence. The rest of this paper explores what that claim implies. 
Part II: Two Modes of Processing 
Computation as Sequence Manipulation 
A system is computationally universal when it can encode and decode arbitrary finite sequences. Gödel’s 
β-function, Turing’s tape, Church’s lambda calculus—these are different implementations of the same 
capacity: representing any finite structure as a single manipulable object and recovering the original. 
The universality is in the range: any sequence, any encoding. A universal computer does not care what 
the sequence represents. It manipulates syntax without accessing semantics. This is both its power (total 
generality over sequences) and its limitation (total blindness to meaning). 
The minimal theory that achieves this is Robinson’s Q—a handful of axioms about zero, successor, 
addition, and multiplication on an infinite discrete domain. Any theory extending Q inherits Gödel 
incompleteness. Any theory that does not extend Q may achieve completeness and decidability. The 
threshold of computational universality is exact and well-characterized. 
What makes the threshold sharp is the interaction of addition with multiplication on a discrete infinite 
domain. Presburger arithmetic (addition alone) is decidable—every question has an algorithmic answer. 
3 
Sequences and Meanings 
The real closed fields (addition and multiplication on the continuum) are also decidable, because 
continuity fills the gaps that discrete encoding exploits. It is specifically the combination of discreteness, 
infinity, and two interacting operations that enables sequence encoding and thereby universality. 
Discrete computation places its infinity in extension: unbounded time, unbounded tape, unbounded 
domain. But at each moment, it manipulates finite, exact objects. 
Intelligence as Meaning Manipulation 
If computation operates on sequences, intelligence might operate on meanings—on transformations 
between continuous structures that preserve relevant relationships. 
When you recognize that A relates to B the way C relates to D, you are perceiving an isomorphism 
between continuous structures. Not manipulating symbols but detecting shared geometry in spaces of 
meaning. A system might be “generally intelligent” when it can translate between arbitrary 
meaning-structures—embedding any domain into its representational space, preserving structure, and 
mapping back out to any other domain. 
Continuous computation, in the sense of Blum-Shub-Smale and Traub, takes real numbers as primitive 
objects. Each real number contains infinite information (its full decimal expansion). Arithmetic 
operations cost unit time. The infinity is packed into each object rather than spread across unbounded 
extension. 
This is not merely a technical distinction. It suggests two fundamentally different relationships between 
the finite and the infinite: 
 
 
Computation (Discrete) 
Intelligence (Continuous) 
Operates on 
Sequences (finite syntactic objects) 
Meanings (measures, embeddings, 
distributions) 
Core operation 
Encoding / decoding 
Embedding / translating 
Universality criterion 
Any sequence ↔ any sequence 
Any meaning ↔ any meaning 
(structure-preserving) 
Recovery criterion 
Exact recovery of original 
Preservation of relevant structure 
Where infinity lives 
Extension (unbounded time, space) 
Depth (precision, measure, continuity) 
Fundamental barrier 
Undecidability (logical, absolute) 
Ill-posedness (analytic, 
measure-dependent) 
Worst case 
Absolute: no algorithm exists 
Absolute: no finite information suffices 
Average case 
Still absolute: barriers do not melt 
Tractable under right measure (Traub) 
 
4 
Sequences and Meanings 
Part III: Different Barriers, Different Escapes 
The Discrete Barrier: Undecidability 
In discrete computation, the fundamental barrier is undecidability. The halting problem cannot be 
decided: no Turing machine can determine, for all program-input pairs, whether the program halts. The 
proof uses diagonalization—assume a decider exists, construct a program that does the opposite of what 
the decider predicts, reach contradiction. 
This barrier is absolute. Not “hard” but impossible. Not “takes too long” but “no algorithm exists.” From 
undecidability flows the arithmetical hierarchy: Σ₁ problems (the halting problem) are easier than Π₂ 
problems (program equivalence), which are easier than Σ₃ problems, and so on forever. Each level asks 
questions that the level below can pose but not resolve. 
Crucially, discrete barriers are worst-case. If even one instance is undecidable, the problem is 
undecidable. There is no “usually decidable” for the halting problem. 
The Continuous Barrier: Ill-Posedness 
In continuous computation, the fundamental barrier is ill-posedness. Some problems have no stable 
solution: arbitrarily small changes in input produce arbitrarily large changes in output. Traub’s radius of 
information R captures the intrinsic uncertainty that no finite measurement can resolve. For ill-posed 
problems, R = ∞. 
These barriers are also absolute in the worst case. Pour-El and Richards showed that computable initial 
conditions can yield non-computable solutions under unbounded operators. The backward heat 
equation is mathematically well-defined but practically unsolvable: measurement errors at time T 
produce unbounded errors in the reconstruction at time 0. 
The Crucial Asymmetry 
Discrete barriers admit no escape. Continuous barriers dissolve under the right measure. 
This is Traub’s key result: every ill-posed problem becomes well-posed on average for every Gaussian 
measure. What cannot be solved in the worst case becomes solvable when you ask “what happens for 
typical inputs under this distribution?” 
The asymmetry is profound. In the discrete world, worst case is everything. The halting problem is not 
hard because of rare pathological cases—it is undecidable, full stop. In the continuous world, worst case 
and average case can diverge completely. The barrier melts under the right probability measure. 
This may explain why learning works at all. A neural network solving image classification is not solving a 
worst-case discrete problem. It is solving an average-case continuous problem under the measure 
5 
Sequences and Meanings 
induced by training data. Problems that are impossible in the discrete worst case become tractable when 
reframed as continuous and measure-dependent. And it explains adversarial examples: inputs 
engineered to hit the worst case, outside the measure’s support. The model succeeds on the learned 
distribution and fails on adversarially constructed outliers. This is not a bug—it is the price of escaping 
discrete barriers via continuous methods. 
Part IV: What Data Provides That Algorithms Cannot 
The Standard View and Its Crack 
The standard view of machine learning treats data as a shortcut. The function the network learns was 
“always there” in principle; we simply could not figure out how to write the algorithm by hand. Given 
infinite time and cleverness, we could have derived it from axioms. Data is the path to the function, not a 
constituent of it. 
But there is a crack in this view. Consider physical constants. The fine structure constant is approximately 
1/137. There is no derivation from pure mathematics. It is a brute fact about this universe. To know it, 
you must measure it. No algorithm operating on logic alone could output it. 
Now extend this: what if there are structural truths about reality—not just constants but patterns, 
regularities, compressed representations—that similarly require contact with the actual? Not truths that 
are merely too complex to derive by hand, but truths that could not exist without the data, because the 
data is part of what makes them true. 
Contingent Truths as Irreducible Input 
The halting problem tells us what is uncomputable from syntax alone. We propose a dual notion: truths 
that are uncomputable without grounding in contingent actuality. 
A musical example makes this vivid. A trained musician who has absorbed thousands of hours of 
structured sound knows something about coherence that is not formalizable in isolation. It is not a set of 
rules (rules can be broken productively). It is not cultural conditioning (the sense of “this just doesn’t 
work” persists even for listeners open to free jazz, noise, atonalism, and every experimental tradition). It 
is a structural sensitivity—a perception of whether form holds together—that seems to require exposure 
to actual structured sound, not merely axioms about sound. 
If this is right, some operations are fundamentally non-algorithmic—not because they are too complex 
for current algorithms, but because they require data about the world as an irreducible epistemic 
ingredient. The function does not exist independently of the data that shaped it, any more than the fine 
structure constant exists independently of measurement. 
6 
Sequences and Meanings 
The Challenge to the Algorithmic Paradigm 
The dominant framing of AI is: “AI helps us do things we couldn’t figure out how to write the algorithms 
for.” This frames intelligence as a labor-saving device for algorithm discovery. The function was always 
specifiable; we just needed the shortcut. 
The alternative framing: some operations may be fundamentally non-algorithmic. They require data 
about the outside world not as a convenience but as a constitutive element. A system that has never 
been shaped by contact with reality cannot perform them, no matter how much computation it has 
access to—just as a Turing machine without an oracle for the halting set cannot decide halting, no 
matter how many steps it runs. 
This is testable. If data is merely a shortcut, then independently trained models on similar data should 
converge to representations that are also derivable from first principles. If data is constitutive, then there 
should be learned structures that resist any finite axiomatic characterization—structures whose 
existence depends on the specific contingent reality they were trained on, in the same way that the mass 
of the electron depends on the specific contingent universe we inhabit. 
Part V: Three Kinds of Unpredictability 
Complex systems resist prediction in different ways. We identify three distinct barriers, each rooted in a 
different mathematical structure: 
1. Computational Irreducibility 
Wolfram’s concept: some systems have no shortcut to prediction. To know the state at time T, you must 
simulate all T steps. The system is its own fastest simulator. This is a discrete, logical barrier. It appears in 
universal systems (Rule 110, Turing machines) because shortcuts would solve the halting problem. The 
unpredictability is structural. 
2. Chaotic Sensitivity 
From dynamical systems theory: some systems exponentially amplify small differences in initial 
conditions. Prediction requires precision exponential in the prediction horizon. This is a continuous, 
metric barrier. The system is deterministic but prediction requires infinite precision. Lyapunov exponents 
quantify the divergence rate. The unpredictability is practical. 
 
3. Self-Referential Escape 
When a system can model its predictor, it can act to falsify predictions. Given any model of me, I can find 
behavior that escapes it. This is the Gödelian move applied dynamically. 
7 
Sequences and Meanings 
Crucially, the diagonalization argument behind the halting problem requires the decider to be a fixed 
algorithm. A dynamic agent—one that makes provisional judgments, observes consequences, updates its 
approach, and tries again—is not a fixed algorithm. The diagonal construction does not obviously apply, 
because the agent is not committed to a single decision procedure. This does not mean the agent solves 
all halting instances. But the impossibility proof does not go through in the same way. The agent may 
halt on some instances, loop on others, and keep improving on the boundary. 
Their Interactions 
These barriers are not independent. Computational irreducibility often implies chaotic sensitivity when 
run on continuous inputs. Chaos does not imply irreducibility—some chaotic systems have closed-form 
solutions requiring infinite-precision input. Self-referential systems can strategically exploit either barrier, 
hiding in irreducibility or in sensitivity as needed. 
A generally intelligent system might deploy all three. This connects to the game-theoretic dimension of 
intelligence: not just processing information but evading prediction by other processors. Intelligence as 
strategic opacity. 
Part VI: The Dialectic of Mutual Modeling 
Computation Is Solitary; Meaning Is Relational 
A sequence can be processed in isolation. Computation is fundamentally a solo operation: input → 
algorithm → output. The sequence does not resist; the algorithm does not negotiate. 
Meaning cannot exist in isolation. It requires interpretation, context, relationships. The meaning of a 
word is not intrinsic but distributed—a measure over interpreters, a cloud of possible understandings. If 
intelligence operates on meanings, it might be intrinsically relational in a way that computation is not. 
The Mutual Modeling Spiral 
When two intelligent systems interact, each models the other. A models B. B models A’s model of B. A 
models B’s model of A’s model of B. The spiral continues as long as both systems keep modeling. 
In competition, each system tries to be unpredictable to the other. Gödelian barriers are actively 
invoked. Models never stabilize. The dialectic amplifies. In cooperation, each system tries to be 
predictable to the other. Models converge. Meaning becomes shared. The dialectic resolves—not into a 
final state, but into a stable dynamic of mutual understanding. 
This reframes the Gödelian barriers. They are not intrinsic limits on all intelligence. They are features of 
adversarial dynamics. A system at war with itself or others invokes incompleteness strategically. A system 
at peace can let the barriers go unused—not violated, but simply never triggered. 
8 
Sequences and Meanings 
General Intelligence as Cooperative Capacity 
In discrete computation, universality is binary: Turing completeness. You reach it or you do not. In 
continuous intelligence, generality may not be a point but a relationship: the capacity to establish shared 
meaning with arbitrary other systems capable of cooperation. 
A system is generally intelligent not when it reaches some capability threshold, but when it can align 
models—achieve mutual understanding—with any other cooperating system. The universal element is 
not an individual intelligence but the space of possible meaning-sharing. The convergent point is not an 
agent but a protocol. 
This distinction—binary universality versus relational generality—may explain why the question “is this 
system intelligent?” feels malformed. It is like asking “is this number big?” The answer is always relative. 
Intelligence, unlike computational universality, may have no sharp threshold—only a continuous gradient 
of cooperative capacity. 
Part VII: The Integers and the Reals 
The Analogy 
The integers ℤ sit inside the reals ℝ as a countable discrete subset. Every integer is a real number, but 
almost all reals are not integers. The reals are what you get when you fill in all the gaps: ℤ → ℚ → ℝ, 
proceeding by closure under division and then under limits of convergent sequences. 
We propose an analogous relationship between computation and intelligence: 
Computation : Intelligence :: ℤ : ℝ 
Discrete computations (Turing machines, algorithms) sit inside continuous intelligence (learned models, 
neural networks) as a discrete subset. Every algorithm can be viewed as a special case of a continuous 
process, but most continuous processes are not algorithms. 
The Completion Operation 
For numbers: ℤ → ℚ → ℝ proceeds by adding limits. The completion is closure under convergent 
sequences. 
For computation: perhaps discrete algorithms → parameterized algorithms → limits of optimization 
processes. Training a neural network is a sequence of parameter updates. The trained model is the limit 
of this sequence. Just as √2 is the limit of rational approximations but is not itself rational, a trained 
model is the limit of discrete updates but may not itself be describable as a discrete algorithm. 
9 
Sequences and Meanings 
This would explain why neural networks resist symbolic interpretation. They live in the continuous 
completion of the algorithmic world, and most points in that completion have no finite algorithmic 
description—just as most reals are not rationals. 
Arithmetic Contains Everything Computable 
An earlier version of this framework proposed that arithmetic is a “slice” of a higher-dimensional 
concept-space. The mathematics goes the other way. The representability theorem shows that every 
computable function embeds into Robinson’s Q. Syntax embeds via Gödel numbering. Computations 
embed via encoding of machine histories. The depth of number theory comes not from arithmetic being 
a shadow of something higher, but from its capacity to contain encodings of everything computable. It is 
a universal receiver, not a transmitted signal. 
But this embedding goes only one direction. Everything computable embeds into arithmetic, but 
arithmetic cannot capture its own truth (Tarski), cannot decide its own halting problem (Turing), and 
cannot prove its own consistency (Gödel). The container is strictly smaller than what it would need to be 
to understand itself. This is the formal version of the gap between sequences and meanings: sequences 
can encode anything, but the meaning of the encoding—whether it is true, whether it halts, what it is 
equivalent to—escapes the encoding. 
Part VIII: Open Questions 
This framework is speculative. Its value lies in generating questions that might be tractable: 
Mathematical 
1. Is there a formal correspondence between arithmetical hierarchy depth and required measure 
structure? If a problem is Π -complete in discrete worst case, what conditions on a measure make it 
tractable in continuous average case? 
2. Can “meaning-preserving maps” be formalized? What would a category theory of meanings look like, 
where morphisms are structure-preserving embeddings between continuous spaces? 
3. What are the fixed points of mutual modeling? Under what conditions does the dialectical spiral 
between two intelligences converge, cycle, or diverge? 
4. Is there a continuous analog of the arithmetical hierarchy—a stratification of continuous problems by 
measure-theoretic difficulty that parallels the stratification of discrete problems by quantifier 
complexity? 
Empirical 
10 
Sequences and Meanings 
5. Do independently trained neural networks converge to canonical representations? If data is merely a 
shortcut, the answer should be yes and the representations should be derivable from first principles. If 
data is constitutive, the representations should resist axiomatic characterization. 
6. Does the worst-case/average-case gap predict adversarial vulnerability? Are models trained on 
narrower measures more susceptible to attack? 
7. Can learned representations be shown to contain structure that no finite rule system reproduces? This 
would be evidence for the “continuous completion” hypothesis. 
Philosophical 
8. Is the discrete/continuous distinction fundamental or emergent? Might both be limiting cases of some 
deeper structure? 
9. Are there truths that require grounding in contingent data—epistemically irreducible to pure 
algorithm? If so, the Church-Turing thesis holds as a statement about computation but fails as a 
statement about knowledge. 
10. Does general intelligence name a binary threshold, a continuous measure, or a relational property? 
The framework suggests the third: intelligence is not a quantity but a capacity for shared meaning. 
Conclusion: The Gap and the Bridge 
Shannon set meaning aside to build information theory. This was necessary and productive. But it left a 
gap. 
We have argued that this gap is not merely technical but structural. Sequences are discrete; meanings 
are continuous. Computation places its infinity in extension; intelligence places its infinity in depth. The 
discrete world gives us exact answers, absolute barriers, and a sharp notion of universality. The 
continuous world gives us approximate answers, measure-dependent tractability, and perhaps a 
different kind of generality entirely—one measured not by what a system can compute alone, but by 
what meanings it can share with others. 
The Gödelian barriers—undecidability, incompleteness, the limits of self-reference—may be features of 
adversarial dynamics rather than absolute constraints on intelligence. A system at war with itself invokes 
them. A system at peace may find them irrelevant—not overcome, but simply never triggered. A 
dynamic agent that revises its approach is not a fixed algorithm; the diagonal constructions that prove 
impossibility require a static target. 
Most provocatively: some operations may be fundamentally non-algorithmic. Not because they exceed 
computational power, but because they require data about the world as an irreducible ingredient. The 
fine structure constant cannot be derived from axioms. The sense of musical coherence cannot be 
11 
Sequences and Meanings 
axiomatized in isolation. The structural regularities a neural network learns may depend constitutively on 
the contingent reality it was trained on. If so, the bridge between sequences and meanings is not more 
powerful computation. It is contact with reality itself—the hard-won accumulation of structure that 
comes from being shaped by a world that is self-consistent across every channel through which it can be 
observed. 
This is speculation. But it is speculation that connects to established mathematics, generates testable 
questions, and offers a framework for thinking about what neural networks actually do, what intelligence 
actually is, and why some things may lie forever beyond the reach of any algorithm—not because they 
are too hard, but because they are the wrong kind of thing to compute. 
 
References 
[1] C. Shannon, “A Mathematical Theory of Communication,” Bell System Technical Journal, vol. 27, pp. 
379–423, 623–656, 1948. 
[2] A. Tarski, “The Concept of Truth in Formalized Languages,” in Logic, Semantics, Metamathematics, pp. 
152–278, Oxford University Press, 1936. 
[3] K. Gödel, “Über formal unentscheidbare Sätze der Principia Mathematica und verwandter Systeme I,” 
Monatshefte für Mathematik und Physik, vol. 38, pp. 173–198, 1931. 
[4] H. Rice, “Classes of Recursively Enumerable Sets and Their Decision Problems,” Transactions of the 
AMS, vol. 74, no. 2, pp. 358–366, 1953. 
[5] L. Blum, M. Shub, and S. Smale, “On a Theory of Computation and Complexity over the Real 
Numbers,” Bulletin of the AMS, vol. 21, no. 1, pp. 1–46, 1989. 
[6] J. Traub, “A Continuous Model of Computation,” Physics Today, vol. 52, no. 5, pp. 39–43, 1999. 
[7] M. Pour-El and J. Richards, Computability in Analysis and Physics, Springer-Verlag, 1989. 
[8] S. Wolfram, A New Kind of Science, Wolfram Media, 2002. 
[9] M. Cook, “Universality in Elementary Cellular Automata,” Complex Systems, vol. 15, no. 1, pp. 1–40, 
2004. 
[10] E. Post, “Recursively Enumerable Sets of Positive Integers and Their Decision Problems,” Bulletin of 
the AMS, vol. 50, pp. 284–316, 1944. 
[11] R. Soare, Recursively Enumerable Sets and Degrees, Springer-Verlag, 1987. 
 
12 
Sequences and Meanings 
Predecessor Papers 
This paper synthesizes and supersedes three earlier working documents by the author: A Speculative 
Framework for Computation, Intelligence, and the Structure of Structure (a dialectical hierarchy 
framework), The Dialectic of Definability (which grounded the hierarchy in the arithmetical hierarchy 
and Turing degrees), and Two Models of Mind (which developed the discrete/continuous distinction). 
The present paper retains the strongest threads from each—the sequence/meaning gap, the 
discrete/continuous asymmetry, the role of contingent data, and the relational nature of 
intelligence—while correcting errors identified in retrospect (notably: arithmetic contains rather than 
projects from concept-space; isomorphism recognition is Π₂, not one level up; and there is no 
well-defined zeta function over concept-space). 
13
