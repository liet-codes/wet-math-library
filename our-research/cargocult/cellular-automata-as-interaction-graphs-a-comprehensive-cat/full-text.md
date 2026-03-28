Cellular Automata as Interaction Graphs: A Comprehen-
sive Catalog of Types, Shared Rule Spaces, and Tractability
Boundaries
Brooklyn Rose and her robots
Cargo Cult Research
March 2026
Abstract
We adopt the framework of cellular automata over generalized Cayley graphs (Arrighi,
Martiel, Nesme 2012, 2018) and specialize it to the computationally tractable sub-
family of periodic, uniform-in-degree interaction graphs. Within this framework, we
systematically catalog all standard CA types — elementary, extended-neighborhood,
multi-color, totalistic, block (Margolus), second-order, and systems on 2D and 3D lat-
tices — as specific interaction graphs, deriving their symmetry groups from graph
automorphisms and their rule space sizes from the uniform in-degree.
We enumerate all distinct one-dimensional interaction graph types for small input
counts, revealing that the named types in the literature are a small, highly symmetric
subset of a much larger space: at n=3 inputs, only 1 of 3 contiguous-span types has
a conventional name; at n=4, only 5 of 26 distinct types do. By explicit computation,
we show that 256 one-dimensional Margolus block CA rules embed as exactly 149
unique rules in the 65,536-element space of 4-input binary rules, with completely dis-
joint nonlinear structure from trivially-embedded ECAs. We establish the tractability
boundary: all binary CAs up to n=5 (approximately 1.07 billion equivalence classes by
explicit enumeration) and, with modest cloud resources, all 3-color elementary CAs
(approximately 635 billion classes) are within reach of complete classification.
1. Introduction
The theory of cellular automata encompasses a diverse family of computational sys-
tems — elementary CA, totalistic CA, block (Margolus) CA, second-order CA, and
systems on lattices of various dimension — typically treated as distinct categories
with separate classification schemes. We propose that all of these are instances of
a single framework, building on the generalized Cayley graph approach to cellular
automata developed by Arrighi, Martiel, and Nesme [1, 2].
The key idea is that cellular automata can be defined over arbitrary bounded-degree
graphs, not just regular lattices, by extending the Curtis-Hedlund-Lyndon character-
ization of CA as continuous shift-commuting maps [3]. We specialize this framework
to what we call interaction graphs — periodic, layered, directed graphs with uniform
in-degree — which capture the computationally tractable regime where exhaustive
rule space analysis is feasible. Our interaction graphs are a static, uniform-degree
subset of the more general causal graph dynamics of Arrighi and Dowek [4], which
allow the graph topology itself to vary over time; we intentionally fix the graph and
explore variation in the rule, since it is this restriction that makes exhaustive analysis
1
possible.
Within this specialization, the “type” of a CA is the isomorphism class of its interaction
graph. The rule space is determined by two integers: the alphabet size k and the
in-degree n. The symmetry group arises as the automorphism group of the graph
combined with alphabet permutations, rather than being imposed by convention.
Our primary contributions are: (1) A systematic catalog of all standard CA types as
specific interaction graphs, with symmetry groups, rule space sizes, and equivalence
class counts computed uniformly. (2) An enumeration of all distinct one-dimensional
interaction graph types for small n, revealing a large space of unnamed and unstud-
ied types. (3) A concrete computation showing that block CA rules embed as a tiny,
algebraically constrained subspace of the shared rule space. (4) A precise character-
ization of the tractability boundary for exhaustive analysis.
1.1 Relationship to Prior Work
The idea that cellular automata can be defined on general graph structures is well-
established. Hedlund [3] characterized CA as continuous shift-commuting maps on
shift spaces.
This was extended to Cayley graphs of finitely generated groups by
Ceccherini-Silberstein and Coornaert [5], and to generalized Cayley graphs by Ar-
righi, Martiel, and Nesme [1, 2]. Wacker [6] developed the uniform Curtis-Hedlund-
Lyndon theorem for CA on group sets.
Arrighi and Dowek [4] introduced Causal
Graph Dynamics, which allow the underlying graph to vary in time.
Our work differs from these in emphasis. The generalized Cayley graph and causal
graph dynamics literature is primarily concerned with topological and dynamical char-
acterization. We are primarily concerned with algebraic and computational charac-
terization — enumerating interaction graph types, comparing rules across types via
their algebraic normal form structure, and determining the practical limits of exhaus-
tive analysis.
The embedding of partitioned (block) CA into classical CA is known in principle: Tof-
foli and Margolus [7] noted the equivalence, Poupet [8] gave explicit translations, and
Durand-Lose [9] proved that any reversible CA can be expressed as a composition of
block permutations. Our contribution is the complete algebraic characterization of
the image of this embedding — not just that it exists, but exactly which 149 rules it
produces, what their degree profiles are, and how their monomial structure compares
with rules from other CA types.
2. The Interaction Graph Framework
2.1 Definitions
Definition 2.1 (Interaction Graph). An interaction graph is a directed graph G =
(V, E) satisfying: (i) V partitions into layers V₀, V₁, V₂, … such that every edge goes
from layer t to layer t+1. (ii) Every vertex has the same in-degree n ≥1 (uniformity).
(iii) The graph has a periodic structure: there exists a finite fundamental domain that
tiles G by translation (periodicity).
Definition 2.2 (Cellular Automaton). A cellular automaton is a pair (G, f) where G
2
is an interaction graph with uniform in-degree n over an alphabet Σ of size k, and f:
Σ𝑛→Σ is the local rule.
Definition 2.3 (Isomorphism). Two cellular automata (G₁, f₁) and (G₂, f₂) are iso-
morphic if there exists a layer-preserving graph isomorphism mapping G₁ to G₂, and
an alphabet permutation π ∈Sₖ, that together map f₁ to f₂. For standard binary ECAs
(k=2), this π simply corresponds to the familiar bitwise color complementation. The
symmetry group is Aut(G) × Sₖ, where Aut(G) is the automorphism group of the inter-
action graph restricted to layer-preserving automorphisms that permute predecessor
edges.
Figure 1a: An elementary cellular automaton shown as both a spacetime diagram
(left) and its corresponding interaction graph (right).
The red arrows trace the 3
inputs — left neighbor, self, and right neighbor — converging on a single output cell.
ECA: n = 3 inputs, offset set {−1, 0, +1}. Uniform in-degree 3, Aut(G) ≅ℤ₂.
3
Figure 1b: A second-order ECA extends the standard ECA interaction graph with an
additional temporal skip edge (gold, dashed) from the cell’s own state at t−2. This
increases the in-degree to 4 (3 spatial + 1 temporal), placing it in the same rule space
as the 1D contiguous n=4 type, block CAs, and the ladder graph.
2.2 The Rule Space and Its Algebraic Structure
For fixed k and n, the rule space is the set of all functions Σ𝑛→Σ, which has kⁿ
possible inputs and hence k^(kⁿ) possible rules. When k is a prime power, each rule
has a unique representation as a polynomial over the finite field 𝔽ₖ — its algebraic
normal form (ANF). For binary CAs (k=2), each monomial is a product of a subset
of the input variables, with degree equal to the number of variables. There are 2ⁿ
possible monomials, and the ANF coefficients are computed from the truth table via
the Möbius butterfly transform in O(n · 2ⁿ) operations.
For k-color CAs with k > 2 (and k a prime power), the ANF is a polynomial over 𝔽ₖ
where each variable xᵢcan appear with exponent 0, 1, …, k−1 (since xᵢᵏ= xᵢin 𝔽ₖ).
The total degree of a monomial ∏xᵢ^(aᵢ) is the sum of exponents ∑aᵢ. For k=3 with
n=3 variables, each variable has exponent at most 2, so the total degree ranges from
0 to 6, giving 7 distinct degree levels — nearly double the 4 levels available in the
binary ECA.
The ANF depends only on the truth table, not on the interaction graph. The degree
profile, algebraic degree, and all derived algebraic features are graph-independent
invariants of the rule.
2.3 Nested Embedding
For fixed k, the rule spaces at different values of n form a nested hierarchy: every
n-input rule can be extended to an (n+1)-input rule by ignoring one input. There are
(n+1) such embeddings, and their union contains all (n+1)-input rules that depend on
4
at most n of their inputs. By explicit enumeration, for k=2 the n=3 space (256 ECA
rules) embeds into the n=4 space via 4 embeddings, whose union contains exactly
942 of the 65,536 n=4 rules — precisely those 4-input binary functions for which at
least one input is irrelevant.
2.4 Totalistic and Outer-Totalistic Subspaces
Totalistic rules are not a separate interaction graph type but a constrained subspace
within a standard type. A totalistic rule depends only on the sum of input values, not
their positions; it is invariant under all input permutations. An outer-totalistic rule
depends on a distinguished center cell plus the sum of the remaining inputs.
For any given (k, n, G), the totalistic subspace consists of those rules f: Σ𝑛→Σ
that are invariant under all permutations of the inputs. The number of distinct input
sums ranges from 0 to n(k−1), giving n(k−1)+1 possible totalistic inputs and hence
k^(n(k−1)+1) totalistic rules. For outer-totalistic rules with a distinguished center,
the count is k^(k · ((n−1)(k−1)+1)).
Whether totalistic subspaces exhibit algebraic isolation analogous to the block CA dis-
jointness (Section 5) is an open question. The totalistic constraint forces monomials
related by input permutation to share the same coefficient, but does not eliminate
any monomial entirely; it constrains the coefficient space rather than the monomial
space.
The following table summarizes the totalistic subspace sizes for the types cataloged
in this paper:
Type
k
n
Full rule
space
Totalistic
rules
Outer-
totalistic
rules
ECA
2
3
256
16
64
1D r=1,
k=3
3
3
~7.63 ×
10¹²
2,187
19,683
1D r=2 / 2D
Von
Neumann
2
5
~4.3 × 10⁹
64
1,024
2D
Hexagonal /
3D Von
Neumann
2
7
~3.4 × 10³⁸
256
16,384
2D Moore
2
9
~1.3 ×
10¹⁵⁴
1,024
262,144
Table 2.1.
Totalistic and outer-totalistic subspace sizes.
The Game of Life is one
rule in the 262,144-element outer-totalistic subspace of the 2D Moore neighborhood.
Binary totalistic ECAs (16 rules) are the simplest nontrivial totalistic subspace.
These subspace sizes are tiny relative to the full rule spaces but are important be-
cause many well-studied CAs (including the Game of Life and all Wolfram-numbered
5
totalistic CAs) live in them.
3. Catalog of CA Types as Interaction Graphs
3.1 One-Dimensional Types: Offset Sets
For a one-dimensional classical CA with n inputs, the interaction graph is specified by
the offset set: the set of n spatial positions that each cell reads from. After normalizing
by spatial translation (setting the minimum offset to 0), the offset set takes the form
{0, d₁, …, dₙ₋₁} with 0 < d₁ < … < dₙ₋₁. The integer dₙ₋₁ is the span — the width of
the dependency window.
Two offset sets related by spatial reflection (replacing each offset d with span −d)
produce interaction graphs with isomorphic automorphism groups. An offset set that
equals its own reflection is symmetric and has Aut(G) ≅ℤ₂; otherwise Aut(G) is trivial.
The minimum possible span is n−1, achieved only by the contiguous offset set {0,
1, …, n−1}.
Since the span is unbounded, the number of 1D types for any given
n is formally infinite. We restrict attention to types with small spans, focusing on
the contiguous types that correspond to standard named CAs and a representative
selection of non-contiguous types to illustrate the space.
Contiguous types. For each n, the contiguous offset set {0, 1, …, n−1} is the unique
type with minimum span. It is always symmetric (Aut(G) ≅ℤ₂) and corresponds to
the standard “radius-r” CA where n = 2r+1 (for odd n) or a shifted neighborhood (for
even n). These are the types that have been systematically studied in the literature.
Non-contiguous types. At each n, there exist additional 1D types corresponding to
offset sets with gaps. These produce CAs with the same number of inputs but wider
light cones. The simplest non-trivial example is {0,2,4} at n=3 — a “dilated ECA”
where each cell reads from every other cell. This shares the same 256-rule space as
the standard ECA but produces different dynamics due to the wider spatial coupling.
Beyond this illustrative case, non-contiguous types proliferate rapidly with n: at n=4
there are 21 unnamed non-contiguous 1D types (Section 3.3).
3.2 Complete Catalog by Input Count
We now catalog all named interaction graph types organized by their shared rule
spaces.
n=3, k=2: The ECA Space (256 rules)
Type
Geometry
Aut(G)
Aut(G) × S₂
ECA {0,1,2}
1D contiguous
ℤ₂
4
88
16
Table 3.1. The n=3, k=2 interaction graph type. The 16 binary totalistic rules and 64
outer-totalistic rules form subspaces of this 256-rule space.
This is the most thoroughly studied CA rule space. The totalistic subspace (16 rules)
includes the trivial all-zero and all-one rules, the identity, and the additive Rule 150
6
(XOR of all three inputs). The outer-totalistic subspace (64 rules) additionally allows
the center cell to play a distinguished role, and includes Rules 110 and 30.
n=3, k=3: The 3-Color Elementary Space (~7.63 × 10¹² rules)
The same in-
teraction graph as the binary ECA, but with k=3. Full symmetry group: Aut(G) × S₃,
where S₃ has order 6. For the standard contiguous type, |Aut(G) × S₃| = 12. The rule
space has 3²⁷ ≈7.63 × 10¹² rules, collapsing to approximately 635 billion equivalence
classes. Over 𝔽₃, each variable can appear with exponent 0, 1, or 2, so the total de-
gree of a monomial in 3 variables ranges from 0 to 6, giving 7 distinct degree levels.
The totalistic subspace contains 3⁷ = 2,187 rules.
n=4, k=2: The Central Shared Space (65,536 rules, 26 types)
This is the most
densely populated shared rule space in the tractable regime and the primary testing
ground for cross-type comparison. Five named types share this space alongside 21
unnamed 1D types.
Named types:
Type
Geometry
Aut(G)
Aut(G) × S₂
1D
contiguous
{0,1,2,3}
1D
symmetric
ℤ₂
4
16,384
Standard
radius-1½
2D
Triangular
(3.12²)
2D
Archimedean
D₃ (order 6)
12
5,461
3 edge-
neighbors +
self on
(3.12²)
tiling
Ladder
graph
Width-2
strip
ℤ₂ (rail
swap)
4
16,384
2 parallel
chains with
rungs
2nd-order
ECA
Temporal
skip
ℤ₂ (reflect)
4
16,384
ECA +
input from
t−2
1D Block
2-cell
Margolus
factored
—
149
effective
2-step block
composition
Table 3.2. Named interaction graph types at n=4, k=2. All equivalence class counts
by explicit enumeration. The block CA type produces only 149 effective rules (Section
4).
Unnamed 1D types (21 total). At n=4, there are 22 distinct 1D types with span ≤7:
9 symmetric and 13 asymmetric. Excluding the contiguous type {0,1,2,3}, this leaves
21 unnamed types. Symmetric types each have Aut(G) ≅ℤ₂ and 16,384 equivalence
classes; asymmetric types have trivial Aut(G) and 32,768 equivalence classes. Repre-
sentative examples: {0,1,3,4} (symmetric, gap in the middle), {0,1,2,4} (asymmetric,
one outlier), {0,2,4,6} (symmetric, fully dilated — every other cell).
7
2D Archimedean tiling types at n=4.
Three of the 11 Archimedean (vertex-
transitive) tilings of the Euclidean plane have vertex degree 3, giving n=4 when
self-input is included: the (3.12²) super-kagome, the (4.6.12) tiling, and the (4.8²)
truncated square tiling. These are all distinct interaction graph types sharing the
n=4 rule space. The (3.12²) tiling is listed in Table 3.2; the other two have different
automorphism groups and produce different equivalence class counts. All three have
translation symmetry, satisfying the periodicity requirement of Definition 2.1.
Grand total at n=4: 26 distinct interaction graph types, all sharing the same
algebraic rule space of 65,536 binary 4-input functions. Only 5 have conventional
names. The remaining 21 are 1D CAs with non-contiguous offset patterns that have
never been systematically studied.
n=5, k=2: The Billion-Rule Space (~4.3 × 10⁹ rules, 40+ types)
Type
Geometry
Aut(G)
Aut(G) × S₂
1D
contiguous
{0,1,2,3,4}
1D radius-2
ℤ₂
4
~1.07 × 10⁹
Standard
1D r=2
2D Von
Neumann
Square grid,
4 neighbors
+ self
D₄ (order 8)
16
~268 × 10⁶
Cross neigh-
borhood
2D Kagome
(3.6.3.6)
Archimedean
tiling
D₂ (order 4)
8
~537 × 10⁶
4 edge-
neighbors +
self
2D (3.4.6.4)
Archimedean
tiling
varies
varies
—
4 edge-
neighbors +
self
Table 3.3. Named interaction graph types at n=5, k=2. The kagome lattice (trihexag-
onal tiling) and the (3.4.6.4) tiling both have vertex degree 4, giving n=5 with self-
input. Class counts for the standard types by computation; Archimedean tiling types
by symmetry analysis.
The Von Neumann neighborhood’s totalistic subspace contains only 64 rules; its outer-
totalistic subspace contains 1,024 rules. The 37+ unnamed 1D types span the remain-
ing offset-set configurations with span ≤10.
8
Figure 2: Two interaction graph types sharing the n=5 binary rule space. Left: 1D
radius-2 (5 contiguous inputs along a line). Right: 2D Von Neumann (5 inputs in a
cross pattern on the square grid). The bottom panels show spacetime evolution of
the same rule (rule 3033114006 decimal) from random initial conditions — different
dynamics from the same algebraic object, demonstrating that causal topology shapes
behavior independently of the rule’s algebraic structure.
n=6, k=2 (~1.8 × 10¹⁹ rules)
Three Archimedean tilings have vertex degree 5,
giving n=6 with self-input: (3⁴.6), (3³.4²), and (3².4.3.4). These are all distinct inter-
action graph types sharing the n=6 rule space with 1D radius-2½ and approximately
70 unnamed 1D types. This space is beyond exhaustive classification but accessible
to dense sampling.
n=7, k=2 (~3.4 × 10³⁸ rules, 112+ types)
9
Type
Geometry
Aut(G)
Aut(G) × S₂
1D
contiguous
{0,1,…,6}
1D radius-3
ℤ₂
4
~8.5 × 10³⁷
Standard
1D r=3
2D
Hexagonal
(6³)
Hex grid, 6
neighbors +
self
D₆ (order
12)
24
~1.4 × 10³⁷
Regular
hexagonal
tiling
3D Von
Neumann
Cubic grid,
6 face-
neighbors +
self
Oₕ (order
48)
96
~3.5 × 10³⁶
Fewest
classes of
any n=7
type
2D
Triangular
(3⁶)
Triangular
grid, 6
neighbors +
self
D₆ (order
12)
24
~1.4 × 10³⁷
Regular
triangular
tiling
Table 3.4. Named interaction graph types at n=7, k=2. The 3D type has the fewest
equivalence classes due to its 48-element automorphism group. Note that the hexag-
onal and triangular tilings share the same vertex degree and hence the same rule
space, despite having very different spatial structure.
The totalistic subspace at n=7 contains 256 rules; the outer-totalistic subspace con-
tains 16,384 rules.
n=9, k=2 (~1.3 × 10¹⁵⁴ rules)
The 2D Moore neighborhood (3×3 square, 8 neigh-
bors + self) lives here, alongside 1D radius-4 and 500+ unnamed 1D types. Aut(G)
≅D₄ for the Moore neighborhood. The outer-totalistic subspace (262,144 rules) con-
tains the Game of Life and is the only portion of this space that has been substantially
explored. The full space is far beyond exhaustive analysis.
3.3 Growth of the Type Count
n
1D types
(span ≤2n)
Non-1D
named
Total named
Total types
Tractable?
3
9
0
1
9
Trivial
4
22
4+
5
26+
Trivial
5
38
3+
3
41+
Laptop
6
70
3+
3
73+
Sample
7
110+
3+
4
113+
Sample
9
500+
2+
3
502+
Sample
Table 3.5. Growth of interaction graph types with n. Named types are a tiny fraction of
the total. “Tractable?” indicates feasibility of exhaustive classification of the full rule
space. 1D type counts are lower bounds from enumerating offset sets with span ≤2n.
Non-1D counts include 2D/3D lattice types and Archimedean tiling types identified
10
in this section; the “+” indicates that additional Archimedean or higher-dimensional
types may exist.
Asymmetric types outnumber symmetric types by roughly 3:1, increasingly so at
larger n. The total count grows combinatorially with span, reflecting the number of
ways to choose n positions within a window of width 2n.
3.4 Block, Second-Order, and Higher-Dimensional Types
1D Block CA (Margolus, 2-cell). The rule maps 2-cell blocks, giving 4⁴ = 256 block
rules. The 2-step effective interaction graph has in-degree 4. See Section 4 for the
complete algebraic characterization.
Second-order ECA. The interaction graph augments the standard ECA graph with
temporal skip edges from layer t−2, giving in-degree 4. This is equivalent to a stan-
dard n=4 CA where one input is constrained to be the cell’s own previous value — a
fact encoded in the graph topology. More generally, one could construct interaction
graphs reading from multiple past time steps (e.g., spatial neighbors at t−1 plus a
cell at t−3), producing distinct graph types at the same n. We restrict attention to the
standard second-order construction here.
Ladder graph (n=4). A width-2 strip of the square lattice: two parallel 1D chains
with rungs connecting them. Each cell reads from 4 inputs: itself, its left neighbor
on the same chain, its neighbor on the opposite chain, and its left neighbor on the
opposite chain. Aut(G) ≅ℤ₂ (rail swap). This is a genuinely intermediate topology
between 1D and 2D — information can travel transversely between the two chains,
which 1D CAs cannot support.
11
Figure 4: A zoo of named interaction graph topologies at various n. All share the same
local rule structure f: Σ𝑛→Σ; they differ only in how the n inputs are wired spatially
and temporally. The same rule table applies to any graph with matching n and k.
2D Archimedean tiling types. The 11 Archimedean (1-uniform, vertex-transitive)
tilings of the Euclidean plane all satisfy our interaction graph requirements: they are
periodic and every vertex has the same degree. Including self-input, they produce
interaction graphs at n values from 4 through 7:
Tiling
Vertex figure
Edge degree
n (with self)
Aut(G)
(3.12²)
1 tri + 2 dodecagons
3
4
D₃
(4.6.12)
1 sq + 1 hex + 1 dodecagon
3
4
D₁
12
Tiling
Vertex figure
Edge degree
n (with self)
Aut(G)
(4.8²)
1 sq + 2 octagons
3
4
D₂
(3.6.3.6) Kagome
2 tri + 2 hex, alternating
4
5
D₂
(3.4.6.4)
1 tri + 1 sq + 1 hex + 1 sq
4
5
D₁
(4⁴) Square
4 squares
4
5
D₄
(3⁴.6)
4 tri + 1 hex
5
6
D₁
(3³.4²)
3 tri + 2 sq
5
6
D₁
(3².4.3.4)
2 tri + 1 sq + 1 tri + 1 sq
5
6
D₂
(3⁶) Triangular
6 triangles
6
7
D₆
(6³) Hexagonal
3 hexagons
3
4
D₃
Table 3.6. All 11 Archimedean tilings as interaction graphs, listed by vertex degree.
The square tiling (4⁴) with Von Neumann neighborhood is included for completeness.
Note the (6³) hexagonal tiling has edge degree 3 like the (3.12²), (4.6.12), and (4.8²)
tilings — all four share the n=4 rule space but have different automorphism groups.
Automorphism groups listed are the point symmetry groups of the vertex figure; the
full Aut(G) depends on the specific embedding.
These are the only vertex-transitive tilings of the Euclidean plane by regular polygons,
so this table exhausts the 2D Archimedean tiling types. Non-uniform (k-uniform, k ≥
2) tilings violate the vertex-transitivity requirement and hence do not satisfy Defini-
tion 2.1.
13
Figure 6:
Four Archimedean tilings as interaction graphs.
Each tiling is vertex-
transitive and periodic, satisfying Definition 2.1.
Red:
target cell; blue:
edge-
neighbors (inputs). With self-input included, these tilings produce interaction graphs
at n = 4, 5, 6, and 7, sharing rule spaces with the 1D and lattice types cataloged in
Section 3. All 11 Archimedean tilings are cataloged in Table 3.6.
3D lattice types. The standard 3D cubic lattice produces two named types: the Von
Neumann neighborhood (6 face-neighbors + self, n=7) and the Moore neighborhood
(26 neighbors + self, n=27). The Von Neumann type has Aut(G) ≅Oₕ (full octahedral
symmetry, order 48). The 3D Moore rule space, at 2^(2²⁷) ≈10^(4×10⁷), is effectively
infinite.
14
3.5 Scope and Limitations of the Catalog
Our catalog is restricted to interaction graphs satisfying Definition 2.1: periodic, lay-
ered, uniform in-degree. This excludes several classes of graphs that support well-
defined CA dynamics:
Non-abelian Cayley graphs. The theory of CA on Cayley graphs of finitely generated
groups is well-developed [5, 15]. CAs on Cayley graphs of non-abelian groups (e.g.,
free groups, Baumslag-Solitar groups) have rich theory — the Garden of Eden theo-
rem, for instance, holds precisely for amenable groups. However, non-abelian Cayley
graphs generally lack the translation symmetry required for our periodic tiling con-
dition. The Cayley graph of the free group F₂ is an infinite 4-regular tree, which has
uniform degree but no periodic structure. We exclude these from our catalog because
our focus is on exhaustive algebraic classification, which requires finite fundamental
domains.
Hyperbolic tilings. Regular hyperbolic tilings {p,q} have uniform vertex degree and
support well-defined CA dynamics. However, they lack Euclidean translation symme-
try and cannot tile a flat torus, placing them outside our periodicity requirement.
Trees and Bethe lattices. The infinite regular tree (Bethe lattice) has uniform de-
gree but is not periodic. CAs on trees have been studied in the context of decidability
and self-similar dynamics but fall outside our framework.
In all three cases, the algebraic rule space (determined solely by k and n) is identi-
cal to the Euclidean types with the same parameters. The dynamics differ because
the causal topology differs. Our framework captures the types for which exhaustive
analysis of the rule space is feasible; extending the catalog to non-periodic graphs
is a natural direction for future work, though it would require sampling rather than
exhaustive methods.
4. Block CA Embedding: A Worked Example
4.1 Construction
A 1D binary block CA with 2-cell Margolus blocks has 4⁴ = 256 possible rules. Each
maps a 2-cell input (a, b) to a 2-cell output (a′, b′). The two-step composition with
staggered block boundaries produces an effective 4-input function:
cell₀″ = f_R(f_R(c₋₂, c₋₁), f_L(c₀, c₁))
where f_L and f_R are the left and right output components of the block rule. This
effective function is an element of the n=4 binary rule space.
15
Figure 3: Two-step composition of a 2-cell Margolus block CA. Even-phase blocks
(orange) at time t feed into odd-phase blocks (blue) at t+1. The effective dependency
of the target cell at t+2 on four cells at t produces a factored 4-input function. The
inset (right) shows the factored structure: inputs (a, b) and (c, d) are processed in-
dependently before combining, preventing cross-group monomials (e.g., ac, bd) and
constraining which algebraic structures are accessible (Section 4.4).
4.2 Results
By explicit computation of this embedding for all 256 block rules:
Quantity
Value
Total block rules
256
Unique effective n=4 rules
149
Coverage of n=4 space
0.23% (149 / 65,536)
Max degree 0–1 (affine)
17 rules (11.4%)
Max degree 2 (quadratic)
20 rules (13.4%)
Max degree 3 (cubic)
48 rules (32.2%)
Max degree 4 (quartic)
64 rules (43.0%)
Table 4.1. Block CA embedding results. All values by explicit computation.
Despite the constrained factored structure, block CA effective rules span the full
range of algebraic degrees from 0 to 4. The quartic monomial abcd is achieved when
16
both component functions are nonlinear: for example, block rule 192 (where both fₗ
and fᴿcompute AND) produces the effective rule f(a,b,c,d) = (a ∧b) ∧(c ∧d) = abcd,
a pure degree-4 monomial.
4.3 Overlap with ECA
The overlap between trivially-embedded ECAs and block-reachable rules in the n=4
space consists of exactly 16 rules, every one of which is affine (max degree ≤1). No
nonlinear rule is reachable from both sources.
The nonlinear subspaces are com-
pletely disjoint.
17
Figure 5: The n=4 binary rule space (65,536 rules) with ECA and block CA embed-
dings shown as subsets. The 942 trivially-embedded ECA rules and 149 block CA
effective rules overlap in exactly 16 affine rules. All nonlinear structure is completely
disjoint — block CAs and ECAs access algebraically distinct subsets of the monomial
lattice.
18
4.4 Monomial Accessibility
The factored structure f(a,b,c,d) = g(h₁(a,b), h₂(c,d)) constrains which monomials can
appear. A factored function can produce monomials that decompose as (function of
a,b) × (function of c,d) — such as ab, cd, and abcd — but cannot produce monomials
like ac, bc, abd, or acd that mix variables across the factor groups asymmetrically.
This monomial accessibility constraint means that block CAs and standard CAs access
algebraically distinct subsets of the monomial lattice, even when they share the same
rule space.
5. Tractability Boundaries
5.1 Exhaustive Analysis
CA Type
k
n
Equiv.
classes
Resource
Est. time
Types at
this n
ECA
(incl. to-
talistic)
2
3
88
Laptop
Seconds
1 (con-
tiguous)
All n=4
types
2
4
5,461 –
32,768
Laptop
Seconds
26+
1D Block
(effective)
2
4
149
Laptop
Seconds
—
All n=5
types
2
5
~268M –
1.07B
Laptop
5–15 min
41+
3-color
ECA
3
3
~635B
Cloud
GPU
~2 hours
1
Table 5.1. CA types amenable to exhaustive classification. Class counts by computa-
tion; runtime estimates from benchmarking on 8-core laptop. The 3-color estimate
is based on projected GPU performance on an NVIDIA A100, estimated cost $2–4.
Totalistic subspaces at every n are trivially exhaustible on a laptop.
The n=5 binary space is the largest amenable to exhaustive classification on a laptop:
approximately 4.3 billion rules collapsing to approximately 1.07 billion equivalence
classes under the ℤ₂ × S₂ symmetry of the standard contiguous interaction graph.
Crucially, there are 41+ distinct interaction graph types at n=5, each classifiable
with the same pipeline. Running all types requires only ~41× the compute of one
type — still well under an hour.
The 3-color ECA space (3²⁷ ≈7.6 trillion rules, ~635 billion classes under ℤ₂ × S₃) is
the largest space we argue is within reach of exhaustive classification given modern
commodity hardware, requiring a single cloud GPU for an estimated cost of a few
dollars.
5.2 Dense Sampling
19
CA Type
k
n
Sample size
Est. time
1D r=3 / Hex 2D / Tri 2D / 3D VN
2
7
10⁸ rules
~2 min
4-color ECA
4
3
10⁸ rules
~10 min
Table 5.2. Dense sampling regime for rule spaces beyond exhaustive reach.
5.3 Beyond Current Tractability
CA Type
k
n
Rule space
Obstacle
1D r=4 / 2D Moore
2
9
2⁵¹² ≈10¹⁵⁴
Double-exponential
5-color ECA
5
3
≈10⁸⁷
Large alphabet
3D Moore
2
27
≈10^(4×10⁷)
Effectively infinite
Table 5.3. Spaces requiring sparse sampling. Equivalence class counts are on the
order of the rule space divided by the symmetry group order.
6. Discussion
6.1 The Interaction Graph as Type
In this framework, the traditional CA “types” (ECA, block, second-order, 2D Moore,
etc.)
are not categories imposed from outside — they are isomorphism classes of
interaction graphs. Block CAs, second-order CAs, and asymmetric-neighborhood CAs
are all variations on “n=4 rules on different graphs.” The second-order ECA is not
an exotic object: it is a standard n=4 CA where one input comes from the cell’s own
temporal past, a fact encoded in the graph topology rather than requiring a separate
definition.
6.2 Unexplored Territory
The enumeration of Section 3 reveals that the named CA types are a small, highly
symmetric corner of the interaction graph space. At n=4, there are 21 unnamed 1D
interaction graph types — CAs where cells read from non-contiguous positions like
{0,1,3,5} or {0,2,4,6}. None of these have been systematically studied.
This creates a concrete experimental program: running the same rules on different
interaction graphs tests which aspects of dynamical behavior are determined by the
rule’s algebraic structure (graph-independent) and which depend on the causal topol-
ogy (graph-dependent). If a rule classified as Class IV on the standard contiguous
graph maintains that classification across non-contiguous graphs, the algebraic sig-
nature is robust. If it does not, the interaction graph topology contributes something
the algebra cannot capture — an equally informative finding. The n=4 space is par-
ticularly valuable for this purpose because it contains the most named types and is
fully exhaustible on a laptop.
20
6.3 Interaction Graphs and Causal Graph Dynamics
Our interaction graphs are a special case of the generalized Cayley graphs of Arrighi
et al. [1, 2]: periodic, layered, and uniform in degree. We intentionally fix the graph
and vary the rule, whereas causal graph dynamics [4] allow both to evolve. The two
approaches are complementary. Causal graph dynamics addresses “what is the most
general notion of discrete local computation?” We address “given a specific compu-
tational substrate, what can we learn about the space of all possible computations on
it?”
6.4 Algebraic Structure and Causal Topology
The algebraic normal form of a rule is a graph-independent invariant: the ANF, degree
profile, and monomial structure are determined entirely by the truth table and are
identical regardless of which interaction graph the rule is embedded in. However, the
dynamical consequences of that algebraic structure — including whether the rule
supports computational universality — depend on the interaction between the rule
and the causal topology. The shared rule spaces identified in this paper provide a
natural testbed for disentangling these contributions: the same rule, simulated on
multiple interaction graphs, isolates the effect of topology on dynamics.
The block CA monomial accessibility constraint (Section 4.4) demonstrates that inter-
action graph topology can restrict the algebraic structures available to a rule. This
means that different CA types, even when sharing the same (k, n) parameters, have
access to fundamentally different subsets of the algebraic landscape — a structural
constraint with potential implications for understanding the relationship between spa-
tial structure and computational capacity.
7. Conclusion
The generalized Cayley graph framework provides a natural, unified foundation for
cataloging and comparing all standard cellular automata types. The interaction graph
simultaneously encodes spatial topology, causal structure, and symmetry group. The
systematic enumeration reveals a large space of unnamed and unstudied types at ev-
ery input count, with named types constituting a small minority. The Archimedean
tilings of the Euclidean plane contribute additional named 2D types at n=4 through
n=7 that have been largely overlooked in the CA literature. The block CA embedding
demonstrates the power of cross-type algebraic comparison, revealing that differ-
ent interaction graph topologies produce algebraically disjoint nonlinear subspaces
within a shared rule space. The tractability boundary — all binary CAs up to n=5, and
all 3-color ECAs with modest cloud resources — defines a concrete and achievable
program of exhaustive classification.
References
[1] P. Arrighi, S. Martiel, and V. Nesme, “Cellular automata over generalized Cayley
graphs,” Mathematical Structures in Computer Science, vol. 18, pp. 340–383, 2018.
21
[2] P. Arrighi, S. Martiel, and V. Nesme, “Generalized Cayley graphs and cellular
automata over them,” arXiv:1212.0027, 2012.
[3] G. A. Hedlund, “Endomorphisms and automorphisms of the shift dynamical sys-
tem,” Mathematical Systems Theory, vol. 3, pp. 320–375, 1969.
[4] P. Arrighi and G. Dowek, “Causal graph dynamics,” Information and Computation,
vol. 223, pp. 78–103, 2013.
[5] T. Ceccherini-Silberstein and M. Coornaert, Cellular Automata and Groups,
Springer, 2010.
[6] S. Wacker, “Cellular automata on group sets and the uniform Curtis-Hedlund-
Lyndon theorem,” Natural Computing, vol. 18, pp. 445–458, 2019.
[7] T. Toffoli and N. Margolus, Cellular Automata Machines: A New Environment for
Modeling, MIT Press, 1987.
[8] V. Poupet, “Translating partitioned cellular automata into classical type cellular
automata,” JAC 2008, pp. 130–140, 2008.
[9] J. Durand-Lose, “Representing reversible cellular automata with reversible block
cellular automata,” DMTCS Proceedings, 2001.
[10] B. Rose, “Affine Decomposition of Elementary Cellular Automata,” Preprint,
Cargo Cult Research, 2026.
[11] M. Cook, “Universality in Elementary Cellular Automata,” Complex Systems,
vol. 15, no. 1, pp. 1–40, 2004.
[12] J. Kari, “Theory of cellular automata: a survey,” Theoretical Computer Science,
vol. 334, pp. 3–33, 2005.
[13] S. Wolfram, A New Kind of Science, Wolfram Media, 2002.
[14] K. Lindgren and M. G. Nordahl, “Universal Computation in Simple One-
Dimensional Cellular Automata,” Complex Systems, vol. 4, pp. 299–318, 1990.
[15] T. Ceccherini-Silberstein, A. Machì, and F. Scarabotti, “Amenable groups and
cellular automata,” Annales de l’institut Fourier, vol. 49, no. 2, pp. 673–685, 1999.
22
