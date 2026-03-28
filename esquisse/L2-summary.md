An L2 summary of Alexander Grothendieck's "Sketch of a Programme".

## Introduction

This document provides a detailed, section-by-section summary of Alexander Grothendieck's "Sketch of a Programme," written in January 1984 as part of an application to the French Centre National de la Recherche Scientifique (CNRS). In this text, Grothendieck outlines the main themes of his mathematical reflections from roughly 1972 to 1984, a period after he had ceased conventional publication. The "Sketch" is not merely a list of problems but a visionary outline for several vast research programs, revealing a profound shift in his mathematical focus from abstract, general structures to more concrete, intuitive objects, primarily the geometry of surfaces. These simple objects, he argues, serve as a gateway to some of the deepest questions in algebraic geometry, number theory, and topology. The document is unified by the central role of two-dimensional geometry and its unexpected connections to the absolute Galois group of the rational numbers, $\text{Gal}(\overline{\mathbb{Q}}/\mathbb{Q})$.

---

## 1. Preface

Grothendieck begins by stating his motivation for applying to the CNRS. He feels that his university teaching has become illusory and wishes to dedicate his energy to developing research projects that he believes no one else is positioned or inclined to pursue. He refers to two voluminous boxes of handwritten notes from the previous twelve years, which form the basis for the proposed work. He clarifies that his intention is not merely to compile these notes but to actively develop the ideas within them, a process of discovery rather than transcription. The "Sketch" is intended to serve as his work program for the coming years, aimed at the CNRS committee and any colleagues who might find the ideas inspiring.

---

## 2. A game of “Lego-Teichmüller” and the Galois group $\overline{\mathbb{Q}}$ over $\mathbb{Q}$

This section introduces the central and most developed theme of the program, which arose from a shift in Grothendieck's focus. Previously centered on maximal generality in algebraic geometry, his teaching led him to explore the intuitive, two-dimensional topology of surfaces. This path unexpectedly led back to the foundations of algebraic geometry—the study of algebraic curves—and their deep connections to number theory.

### Core Argument

The geometry of surfaces, particularly the study of moduli spaces of algebraic curves, provides a concrete and powerful framework for studying the absolute Galois group $\Gamma = \text{Gal}(\overline{\mathbb{Q}}/\mathbb{Q})$.

### Key Objects and Constructions

*   **Moduli Stacks of Curves:** The central objects of fascination are the moduli stacks (which Grothendieck calls "multiplicities" to emphasize the presence of non-trivial automorphism groups) $\mathcal{M}_{g,\nu}$ of non-singular algebraic curves of genus $g$ with $\nu$ marked points, and their compactifications $\overline{\mathcal{M}}_{g,\nu}$ by Mumford and Deligne, which include "stable" singular curves.

*   **The Teichmüller Tower:** This is the system of all moduli stacks $\{\mathcal{M}_{g,\nu}\}_{g,\nu}$ considered together, linked by fundamental geometric operations:
    *   **Plugging holes:** Forgetting a marked point, corresponding to a map $\mathcal{M}_{g,\nu+1} \to \mathcal{M}_{g,\nu}$.
    *   **Glueing:** Constructing a singular curve by identifying two marked points, an operation that links different moduli spaces.

*   **Teichmüller Groupoids:** The fundamental groupoids of the moduli spaces, denoted $\mathfrak{T}_{g,\nu} = \pi_1(\mathcal{M}_{g,\nu}(\mathbb{C}))$. Their profinite completions are denoted $\widehat{\mathfrak{T}}_{g,\nu}$. The "tower" of these groupoids inherits a rich structure from the geometric operations on the moduli stacks.

### The Action of the Galois Group

*   Since the moduli stacks $\mathcal{M}_{g,\nu}$ are defined over $\mathbb{Q}$, the absolute Galois group $\Gamma = \text{Gal}(\overline{\mathbb{Q}}/\mathbb{Q})$ acts on the entire tower of profinite Teichmüller groupoids $\widehat{\mathfrak{T}}_{g,\nu}$.
*   **Faithfulness of the Action:** Grothendieck states as an extraordinary fact that this action is **faithful**. It is already faithful on the first non-trivial level, $\widehat{\mathfrak{T}}_{0,4}$.
*   The space $\mathcal{M}_{0,4}$ is essentially $\mathbb{P}^1 \setminus \{0, 1, \infty\}$. Its fundamental group, $\pi_{0,3}$, is a free group on two generators. The faithfulness of the action of $\Gamma$ on $\widehat{\mathfrak{T}}_{0,4}$ is equivalent to the faithfulness of the outer action of $\Gamma$ on the profinite completion $\widehat{\pi}_{0,3}$.
*   **A New Description of $\Gamma$:** This realization allows one to view $\Gamma$ as a subgroup of the outer automorphism group $\text{Out}(\widehat{\pi}_{0,3})$. A central, though perhaps "out of reach," goal is to find a purely group-theoretic characterization of the elements of $\text{Out}(\widehat{\pi}_{0,3})$ that belong to the image of $\Gamma$. This would provide a description of the Galois group of $\mathbb{Q}$ without reference to number fields.

### A Conjectural Construction Principle for the Tower

*   Grothendieck proposes a principle for reconstructing the entire Teichmüller tower from its first two "levels," defined by the modular dimension $N = 3g-3+\nu$.
    *   **Level 1 ($N=1$):** The spaces $\mathcal{M}_{0,4}$ and $\mathcal{M}_{1,1}$ provide a complete system of **generators** for the tower via the "glueing" operation.
    *   **Level 2 ($N=2$):** The spaces $\mathcal{M}_{0,5}$ and $\mathcal{M}_{1,2}$ provide a complete system of **relations**.
*   He notes a striking analogy with Demazure's principle for the structure of reductive algebraic groups, where groups of semi-simple rank 1 and 2 play a similar foundational role. The link is reinforced by the fact that the discrete Teichmüller group $T_{1,1}$ is isomorphic to $SL(2, \mathbb{Z})$, the integral points of the simple group scheme of rank 1, $SL(2)_{\mathbb{Z}}$.

### The "Lego-Teichmüller" Game

*   To understand the combinatorial structure of the tower, Grothendieck proposes a "game of Lego-Teichmüller."
*   The "building blocks" are surfaces with boundary (where marked points become "holes") corresponding to curves with large automorphism groups. There are 12 fundamental blocks (6 of genus 0, 6 of genus 1).
*   Assembling these blocks provides a visual method for constructing any topological surface and for understanding the generators (e.g., "twists") and relations of the Teichmüller groups.
*   This approach is very close to William Thurston's work on hyperbolic geodesic surgery, which Grothendieck had recently learned about.
*   These building blocks come with canonical cellular decompositions, which in turn define canonical algebraic curves over $\overline{\mathbb{Q}}$, creating a deep interplay between combinatorics and arithmetic geometry.

---

## 3. Number fields associated to a child’s drawing

This section elaborates on the origins of the connection between combinatorics and number theory, which Grothendieck calls one of the most striking mathematical facts he has ever encountered.

### Core Argument

There is a profound and canonical correspondence between combinatorial maps on surfaces (which he calls "dessins d'enfants" or "child's drawings") and algebraic curves defined over the field of algebraic numbers, $\overline{\mathbb{Q}}$. This correspondence makes the absolute Galois group $\text{Gal}(\overline{\mathbb{Q}}/\mathbb{Q})$ act on these combinatorial objects.

### Key Objects and Constructions

*   **Maps and the Cartographic Group:** A "map" is a decomposition of a compact surface $X$ into vertices, edges, and faces by a graph $K$. The combinatorial structure of an oriented map can be described algebraically by a finite set with an action of the **oriented cartographic group**:
    $$ C_2^+ = \langle \rho_s, \rho_f, \sigma \mid \rho_s \rho_f = \sigma, \sigma^2 = 1 \rangle $$
    The generators correspond to elementary rotations of a flag (an edge incident to a vertex and a face) around a vertex ($\rho_s$), a face ($\rho_f$), and an edge ($\sigma$).

*   **The Bridge to Algebraic Geometry:** Grothendieck makes the crucial observation that $C_2^+$ is a quotient of the fundamental group of $\mathbb{P}^1_{\mathbb{C}} \setminus \{0, 1, \infty\}$. The loops around $0, \infty, 1$ correspond to $\rho_s, \rho_f, \sigma$ respectively.
*   A finite oriented map corresponds to a finite-sheeted covering of $\mathbb{P}^1_{\mathbb{C}}$ ramified only over the points $\{0, 1, \infty\}$.
*   By Riemann's existence theorem, such a covering is given by a morphism $f: X \to \mathbb{P}^1_{\mathbb{C}}$ from a unique compact Riemann surface (algebraic curve) $X$.
*   Since the base curve $\mathbb{P}^1$ and the ramification points $\{0, 1, \infty\}$ are defined over $\mathbb{Q}$, the curve $X$ and the map $f$ are defined over the algebraic closure $\overline{\mathbb{Q}}$.
*   The "dessin d'enfant" itself can be recovered as the preimage $f^{-1}([0,1])$ on the curve $X$. The points above 0 are the vertices, the points above 1 are the midpoints of edges, and the points above $\infty$ are the centers of faces.

### Belyi's Theorem and its Consequences

*   This discovery led Grothendieck to a question he considered "crazy": can *every* algebraic curve defined over a number field be obtained in this way?
*   The affirmative answer was provided shortly after by G. V. Belyi. **Belyi's Theorem** states that a projective non-singular algebraic curve is defined over a number field if and only if it admits a morphism to $\mathbb{P}^1$ ramified only over $\{0, 1, \infty\}$.
*   Grothendieck views this as a result of "considerable importance," establishing a "profound identity between the combinatorics of finite maps... and the geometry of algebraic curves defined over number fields."

### Anabelian Algebraic Geometry

*   This discovery was the starting point for what Grothendieck terms **anabelian algebraic geometry**. This field studies the extent to which certain algebraic varieties (the "anabelian" ones) can be reconstructed from their profinite fundamental groups, equipped with the natural outer action of the absolute Galois group of the base field.
*   An algebraic curve is anabelian if its Euler characteristic is negative, i.e., $2g-2+\nu > 0$.
*   **The Fundamental Conjecture of Anabelian Algebraic Geometry:** An anabelian variety over a number field $K$ is determined up to isomorphism by its "mixed fundamental group," which is the group extension $1 \to \pi_1(X_{\overline{K}}) \to \pi_1(X_K) \to \text{Gal}(\overline{K}/K) \to 1$.
*   A key result, which Grothendieck views as essentially equivalent to Belyi's theorem, is that the outer action of $\text{Gal}(\overline{\mathbb{Q}}/\mathbb{Q})$ on the profinite geometric fundamental group of *any* anabelian curve defined over $\overline{\mathbb{Q}}$ is faithful.

### The Central Role of $SL(2, \mathbb{Z})$

*   The profinite completion $\widehat{SL(2, \mathbb{Z})}$ is a key anabelian group. Belyi's theorem implies that the fundamental groups of all algebraic curves over number fields can be obtained as quotients of finite index subgroups of $\widehat{SL(2, \mathbb{Z})}$.
*   Therefore, the single outer action of $\Gamma$ on $\widehat{SL(2, \mathbb{Z})}$ contains, in a sense, all the information about the Galois action on the fundamental groups of all curves over number fields. This includes all the abelian $\ell$-adic representations associated with their Jacobians.
*   Grothendieck describes $\widehat{SL(2, \mathbb{Z})}$ as a "machine for constructing 'motivic' representations" of $\Gamma$.

---

## 4. Regular polyhedra over finite fields

This section extends the combinatorial-geometric theme to the more structured case of regular maps and their geometric realizations as polyhedra, exploring what happens when the base field is not $\mathbb{R}$ or $\mathbb{C}$.

### Core Argument

The theory of regular polyhedra becomes infinitely richer when one considers base fields of non-zero characteristic. Specializing infinite regular polyhedra (tilings) defined over number fields to finite fields $\mathbb{F}_p$ generates infinite new families of finite regular polyhedra, whose combinatorial types vary "arithmetically" with the prime $p$.

### Key Objects and Constructions

*   **Regular Maps:** These are maps whose automorphism group acts transitively on the set of flags. In the algebraic-geometric interpretation, they correspond to **Galois coverings** of $\mathbb{P}^1$.
*   **Universal Polyhedra:** Grothendieck describes a "universal" pinned $n$-dimensional polyhedron defined over a polynomial ring $\mathbb{Z}[\alpha_1, \dots, \alpha_n]$. The variables $\alpha_i$ are geometric parameters (doubles of cosines of the "fundamental angles"). Any specific regular polyhedron over a field $k$ is obtained by specializing the $\alpha_i$ to values in $k$.
*   **From Infinite to Finite:** The classical theory over $\mathbb{R}$ yields the finite Platonic solids and the infinite regular tilings of the Euclidean and hyperbolic planes. An infinite tiling can be viewed as a polyhedron defined over a number field. By reducing its defining equations modulo various primes $p$, one obtains a regular polyhedron over the finite field $\mathbb{F}_p$. Since any polyhedron over a finite field must be finite, this process generates an infinite family of new, finite combinatorial structures.
*   **A Central Question:** Which finite regular maps can be realized as regular polyhedra over finite fields?

### The Combinatorial Paradigm

*   Grothendieck observes a recurring "miracle" he calls the **combinatorial paradigm**. When a classical polyhedron (like the icosahedron) is specialized to one of its "most singular" characteristics (e.g., characteristic 2 or 5 for the icosahedron), the resulting geometric object over the finite field provides a particularly elegant and unexpected description of the original combinatorial structure. He intuits this to be a principle of great generality.

---

## 5. Denunciation of so-called “general” topology, and heuristic reflections towards a so-called “tame” topology

Here, Grothendieck argues for a complete refoundation of topology to suit the needs of geometry, criticizing standard point-set topology for being plagued by "wild" phenomena irrelevant to the intuition of shapes.

### Core Argument

General topology is fundamentally inadequate for geometric purposes. A new framework, **tame topology**, is needed to provide a context free of "pathological" objects, where essential geometric constructions like the "dévissage" of stratified spaces are well-behaved and canonical.

### Motivation: The Dévissage of Stratified Structures

*   The central motivating problem is to define a canonical way to decompose a stratified space (e.g., a singular algebraic variety, or the compactified moduli space $\overline{\mathcal{M}}_{g,\nu}$) into its constituent strata ("building blocks") and describe the "glueing" data that reassembles them.
*   In standard topology, this is obstructed by the non-canonicity of constructions like tubular neighborhoods and by "wild" behavior (e.g., a cone over a non-sphere can be a manifold at its vertex).

### The Proposal for Tame Topology

*   **Axiomatic Approach:** Instead of fixing one class of objects, Grothendieck proposes an axiomatic definition of a "tame theory." A theory would be defined by specifying a collection of "tame subsets" of each $\mathbb{R}^n$ that is closed under a robust set of geometric operations (Boolean operations, products, projections, etc.) but excludes wild sets.
*   **Examples of Tame Theories:**
    *   Piecewise $\mathbb{Q}_r$-algebraic sets (where $\mathbb{Q}_r = \mathbb{Q} \cap \mathbb{R}$).
    *   Piecewise $\mathbb{R}$-algebraic sets.
    *   Semi-analytic sets (in the sense of Hironaka).
*   **Expected Results:** Within a tame framework, one should be able to