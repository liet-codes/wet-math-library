# L1-Summary: Sketch of a Programme

-   **Title**: Sketch of a Programme (Esquisse d'un Programme)
-   **Author**: Alexandre Grothendieck
-   **Date**: January 1984
-   **Context**: A research proposal submitted to the French National Centre for Scientific Research (CNRS). It outlines the mathematical themes Grothendieck pursued in relative isolation from 1970 to 1984 and serves as a visionary blueprint for future research. The document marks a shift from the abstract, general framework of his earlier work (schemes, topoi) to more concrete, geometric, and combinatorial problems, primarily rooted in two-dimensional topology and its connection to number theory.

### Structural Overview

The programme is organized into ten sections, outlining a vast, interconnected research landscape.

1.  **Preface**: Introduces the document as a CNRS application and a summary of his mathematical reflections since ceasing publication in 1970.
2.  **A game of “Lego-Teichmüller” and the Galois group $\overline{\mathbb{Q}}$ over $\mathbb{Q}$**: Proposes studying the "Teichmüller tower" of moduli spaces of curves and the faithful action of the absolute Galois group $\text{Gal}(\overline{\mathbb{Q}}/\mathbb{Q})$ on its structure.
3.  **Number fields associated to a child’s drawing**: Introduces *dessins d'enfants* (child's drawings), combinatorial graphs on surfaces that, via Belyi's theorem, correspond to algebraic curves defined over number fields, revealing a surprising link between combinatorics and arithmetic geometry.
4.  **Regular polyhedra over finite fields**: Generalizes the classical theory of regular polyhedra from base field $\mathbb{R}$ to arbitrary fields, especially finite fields, uncovering a much richer universe of combinatorial structures.
5.  **Denunciation of so-called “general” topology, and heuristic reflections towards a so-called “tame” topology**: Critiques standard point-set topology for its pathological ("wild") phenomena and proposes an axiomatic foundation for a "tame topology" suitable for a theory of *dévissage* (disassembly/reassembly) of stratified spaces.
6.  **“Differentiable theories” (`a la Nash) and “tame theories”**: Recalls an earlier axiomatic approach to defining classes of "well-behaved" differentiable functions and connects it to the proposed tame topology.
7.  **Pursuing Stacks**: Briefly describes his then-current work on the foundations of higher category theory and homotopy theory, particularly the idea of using $\infty$-groupoids as models for homotopy types.
8.  **Digressions on 2-dimensional geometry**: Mentions other undeveloped research themes in low-dimensional topology, such as immersed curves on surfaces and systems of pseudo-lines.
9.  **Assessment of a teaching activity**: A personal reflection on his university teaching experience, which he considers a failure in terms of fostering a research community.
10. **Epilogue**: Concludes by emphasizing the profound unity of the proposed themes, all stemming from the geometry of surfaces, and his new, "lighter" approach to mathematical exploration.

### Main Thesis and Key Ideas

The central thesis is that the geometry of surfaces provides a powerful, unifying framework for exploring deep, unsuspected connections between number theory, algebraic geometry, and topology. The programme aims to build a "Galois-Teichmüller Theory" by studying the action of the absolute Galois group on geometric and combinatorial objects.

-   **Anabelian Algebraic Geometry**: This is the programme's core. It posits that certain algebraic varieties, termed "anabelian" (e.g., those with hyperbolic uniformization), are entirely determined by their profinite étale homotopy type, including the action of the absolute Galois group on it. The ultimate goal is a purely group-theoretic description of the category of schemes over $\mathbb{Q}$, effectively "reconstituting" geometry from fundamental groups.
-   **The Teichmüller Tower**: The collection of Teichmüller groupoids $\{\mathbb{T}_{g,\nu}\}$, which are the fundamental groupoids of the moduli spaces of curves $\mathcal{M}_{g,\nu}$, forms a tower-like structure connected by geometric operations (gluing surfaces, forgetting marked points). Grothendieck conjectures this tower has a presentation by generators (from dimension 1 moduli spaces) and relations (from dimension 2), and that $\text{Gal}(\overline{\mathbb{Q}}/\mathbb{Q})$ acts faithfully on its profinite completion.
-   ***Dessins d'Enfants***: Based on Belyi's theorem, which states that any algebraic curve over $\overline{\mathbb{Q}}$ is a ramified cover of $\mathbb{P}^1$ over just three points ($\{0, 1, \infty\}$), Grothendieck establishes a dictionary between such curves and *dessins d'enfants*—bipartite graphs embedded in surfaces. This transforms the action of $\text{Gal}(\overline{\mathbb{Q}}/\mathbb{Q})$ on algebraic curves into a concrete, combinatorial action on these drawings.

### Key Mathematical Objects

-   The absolute Galois group $\text{Gal}(\overline{\mathbb{Q}}/\mathbb{Q})$.
-   Moduli stacks of algebraic curves with marked points, $\mathcal{M}_{g,\nu}$, and their Deligne-Mumford compactifications, $\overline{\mathcal{M}}_{g,\nu}$.
-   Teichmüller groups/groupoids $\mathbb{T}_{g,\nu} = \pi_1(\mathcal{M}_{g,\nu})$ and their profinite completions $\widehat{\mathbb{T}}_{g,\nu}$.
-   The profinite fundamental group of the projective line minus three points, $\widehat{\pi}_1(\mathbb{P}^1_{\overline{\mathbb{Q}}} \setminus \{0, 1, \infty\})$.
-   *Dessins d'enfants* and the cartographic group.
-   The modular group $SL(2, \mathbb{Z})$ and its profinite completion $\widehat{SL(2, \mathbb{Z})}$.

### Relevance to Modern Mathematics

-   **Higher Category Theory, ∞-groupoids, Homotopy Types**: Section 7, on *Pursuing Stacks*, lays out the "Grothendieck hypothesis" that homotopy types are best modeled by $\infty$-groupoids. This is a foundational principle of modern homotopy theory and higher topos theory. The Teichmüller tower itself is naturally a higher-categorical object.
-   **Non-commutativity and Commutators**: The entire programme is built on the study of non-abelian fundamental groups, where commutators and outer automorphism groups are the central objects of study, in stark contrast to the abelian focus of class field theory.
-   **Galois Theory and Algebraic Closure**: The programme proposes a radical extension of Galois theory. Instead of studying automorphisms of fields like the algebraic closure $\overline{\mathbb{Q}}$, it seeks to characterize the group $\text{Gal}(\overline{\mathbb{Q}}/\mathbb{Q})$ itself through its faithful geometric action on the "Teichmüller tower," a vast non-abelian object.
-   **Scale Geometry**: This specific term does not appear in the text. The programme's focus is on the discrete, combinatorial, and arithmetic properties of geometric objects, rather than on metric or spectral properties at varying scales.