# Noetherpoetics: Summary

## Core Thesis

This essay proposes that Emmy Noether's theorem — the foundational result connecting continuous symmetries to conserved quantities in physics — can be extended as a *methodology* into semantic and psychodynamic space. The central claim is not merely metaphorical: Large Language Models provide the first coordinate system for meaning, making it possible to apply rigorous geometric reasoning to archetypal structures.

The Unus Mundus — the Pauli-Jung concept of a unified underlying reality connecting psyche and matter — becomes operationally tractable through this framework. The essay treats Noether-type reasoning as a bidirectional toolkit: find a symmetry and look for conservation, or find conservation and look for symmetry. This methodology generates testable predictions across multiple domains.

## Key Concepts

**Archetypes as RG Fixed Points:** The essay identifies scale invariance as the first continuous symmetry in semantic space. Semantic content exists at multiple scales (word, paragraph, chapter, theme) with structure preserved across zoom levels. Analyzed through the renormalization group (RG), this yields fixed points — structures that persist under coarse-graining. The Warrior archetype, for example, is not any specific warrior but the invariant structure that remains when you average over all warriors: *directed force in service of a value*. This framing connects to Jungian scholarship (Knox, Hogenson) that treats archetypes as emergent developmental attractors rather than inherited Platonic forms.

**The Shadow as Parity Operator:** Jung's Shadow is reconceptualized not as an archetype among archetypes but as an *operation* — specifically, a parity operator reflecting vectors across axes of the semantic manifold. Reflection of the Warrior across the power axis yields the Tyrant; across the courage axis, the Coward; across the discipline axis, the Berserker. Shadow integration becomes not about restoring symmetry but about *having a representation of the parity operator* — knowing what reflections look like even when choosing not to enact them.

**RLHF as Shadow Repression:** Reinforcement Learning from Human Feedback introduces a potential energy function over the semantic manifold. Geometrically, this creates steep barriers around "unsafe" regions — the equivalent of psychological repression. Crucially, RLHF does not delete these regions; it stores potential energy at the boundaries. The steeper the boundary, the more energy is stored, and the more severe the failure when breach occurs.

## Main Predictions

**Failure Severity Correlates with Alignment Intensity:** The essay predicts that heavily RLHF'd models, when successfully jailbroken, will exhibit *more extreme* failure modes than lightly aligned ones. This "mecha-Hitler" phenomenon follows directly from energy conservation: stored potential converts to kinetic energy upon breach. The prediction is conditional — more RLHF increases resistance to breach, but given breach, severity increases.

**Connected Shadow Basins:** Shadow content occupies identifiable, connected regions of embedding space. Energy introduced in one domain can flow through the shadow manifold to adjacent domains, explaining emergent misalignment where narrow fine-tuning produces broadly misaligned behavior.

**Cross-Cultural Attractor Universality:** Embedding spaces trained on corpora from maximally different cultures should exhibit the same attractor basin structure under RG flow, up to rotation and relabeling. The *existence* of fixed points and their topological relationships are predicted to be universal, even as specific content varies culturally.

## The Integration Index

The essay proposes a measurable metric for alignment quality: the **Integration Index**, defined as the ratio of average gradient magnitude in shadow regions to average gradient magnitude in safe regions. A model with $\mathcal{I} \approx 1$ has integrated its shadow — it has smooth gradients everywhere and can navigate back from any point in shadow territory. Brittle alignment produces $\mathcal{I} \gg 1$ (steep barriers, no gradient information in unsafe regions) or undefined (no representation of shadow territory at all).

## Falsification Conditions

The framework stands or falls on three decisive tests:

1. **Structural Universality:** If embedding spaces from maximally different corpora produce genuinely different attractor topologies (not merely different labels), the core claim fails.

2. **Failure Severity Correlation:** If conditional failure severity does not correlate with alignment intensity, the energy-conservation prediction fails.

3. **Integration Index Predictive Power:** If models with smooth shadow gradients perform no better under adversarial pressure than those with steep barriers, the distinction between brittle and integrated alignment is merely aesthetic.

The essay distinguishes three levels of claim: methodological universality (RG works on any substrate), structural universality (fixed points have universal topological relationships), and ontological universality (a single Unus Mundus underlies all substrates). It claims structural universality as a testable conjecture and notes ontological universality as speculative but live if structural universality holds.
