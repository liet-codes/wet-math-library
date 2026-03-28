# L2-Summary: Pursuing Stacks, First Episode: The Modelizing Story

This document provides a detailed section-by-section summary of Alexander Grothendieck's "Pursuing Stacks (À la poursuite des Champs), First episode: The modelizing story (histoire de modèles)".

## Preface

The preface, a translation of a section from Grothendieck's 1984 "Esquisse d’un Programme", frames the work as a reflection on the foundations of non-commutative (co)homological algebra, which he equates with homotopical algebra. He states that for nearly twenty years, fundamental questions about the basic structures underlying homotopy theory have been ripe for investigation but largely ignored. While acknowledging Quillen's work on model categories, he notes it goes in a different direction from his own interests, which focus on the internal structures of derived categories and the natural "coefficients" for a non-commutative cohomological formalism beyond the 1-stacks of Giraud.

The impetus for this work was a 1975 correspondence with Larry Breen, where the intuition that ∞-groupoids should be adequate models for homotopy types first appeared. He notes that Ronnie Brown and his students in Bangor independently discovered a similar intuition, but using a notion of ∞-groupoid that Grothendieck found too restrictive. This correspondence ultimately spurred him to begin the work that became "Pursuing Stacks".

He describes "The Modelizing Story" as an "unintended digression" from the main project on stacks. He also connects this work to other themes, such as a "De Rham complex with divided powers" and the idea of a "schematization" of homotopy types, which he plans to explore in a hypothetical chapter. He views this work as paying a debt to his past focus on cohomological tools in algebraic geometry (1955-1970), renewed not out of nostalgia but because of the numerous unexpected phenomena that continually arise.

---

## Part I: Take-off

This part consists of a long letter to Daniel Quillen, written over several days in February 1983, outlining the initial ideas and motivations for the project.

### §1 The importance of innocence.

Grothendieck begins by noting the lack of substantial progress in understanding the basic structures of homotopy and homological algebra since Quillen's work in the 1960s. He suggests this is due to a "wind of disrepute for any foundational matters." He argues that, even more strikingly, topology itself lacks proper foundations, specifically a context of "tame" topology. He believes developing such a theory for "stratified (tame) spaces" would have an impact on geometric topology comparable to the introduction of schemes in algebraic geometry.

### §2 A short look into purgatory.

Grothendieck critiques the work of the "Bangor group" (Ronnie Brown and his collaborators). While they share the intuition that n-truncated homotopy types are equivalent to n-groupoids, their notion of ∞-groupoid is too restrictive. By insisting on strict associativity of compositions, their framework can only model simply connected homotopy types that are products of Eilenberg-MacLane spaces, making it inadequate for a general foundational theory.

This motivates him to outline the data for a more general ∞-groupoid:
*   Sets of i-objects $F_i$ for $i \in \mathbb{N}$.
*   Source, target, and identity maps: $s_1^i, t_1^i: F_i \to F_{i-1}$ (for $i \ge 1$) and $k_1^i: F_i \to F_{i+1}$ (for $i \in \mathbb{N}$).
*   Inversion maps: $\text{inv}_i: F_i \to F_i$ (for $i \ge 1$).
*   Iterated source/target maps: $s_\ell^i, t_\ell^i: F_i \to F_{i-\ell}$ for $0 \le \ell \le i$.
*   Composition maps (Godement-style operations): $(u, v) \mapsto (v *_\ell u)$ for $1 \le \ell \le i$, defined when $t_\ell(u) = s_\ell(v)$. The case $\ell=1$ is the usual composition $v \circ u$.

The crucial point is that for the desired notion of ∞-groupoid, the axioms (like associativity, Godement's interchange law, and properties of inversion) should not be equalities but should be replaced by "homotopies," i.e., $(i+1)$-arrows. This leads to a potential infinite regress of higher-order coherence data (e.g., a "pentagon axiom" for associativity isomorphisms, which itself should hold only up to a "ternary" structure). He seeks a "simple guiding principle" to manage this complexity.

### §3 “Fundamental ∞-groupoids” as objects of a “model category”?

Grothendieck asks Quillen if such a structure has been worked out, recalling that Quillen's own description of n-categories was for the strict case. He suggests that the category of ∞-groupoids should be a "model category" for the usual homotopy category, making precise the intuition that a homotopy type is "essentially the same" as an ∞-groupoid. He also proposes that the construction of the fundamental ∞-groupoid of a space can be generalized to any model category in Quillen's sense, yielding a functor from that model category to the category of ∞-groupoids and hence to `(Hot)`.

### §4 A bit of ordering in the mess of “higher order structures”.

Grothendieck refines his classification of the structures of an ∞-groupoid:
*   **Primitive (or Skeletal) Structure:** The source and target maps $s^i, t^i: F_i \to F_{i-1}$.
*   **Primary Structure:** The composition operations $*_1$, the identity maps $k_1^i$, and the pseudo-inversion maps $\text{inv}_i$. He argues that even identities and inverses are not primitive, as their choice for the fundamental ∞-groupoid of a space depends on arbitrary choices (e.g., choosing an isomorphism to compose paths).
*   **Secondary, Ternary, etc. Structures:** The higher compositions $*_2, *_3, \dots$.

This ordering is motivated by the idea that the construction of higher-order structures should rely only on the primitive data.

### §5 Jumping over the abyss!

Grothendieck proposes a precise, inductive construction of the "structure species" of ∞-groupoids.
*   He will construct a sequence of categories and functors: $C_0 \to C_1 \to C_2 \to \dots$.
*   $C_n$ is the category harboring the "universal" partial structure of an ∞-groupoid of order $\le n$.
*   The objects of all $C_n$ are the same: formal objects $\mathbf{F}^i$ and their "standard" iterated fiber products built using only the primitive source and target maps.
*   $C_0$ contains only the arrows corresponding to the primitive structure.
*   $C_{n+1}$ is obtained from $C_n$ by formally adding new arrows (the $(n+1)$-ary structure).
*   The category $C_\infty = \varinjlim C_n$ is the **coherator**, embodying the universal structure.
*   A structure of an ∞-groupoid in a category $\mathcal{C}$ is then a functor $C_\infty \to \mathcal{C}$ that preserves the standard fiber products.
He conjectures that at every step, new structure is added, i.e., $C_n \to C_{n+1}$ is not an equivalence.

### §6 The topological model: hemispheres building up the (tentative) “universal ∞-(co)groupoid”.

The guiding principle for the construction of $C_\infty$ is topological.
*   The functors $X \mapsto F_i(X) = \text{Hom}_{\text{Top}}(\mathbf{D}^i, X)$ are representable by i-cells (disks) $\mathbf{D}^i$.
*   The source/target maps $s_\ell^i, t_\ell^i: F_i(X) \to F_{i-\ell}(X)$ are transposes of maps $\mathbf{D}^{i-\ell} \to \mathbf{D}^i$.
*   The collection of disks $(\mathbf{D}^i)_i$ with these maps and further structure maps (for composition, etc.) forms a **co-∞-groupoid** in the category of topological spaces `(Top)`.
*   The universal coherator $C_\infty$ is conjectured to be the dual of a category $B_\infty$ whose objects are the cells $\mathbf{D}^i$ and their "standard" amalgamated sums, and whose arrows are the maps defining the co-structure.
*   This construction depends on arbitrary choices at each step (e.g., how to compose paths), but the resulting category $C_\infty$ (and each $C_n$) is expected to be independent of these choices up to a unique isomorphism.

### §7 Gluing hemispheres: the “standard amalgamations”.

Grothendieck describes the primitive structure on the cells $\mathbf{D}^i$ more concretely.
*   The boundary $\dot{\mathbf{D}}^{i+1} = S^i$ is the union of two hemispheres, $S^+_i$ and $S^-_i$, which are the images of injective maps $\phi^+_i, \phi^-_i: \mathbf{D}^i \to \mathbf{D}^{i+1}$.
*   Their intersection $S^+_i \cap S^-_i$ is isomorphic to $S^{i-1} = \dot{\mathbf{D}}^i$.
*   A **standard amalgamation** is a finite union of cells $X = \bigcup_i X_i$ (where each $X_i \cong \mathbf{D}^{n(i)}$) that can be built up sequentially by attaching one cell at a time along a single hemisphere of its boundary. This is a combinatorial condition intended to ensure the resulting space is contractible.
*   The dual notion in a category $\mathcal{C}$ is a **standard fiber product**, built from objects $F_i$ using the primitive source/target maps, mirroring this sequential attachment process.

### §8 Description of the universal primitive structure.

The category $B_0$ is defined as the category of "standard ordered sets" $(K, (K_i), (f_i))$, which are combinatorial models for the cellular decompositions of standard amalgamations. The category $C_0$ is its dual, $C_0 = B_0^{\text{op}}$. This gives a precise, explicit description of the category for the primitive structure.

### §9 The main inductive step: just add coherence arrows!

Grothendieck states the two main properties that define the inductive construction of $C_\infty$:
*   **(A) Universal Coherence:** For any object $K \in \text{Ob}(C_\infty)$ and any two parallel arrows $f, g: K \to \mathbf{F}^i$ in $C_\infty$ such that $s_1^i f = s_1^i g$ and $t_1^i f = t_1^i g$, there exists an arrow $h: K \to \mathbf{F}^{i+1}$ such that $s_1^{i+1} h = f$ and $t_1^{i+1} h = g$. This means any two "compatible" constructions automatically have a built-in "homotopy" between them.
*   **(B) Inductive Step:** The category $C_{n+1}$ is obtained from $C_n$ by formally adding new arrows $h$ as in (A) for all pairs $(f, g)$ of arrows *in $C_n$*.

He emphasizes that this construction is inherently ambiguous. Different choices of which arrows to add at each step will lead to non-equivalent coherators $C_\infty$. However, this ambiguity is "irrelevant." Any two resulting theories of ∞-stacks will be related by a pair of functors, and any two objects $T, T'$ corresponding to each other under these functors will be canonically "∞-equivalent." This leads to an infinite hierarchy of equivalences between equivalences, which he illustrates with a story of seven mathematicians.

### §10 Cutting down redundancies – or: “l’embarras du choix”.

Grothendieck considers ways to make the construction of $C_{n+1}$ from $C_n$ more economical, for instance, by adding a new arrow $h$ only when one doesn't already exist in $C_n$. He notes that even with such restrictions, redundancies remain (e.g., having n-ary compositions for all $n$ instead of just iterating binary composition). He concludes that there is no single "most economic" way and prefers to work with a notion of ∞-groupoid that remains partly indeterminate, defined by the general properties (A) and (B).

### §11 Returning to the topological model (the canonical functor from spaces to “∞-groupoids”).

One could try to construct $C_\infty$ as the dual of a category $B_\infty$ of specific topological spaces (geometric realizations $|K|$ of objects $K \in B_0$) and "allowable" continuous maps between them. The condition (B) would translate to an extension property for allowable maps. However, it is not clear that this topological construction would be free of extra, unwanted relations. He concludes that the universal algebra approach is safer and more fundamental; it yields a canonical co-∞-groupoid in `(Top)` (a functor $K \mapsto |K|$ from $C_\infty^{\text{op}}$ to `(Top)`), but this functor need not be faithful.

### §12 About replacing spaces by objects of a “model category”.

The construction of a co-∞-groupoid in `(Top)` can be generalized to any Quillen model category $\mathcal{M}$.
*   The objects $\mathbf{D}^i \in \mathcal{M}$ are chosen inductively. $\mathbf{D}^0$ is a fibrant and trivial object. $\mathbf{D}^{n+1}$ is chosen as a fibrant and trivial object fitting into a diagram with a cofibrant map $S_n \to \mathbf{D}^{n+1}$, where $S_n$ is the pushout modeling the boundary of $\mathbf{D}^{n+1}$.
*   This yields a functor $B_0 \to \mathcal{M}$, which can be extended to $B_\infty \to \mathcal{M}$, provided standard gluings of fibrant and trivial objects remain fibrant and trivial.
*   This construction gives a functor from $\mathcal{M}$ to the category of ∞-groupoids, and composing with localization gives the functor $\mathcal{M} \to \text{(Hot)}$ he alluded to in §3.
*   He conjectures this functor corresponds to the operation of "integration" or "sections" for n-stacks over a topos, a key operation in non-commutative homological algebra.

### §13 An urgent reﬂection on proper names: “Stacks” and “coherators”.

Grothendieck revises his terminology.
*   **Stacks:** He abandons "n-groupoid" because it conflicts with existing (stricter) usage and because his construction is ambiguous. He adopts the term **n-stack** (or **n-Gr-stack** for the groupoid case), extending Giraud's terminology for 1-stacks. This name naturally suggests relativization over an arbitrary topos. An n-stack defined via a specific coherator $C$ can be called an **n-C-stack**.
*   **Coherators:** The universal categories $C_\infty$ that define the structure species of stacks are called **coherators** (*cohéreurs* in French). A coherator embodies a specific hierarchy of coherence "homotopies." He argues that the category structure of a coherator, together with its filtration by the subcategories $C_n$, should be enough to determine all other relevant data, like the primitive objects $\mathbf{F}^i$ and maps $s^i, t^i$.

---

## Appendix: Three letters to Larry Breen

This appendix reproduces three letters from 1975 which contain the seeds of the ideas developed in the main text.

### §1 Examples de 2-catégories de Picard. (Examples of Picard 2-categories.)

Grothendieck provides Breen with examples of Picard 2-categories (groupoids with a symmetric monoidal structure) to demonstrate their importance.
1.  **Gerbes:** For a *lien* (tie) $Z$ on a topos $X$, the $Z$-gerbes form a strict Picard 2-category, represented by the truncated complex $R\Gamma_X(Z)[0,2]$. The obstruction to a gerbe being non-empty lies in $H^3(X, Z)$, which points towards Picard 3-categories.
2.  **Extensions of Sheaves:** For abelian sheaves $M, N$ on $X$, the Picard stacks with invariants $M, N$ form a strict Picard 2-category represented by the truncated complex $R\text{Hom}(M, N)[0,2]$, with invariants $\text{Ext}^i(M, N)$ for $i=0,1,2$.
3.  **Group Actions:** For a group $G$ on $X$ acting on an abelian sheaf $N$, the stacks in Gr-categories on $X$ tied by $(G, N)$ form a Picard 2-category with invariants related to the cohomology of the classifying topos $BG$.
4.  **Azumaya Algebras:** Azumaya algebras on a ringed topos $X$ form a Picard 2-category (the "Brauer" 2-category) whose invariants are the Brauer group $H^2(X, \mathbb{G}_m)_{\text{Br}}$, $H^1(X, \mathbb{G}_m)$, and $H^0(X, \mathbb{G}_m)$.

### §2 Théorème de Lefschetz (faible) en termes de Champs. (Weak Lefschetz theorem in terms of Stacks.)

He argues that strict Picard n-categories provide the geometric interpretation for truncated complexes in derived categories, thus bridging commutative and non-commutative homological algebra. The key motivation comes from algebraic geometry, specifically proving Lefschetz-type theorems for étale cohomology with discrete coefficients. The strongest and most natural statements of these theorems, and the related notion of cohomological depth, are formulated in terms of 1-stacks. He mentions that the proofs in Mme. Raynaud's thesis require the full machinery of 1-stacks (base change theorems for proper and smooth morphisms), suggesting that the