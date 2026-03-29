---
type: manuscript
title: "Esquisse d'un Programme"
author: "Alexander Grothendieck"
date: "2024"
language: en
tags: ["wet-math", "category-theory", "cellular-automata"]
source: "esquisse"
word_count: 19167
l0: "Abstract not available."
relations:
  cites: []
  cited_by: []
  related: []
---

<!-- L1: Overview (~2k tokens) -->
## Overview

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

### Key Concepts
- [[cellular-automata]] — brief description
- [[anabelian-geometry]] — brief description

### Connections
- Relates to [[groovy-commutator]] (dessins d'enfants, operational approach to fundamental groups)

<!-- L2: Full Content -->
## Full Text

SKETCH OF A PROGRAMME
by Alexandre Grothendieck
Summary:
1.
Preface.
2.
A game of “Lego-Teichm¨uller” and the Galois group Q over Q.
3.
Number ﬁelds associated to a child’s drawing.
4.
Regular polyhedra over ﬁnite ﬁelds.
5.
Denunciation of so-called “general” topology, and heuristic reﬂections
towards a so-called “tame” topology.
6.
“Diﬀerentiable theories” (`a la Nash) and “tame theories”.
7.
Pursuing Stacks.
8.
Digressions on 2-dimensional geometry.
9.
Assessment of a teaching activity.
10. Epilogue.
Notes
N.B. The asterisks (*) refer to the footnotes on the same page, the super-
scripts numbered from (1) to (7) refer to the notes (added later) collected
at the end of this report.


---

SKETCH OF A PROGRAMME
by Alexandre Grothendieck
1. As the present situation makes the prospect of teaching at the research
level at the University seem more and more illusory, I have resolved to apply
for admission to the CNRS, in order to devote my energy to the development
of projects and perspectives for which it is becoming clear that no student
(nor even, it seems, any mathematical colleague) will be found to develop
them in my stead.
In the role of the document “Titles and Articles”, one can ﬁnd after this
text the complete reproduction of a sketch, by themes, of what I considered
to be my principal mathematical contributions at the time of writing that
report, in 1972. It also contains a list of articles published at that date. I
ceased all publication of scientiﬁc articles in 1970. In the following lines,
I propose to give a view of at least some of the principal themes of my
mathematical reﬂections since then. These reﬂections materialised over the
years in the form of two voluminous boxes of handwritten notes, doubtless
diﬃcult to decipher for anyone but myself, and which, after several succes-
sive stages of settling, are perhaps waiting for their moment to be written
up together at least in a temporary fashion, for the beneﬁt of the mathema-
tical community. The term “written up” is somewhat incorrect here, since
in fact it is much more a question of developing the ideas and the multiple
visions begun during these last twelve years, to make them more precise and
deeper, with all the unexpected rebounds which constantly accompany this
kind of work – a work of discovery, thus, and not of compilation of piously
accumulated notes. And in writing the “Mathematical Reﬂections”, begun
since February 1983, I do intend throughout its pages to clearly reveal the
process of thought, which feels and discovers, often blindly in the shadows,
with sudden ﬂashes of light when some tenacious false or simply inadequate
1
2
image is ﬁnally shown for what it is, and things which seemed all crooked
fall into place, with that mutual harmony which is their own.
In any case, the following sketch of some themes of reﬂection from the
last ten or twelve years will also serve as a sketch of my programme of work
for the coming years, which I intend to devote to the development of these
themes, or at least some of them. It is intended on the one hand for my
colleagues of the National Committee whose job it is to decide the fate of
my application, and on the other hand for some other colleagues, former
students, friends, in the possibility that some of the ideas sketched here
might interest one of them.


---

240
Alexandre Grothendieck
2. The demands of university teaching, addressed to students (including
those said to be “advanced”) with a modest (and frequently less than mod-
est) mathematical baggage, led me to a Draconian renewal of the themes
of reﬂection I proposed to my students, and gradually to myself as well.
It seemed important to me to start from an intuitive baggage common to
everyone, independent of any technical language used to express it, and
anterior to any such language – it turned out that the geometric and topo-
logical intuition of shapes, particularly two-dimensional shapes, formed such
a common ground. This consists of themes which can be grouped under the
general name of “topology of surfaces” or “geometry of surfaces”, it being
understood in this last expression that the main emphasis is on the topolog-
ical properties of the surfaces, or the combinatorial aspects which form the
most down-to-earth technical expression of them, and not on the diﬀeren-
tial, conformal, Riemannian, holomorphic aspects, and (from there) on to
“complex algebraic curves”. Once this last step is taken, however, algebraic
geometry (my former love!) suddenly bursts forth once again, and this via
the objects which we can consider as the basic building blocks for all other
algebraic varieties. Whereas in my research before 1970, my attention was
2
3
systematically directed towards objects of maximal generality, in order to
uncover a general language adequate for the world of algebraic geometry,
and I never restricted myself to algebraic curves except when strictly neces-
sary (notably in etale cohomology), preferring to develop “pass-key” tech-
niques and statements valid in all dimensions and in every place (I mean,
over all base schemes, or even base ringed topoi...), here I was brought
back, via objects so simple that a child learns them while playing, to the
beginnings and origins of algebraic geometry, familiar to Riemann and his
followers!
Since around 1975, it is thus the geometry of (real) surfaces, and starting
in 1977 the links between questions of geometry of surfaces and the algebraic
geometry of algebraic curves deﬁned over ﬁelds such as C, R or extensions
of Q of ﬁnite type, which were my principal source of inspiration and my
constant guiding thread. It is with surprise and wonderment that over the
years I discovered (or rather, doubtless, rediscovered) the prodigious, truly
inexhaustible richness, the unsuspected depth of this theme, apparently so
anodine. I believe I feel a central sensitive point there, a privileged point
of convergence of the principal currents of mathematical ideas, and also of
the principal structures and visions of things which they express, from the
most speciﬁc (such as the rings Z, Q, Q, R, C or the group Sl(2) over one of
these rings, or general reductive algebraic groups) to the most “abstract”,
such as the algebraic “multiplicities”, complex analytic or real analytic.
(These are naturally introduced when systematically studying “moduli va-


---

Sketch of a Programme
241
rieties” for the geometric objects considered, if we want to go farther than
the notoriously insuﬃcient point of view of “coarse moduli” which comes
down to most unfortunately killing the automorphism groups of these ob-
jects.) Among these modular multiplicities, it is those of Mumford-Deligne
for “stable” algebraic curves of genus g with ν marked points,
which I
3
4
denote by c
Mg,ν (compactiﬁcation of the “open” multiplicity Mg,ν corre-
sponding to non-singular curves), which for the last two or three years have
exercised a particular fascination over me, perhaps even stronger than any
other mathematical object to this day. Indeed, it is more the system of all
the multiplicities Mg,ν for variable g, ν, linked together by a certain num-
ber of fundamental operations (such as the operations of “plugging holes”,
i.e. “erasing” marked points, and of “glueing”, and the inverse operations),
which are the reﬂection in absolute algebraic geometry in characteristic zero
(for the moment) of geometric operations familiar from the point of view of
topological or conformal “surgery” of surfaces. Doubtless the principal rea-
son of this fascination is that this very rich geometric structure on the system
of “open” modular multiplicities Mg,ν is reﬂected in an analogous structure
on the corresponding fundamental groupoids, the “Teichm¨uller groupoids”
bTg,ν, and that these operations on the level of the bTg,ν are suﬃciently intrin-
sic for the Galois group IΓ of Q/Q to act on this whole “tower” of Teichm¨uller
groupoids, respecting all these structures. Even more extraordinary, this ac-
tion is faithful – indeed, it is already faithful on the ﬁrst non-trivial “level”
of this tower, namely bT0,4 – which also means, essentially, that the outer
action of IΓ on the fundamental group ˆπ0,3 of the standard projective line P1
over Q with the three points 0, 1 and ∞removed, is already faithful. Thus
the Galois group IΓ can be realised as an automorphism group of a very
concrete proﬁnite group, and moreover respects certain essential structures
of this group. It follows that an element of IΓ can be “parametrised” (in
various equivalent ways) by a suitable element of this proﬁnite group ˆπ0,3
(a free proﬁnite group on two generators), or by a system of such elements,
these elements being subject to certain simple necessary (but doubtless not
suﬃcient) conditions for this or these elements to really correspond to an
element of IΓ. One of the most fascinating tasks here is precisely to discover
necessary and suﬃcient conditions on an exterior automorphism
of ˆπ0,3,
4
5
i.e. on the corresponding parameter(s), for it to come from an element of
IΓ – which would give a “purely algebraic” description, in terms of proﬁnite
groups and with no reference to the Galois theory of number ﬁelds, to the
Galois group IΓ = Gal(Q/Q).
Perhaps even a conjectural characterisation of IΓ as a subgroup of
Autextˆπ0,3 is for the moment out of reach (1); I do not yet have any conjec-
ture to propose. On the other hand another task is immediately accessible,


---

242
Alexandre Grothendieck
which is to describe the action of IΓ on all of the Teichm¨uller tower, in terms
of its action on the “ﬁrst level” ˆπ0,3, i.e. to express an automorphism of
this tower, in terms of the “parameter” in ˆπ0,3 which picks out the element
γ running through IΓ. This is linked to a representation of the Teichm¨uller
tower (considered as a groupoid equipped with an operation of “glueing”)
by generators and relations, which will in particular give a presentation by
generators and relations in the usual sense of each of the bTg,ν (as a proﬁnite
groupoid). Here, even for g = 0 (so when the corresponding Teichm¨uller
groups are “well-known” braid groups), the generators and relations known
to date which I have heard of appear to me to be unusable as they stand, be-
cause they do not present the characteristics of invariance and of symmetry
indispensable for the action of IΓ to be directly legible on the presentation.
This is particularly linked to the fact that people still obstinately persist,
when calculating with fundamental groups, in ﬁxing a single base point, in-
stead of cleverly choosing a whole packet of points which is invariant under
the symmetries of the situation, which thus get lost on the way. In cer-
tain situations (such as descent theorems for fundamental groups `a la van
Kampen) it is much more elegant, even indispensable for understanding
something, to work with fundamental groupoids with respect to a suitable
packet of base points, and it is certainly so for the Teichm¨uller tower. It
would seem (incredible, but true!) that even the geometry of the ﬁrst level
of the Teichm¨uller tower (corresponding thus to “moduli” either for projec-
tive lines with four marked points, or to elliptic curves (!)) has never been
5
6
explicitly described, for example the relation between the genus 0 case and
the geometry of the octahedron, and that of the tetrahedron. A fortiori the
modular multiplicities M0,5 (for projective lines with ﬁve marked points)
and M1,2 (for curves of genus 1 with two marked points), which actually
are practically isomorphic, appear to be virgin territory – braid groups will
not enlighten us on their score! I have begun to look at M0,5 at stray mo-
ments; it is a real jewel, with a very rich geometry closely related to the
geometry of the icosahedron.
The a priori interest of a complete knowledge of the two ﬁrst levels of the
tower (i.e., the cases where the modular dimension N = 3g −3+ν is ≤2) is
to be found in the principle that the entire tower can be reconstituted from
these two ﬁrst levels, in the sense that via the fundamental operation of
“glueing”, level 1 gives a complete system of generators, and level 2 a com-
plete system of relations. There is a striking analogy, and I am certain it
is not merely formal, between this principle and the analogous principle
of Demazure for the structure of reductive algebraic groups, if we replace
the term “level” or “modular dimension” with “semi-simple rank of the
reductive group”. The link becomes even more striking, if we recall that


---

Sketch of a Programme
243
the Teichm¨uller group T1,1 (in the discrete, transcendental context now,
and not in the proﬁnite algebraic context, where we ﬁnd the proﬁnite com-
pletions of the former) is no other than Sl(2, Z), i.e.
the group of inte-
gral points of the simple group scheme of “absolute” rank 1 Sl(2)Z. Thus,
the fundamental building block for the Teichm¨uller tower is essentially the
same as for the “tower” of reductive groups of all ranks – a group of which,
moreover, we may say that it is doubtless present in all the essential disci-
plines of mathematics.
This principle of construction of the Teichm¨uller tower is not proved at
this time – but I have no doubt that it is valid. It would be a consequence
(via a theory of d´evissage of stratiﬁed structures – here the c
Mg,ν – which
remains to be written, cf. par. 5) of an extremely plausible property of the
open modular multiplicities Mg,ν in the complex analytic context, namely
6
7
that for modular dimension N ≥3, the fundamental group of Mg,ν (i.e. the
usual Teichm¨uller group Tg,ν) is isomorphic to the “fundamental group at
inﬁnity”, i.e. that of a “tubular neighbourhood of inﬁnity”. This is a very
familiar thing (essentially due to Lefschetz) for a non-singular aﬃne variety
of dimension N ≥3. True, the modular multiplicities are not aﬃne (except
for small values of g), but it would suﬃce if such an Mg,ν of dimension N
(or rather, a suitable ﬁnite covering) were a union of N −2 aﬃne open sets,
making Mg,ν “not too near a compact variety”.
Having no doubt about this principle of construction of the Teichm¨uller
tower, I prefer to leave to the experts, better equipped than I am, the
task of proving the necessary (if it so happens that any are interested), to
rather study, with all the care it deserves, the structure which ensues for
the Teichm¨uller tower by generators and relations, this time in the discrete,
not the proﬁnite framework – which essentially comes down to a complete
understanding of the four modular multiplicities M0,4, M1,1, M0,5, M1,2
and their fundamental groupoids based at suitably chosen “base points”.
These oﬀer themselves quite naturally, as the complex algebraic curves of
the type (g, n) under consideration, having automorphism group (necessar-
ily ﬁnite) larger than in the generic case (*). Including the holomorphic
(*) It is also necessary to add the “base points” coming from operations of
glueing of “blocks” of the same type in smaller modular dimension. On
the other hand, in modular dimension 2 (the cases of M0,5 and M1,2), it is
advisable to exclude the points of certain one-parameter families of curves
admitting an exceptional automorphism of order 2. These families actu-
ally constitute remarkable rational curves on the multiplicities considered,
which appear to me to be an important ingredient in the structure of these
multiplicities.


---

244
Alexandre Grothendieck
sphere with three marked points (coming from M0,3, i.e. from level 0), we
7
8
ﬁnd twelve fundamental “building blocks” (6 of genus 0, 6 of genus 1) in a
“game of Lego-Teichm¨uller” (large box), where the points marked on the
surfaces considered are replaced by “holes” with boundary, so as to have
surfaces with boundary, functioning as building blocks which can be assem-
bled by gentle rubbing as in the ordinary game of Lego dear to our children
(or grandchildren...). By assembling them we ﬁnd an entirely visual way to
construct every type of surface (it is essentially these constructions which
will be the “base points” for our famous tower), and also to visualise the
elementary “paths” by operations as concrete as “twists”, or automorphisms
of blocks in the game, and to write the fundamental relations between com-
posed paths. According to the size (and the price!) of the construction box
used, we can even ﬁnd numerous diﬀerent descriptions of the Teichm¨uller
tower by generators and relations. The smallest box is reduced to identi-
cal blocks, of type (0, 3) – these are the Thurston “pants”, and the game
of Lego-Teichm¨uller which I am trying to describe, springing from motiva-
tions and reﬂections of absolute algebraic geometry over the ﬁeld Q, is very
close to the game of “hyperbolic geodesic surgery” of Thurston, whose exis-
tence I learned of last year from Yves Ladegaillerie. In a microseminar with
Carlos Contou-Carr`ere and Yves Ladegaillerie, we began a reﬂection one
of whose objects is to confront the two points of view, which are mutually
complementary.
I add that each of the twelve building blocks of the “large box” is equipped
with a canonical cellular decomposition, stable under all symmetries, having
as its only vertices the “marked points” (or centres of the holes), and as
edges certain geodesic paths (for the canonical Riemannian structure on the
sphere or the torus considered) between certain pairs of vertices (namely
those which lie on the same “real locus”, for a suitable real structure of
the complex algebraic curve considered).
Consequently, all the surfaces
obtained in this game by assembling are equipped with canonical cellular
structures, which in their turn (cf. §3 below) enable us to consider these
8
9
surfaces as associated to complex algebraic curves (and even over Q) which
are canonically determined. There is here a typical game of intertwining of
the combinatorial and the complex algebraic (or rather, the algebraic over
Q).
The “small box” with identical blocks, which has the charm of economy,
will doubtless give rise to a relatively complex description for the relations
(complex, but not at all inextricable!).
The large box will give rise to
more numerous relations (because there are many more base points and
remarkable paths between them), but with a more transparent structure.
I foresee that in modular dimension 2, just as in the more or less familiar


---

Sketch of a Programme
245
case of modular dimension 1 (in particular with the description of Sl(2, Z)
by (ρ, σ | ρ3 = σ2, ρ4 = σ6 = 1)), we will ﬁnd a generation by the auto-
morphism groups of the three types of relevant blocks, with simple relations
which I have not clariﬁed as I write these lines. Perhaps we will even ﬁnd
a principle of this type for all the Tg,ν, as well as a cellular decomposition
of c
Mg,ν generalising those which present themselves spontaneously for c
M0,4
and c
M1,1, and which I already perceive for modular dimension 2, using the
hypersurfaces corresponding to the various real structures on the complex
structures considered, to eﬀect the desired cellular decomposition.
3.
Instead of following (as I meant to) a rigorous thematic order, I let
myself be carried away by my predilection for a particularly rich and burning
theme, to which I intend to devote myself prioritarily for some time, starting
at the beginning of the academic year 84/85. Thus I will take the thematic
description up again where I left it, at the very beginning of the preceding
paragraph.
My interest in topological surfaces began to appear in 1974, when I pro-
posed to Yves Ladegaillerie the theme of the isotopic study of embeddings
of a topological 1-complex into a compact surface. Over the two following
years, this study led him to a remarkable isotopy theorem, giving a com-
plete algebraic description of the
isotopy classes of embeddings of such
9
10
1-complexes, or compact surfaces with boundary, in a compact oriented
surface, in terms of certain very simple combinatorial invariants, and the
fundamental groups of the protagonists. This theorem, which should be
easily generalisable to embeddings of any compact space (triangulable to
simplify) in a compact oriented surface, gives as easy corollaries several
deep classical results in the theory of surfaces, and in particular Baer’s iso-
topy theorem. It will ﬁnally be published, separately from the rest (and
ten years later, seeing the diﬃculty of the times...), in Topology. In the
work of Ladegaillerie there is also a purely algebraic description, in terms
of fundamental groups, of the “isotopic” category of compact surfaces X,
equipped with a topological 1-complex K embedded in X. This description,
which had the misfortune to run counter to “today’s taste” and because of
this appears to be unpublishable, nevertheless served (and still serves) as a
precious guide in my later reﬂections, particularly in the context of absolute
algebraic geometry in characteristic zero.
The case where (X, K) is a 2-dimensional “map”, i.e. where the connected
components of X\K are open 2-cells (and where moreover K is equipped
with a ﬁnite set S of “vertices”, such that the connected components of
K\S are open 1-cells) progressively attracted my attention over the follow-
ing years. The isotopic category of these maps admits a particularly simple


---

246
Alexandre Grothendieck
algebraic description, via the set of “markers” (or “ﬂags”, or “biarcs”) as-
sociated to the map, which is naturally equipped with the structure of a set
with a group of operators, under the group
C2 =< σ0, σ1, σ2 | σ2
0 = σ2
1 = σ2
2 = (σ0σ2)2 = 1 >,
which I call the (non-oriented) cartographic group of dimension 2. It admits
as a subgroup of index 2 the oriented cartographic group, generated by the
products of an even number of generators, which can also be described by
C+
2 =< ρs, ρf, σ | ρsρf = σ, σ2 = 1 >,
(with
ρs = σ2σ1,
ρf = σ1σ0,
σ = σ0σ2 = σ2σ0,
operations of elementary rotation of a ﬂag around a vertex, a face and an
10
11
edge respectively). There is a perfect dictionary between the topological
situation of compact maps, resp. oriented compact maps, on the one hand,
and ﬁnite sets with group of operators C2 resp. C+
2 on the other, a dictio-
nary whose existence was actually more or less known, but never stated with
the necessary precision, nor developed at all. This foundational work was
done with the care it deserved in an excellent DEA thesis, written jointly
by Jean Malgoire and Christine Voisin in 1976.
This reﬂection suddenly takes on a new dimension, with the simple remark
that the group C+
2 can be interpreted as a quotient of the fundamental group
of an oriented sphere with three points, numbered 0, 1 and 2, removed; the
operations ρs, σ, ρf are interpreted as loops around these points, satisfying
the familiar relation
ℓ0ℓ1ℓ2 = 1,
while the additional relation σ2 = 1, i.e. ℓ2
1 = 1 means that we are in-
terested in the quotient of the fundamental group corresponding to an im-
posed ramiﬁcation index of 2 over the point 1, which thus classiﬁes the
coverings of the sphere ramiﬁed at most over the points 0, 1 and 2 with
ramiﬁcation equal to 1 or 2 at the points over 1. Thus, the compact ori-
ented maps form an isotopic category equivalent to that of these cover-
ings, subject to the additional condition of being ﬁnite coverings.
Now
taking the Riemann sphere, or the projective complex line, as reference
sphere, rigidiﬁed by the three points 0, 1 and ∞(this last thus replacing
2), and recalling that every ﬁnite ramiﬁed covering of a complex algebraic
curve itself inherits the structure of a complex algebraic curve, we arrive
at this fact, which eight years later still appears to me as extraordinary:
every “ﬁnite” oriented map is canonically realised on a complex algebraic


---

Sketch of a Programme
247
curve!
Even better,
as the complex projective line is deﬁned over the
11
12
absolute base ﬁeld Q, as are the admitted points of ramiﬁcation, the alge-
braic curves we obtain are deﬁned not only over C, but over the algebraic
closure Q of Q in C. As for the map we started with, it can be found on
the algebraic curve, as the inverse image of the real segment [0, 1] (where 0
is considered as a vertex, and 1 as the middle of a “folded edge” of centre
1), which itself is the “universal oriented 2-map” on the Riemann sphere
(*). The points of the algebraic curve X over 0, 1 and ∞are neither more
nor less than the vertices, the “centres” of the edges and those of the faces
of the map (X, K), and the orders of the vertices and the faces are exactly
the multiplicities of the zeros and the poles of the rational function (deﬁned
over Q) on X, which expresses its structural projection to P1
C.
This discovery, which is technically so simple, made a very strong im-
pression on me, and it represents a decisive turning point in the course of
my reﬂections, a shift in particular of my centre of interest in mathema-
tics, which suddenly found itself strongly focused. I do not believe that a
mathematical fact has ever struck me quite so strongly as this one, nor had
a comparable psychological impact (2). This is surely because of the very
familiar, non-technical nature of the objects considered, of which any child’s
drawing scrawled on a bit of paper (at least if the drawing is made without
lifting the pencil) gives a perfectly explicit example. To such a dessin, we
ﬁnd associated subtle arithmetic invariants, which are completely turned
topsy-turvy as soon as we add one more stroke. Since these are spherical
maps, giving rise to curves of genus 0 (which thus do not lead to “moduli”),
12
13
we can say that the curve in question is “pinned down” if we ﬁx three of
its points, for instance three vertices of the map, or more generally three
centres of facets (vertices, edges or faces) – and then the structural map
f : X →P1
C can be interpreted as a well-determined rational function
f(z) = P(z)/Q(z) ∈C(z),
quotient of two well-determined relatively prime polynomials, with Q uni-
tary, satisfying algebraic conditions which in particular reﬂect the fact that
f is unramiﬁed outside of 0, 1 and ∞, and which imply that the coeﬃcients
(*) There is an analogous description of ﬁnite non-oriented maps, possibly
with boundary, in terms of real algebraic curves, more precisely of coverings
of P1
R ramiﬁed only over 0, 1, ∞, the surface with boundary associated
to such a covering being X(C)/τ, where τ is complex conjugation. The
“universal” non-oriented map is here the disk, or upper hemisphere of the
Riemann sphere, equipped as before with the embedded 1-complex K =
[0, 1].


---

248
Alexandre Grothendieck
of these polynomials are algebraic numbers; thus their zeros are algebraic
numbers, which represent respectively the vertices and the centres of the
faces of the map under consideration.
Returning to the general case, since ﬁnite maps can be interpreted as
coverings over Q of an algebraic curve deﬁned over the prime ﬁeld Q itself,
it follows that the Galois group IΓ of Q over Q acts on the category of these
maps in a natural way. For instance, the operation of an automorphism
γ ∈IΓ on a spherical map given by the rational function above is obtained
by applying γ to the coeﬃcients of the polynomials P, Q. Here, then, is
that mysterious group IΓ intervening as a transforming agent on topologico-
combinatorial forms of the most elementary possible nature, leading us to
ask questions like: are such and such oriented maps “conjugate” or: exactly
which are the conjugates of a given oriented map? (Visibly, there is only a
ﬁnite number of these).
I considered some concrete cases (for coverings of low degree) by vari-
ous methods, J. Malgoire considered some others – I doubt that there is
a uniform method for solving the problem by computer.
My reﬂection
quickly
took a more conceptual path, attempting to apprehend the na-
13
14
ture of this action of IΓ. One sees immediately that roughly speaking, this
action is expressed by a certain “outer” action of IΓ on the proﬁnite com-
pactiﬁcation of the oriented cartographic group C+
2 , and this action in its
turn is deduced by passage to the quotient of the canonical outer action of
IΓ on the proﬁnite fundamental group ˆπ0,3 of (U0,3)Q, where U0,3 denotes
the typical curve of genus 0 over the prime ﬁeld Q, with three points re-
moved. This is how my attention was drawn to what I have since termed
“anabelian algebraic geometry”, whose starting point was exactly a study
(limited for the moment to characteristic zero) of the action of “absolute”
Galois groups (particularly the groups Gal(K/K), where K is an exten-
sion of ﬁnite type of the prime ﬁeld) on (proﬁnite) geometric fundamental
groups of algebraic varieties (deﬁned over K), and more particularly (break-
ing with a well-established tradition) fundamental groups which are very far
from abelian groups (and which for this reason I call “anabelian”). Among
these groups, and very close to the group ˆπ0,3, there is the proﬁnite com-
pactiﬁcation of the modular group Sl(2, Z), whose quotient by its centre
±1 contains the former as congruence subgroup mod 2, and can also be
interpreted as an oriented “cartographic” group, namely the one classify-
ing triangulated oriented maps (i.e. those whose faces are all triangles or
monogons).
Every ﬁnite oriented map gives rise to a projective non-singular algebraic
curve deﬁned over Q, and one immediately asks the question: which are
the algebraic curves over Q obtained in this way – do we obtain them all,


---

Sketch of a Programme
249
who knows? In more erudite terms, could it be true that every projective
non-singular algebraic curve deﬁned over a number ﬁeld occurs as a possi-
ble “modular curve” parametrising elliptic curves equipped with a suitable
rigidiﬁcation? Such a supposition seemed so crazy that I was almost em-
14
15
barrassed to submit it to the competent people in the domain.
Deligne
when I consulted him found it crazy indeed, but didn’t have any counterex-
ample up his sleeve. Less than a year later, at the International Congress
in Helsinki, the Soviet mathematician Bielyi announced exactly that result,
with a proof of disconcerting simplicity which ﬁt into two little pages of a
letter of Deligne – never, without a doubt, was such a deep and disconcerting
result proved in so few lines!
In the form in which Bielyi states it, his result essentially says that
every algebraic curve deﬁned over a number ﬁeld can be obtained as a
covering of the projective line ramiﬁed only over the points 0, 1 and ∞.
This result seems to have remained more or less unobserved. Yet it appears
to me to have considerable importance.
To me, its essential message is
that there is a profound identity between the combinatorics of ﬁnite maps
on the one hand, and the geometry of algebraic curves deﬁned over num-
ber ﬁelds on the other.
This deep result, together with the algebraic-
geometric interpretation of maps, opens the door onto a new, unexplored
world – within reach of all, who pass by without seeing it.
It was only close to three years later, seeing that decidedly the vast hori-
zons opening here caused nothing to quiver in any of my students, nor even
in any of the three or four high-ﬂying colleagues to whom I had occasion
to talk about it in a detailed way, that I made a ﬁrst scouting voyage into
this “new world”, from January to June 1981.
This ﬁrst foray materi-
alised into a packet of some 1300 handwritten pages, baptised “The Long
March through Galois theory”. It is ﬁrst and foremost an attempt at un-
derstanding the relations between “arithmetic” Galois groups and proﬁnite
“geometric” fundamental groups. Quite quickly it became oriented towards
a work of computational formulation of the action of Gal(Q/Q) on ˆπ0,3, and
at a later stage, on the somewhat larger group \
Sl(2, Z), which gives rise to
a more elegant and eﬃcient formalism. Also during the course of this work
(but developed in a diﬀerent set of notes) appeared the central theme of
15
16
anabelian algebraic geometry, which is to reconstitute certain so-called “an-
abelian” varieties X over an absolute ﬁeld K from their mixed fundamental
group, the extension of Gal(K/K) by π1(XK); this is when I discovered
the “fundamental conjecture of anabelian algebraic geometry”, close to the
conjectures of Mordell and Tate recently proved by Faltings (3). This period
also saw the appearance of the ﬁrst reﬂection on the Teichm¨uller groups, and
the ﬁrst intuitions on the many-faceted structure of the “Teichm¨uller tower”


---

250
Alexandre Grothendieck
– the open modular multiplicities Mg,ν also appearing as the ﬁrst important
examples in dimension > 1, of varieties (or rather, multiplicities) seeming
to deserve the appellation of “anabelian”. Towards the end of this period
of reﬂection, it appeared to me as a fundamental reﬂection on a theory still
completely up in the air, for which the name “Galois-Teichm¨uller theory”
seems to me more appropriate than the name “Galois Theory” which I had
at ﬁrst given to my notes. Here is not the place to give a more detailed
description of this set of questions, intuitions, ideas – which even includes
some tangible results. The most important thing seems to me to be the
one pointed out in par. 2, namely the faithfulness of the outer action of
IΓ = Gal(Q/Q) (and of its open subgroups) on ˆπ0,3, and more generally
(if I remember rightly) on the fundamental group of any “anabelian” alge-
braic curve (i.e. whose genus g and “number of holes” ν satisfy the equality
2g + ν ≥3, i.e. such that χ(X) < 0) deﬁned over a ﬁnite extension of
Q. This result can be considered to be essentially equivalent to Bielyi’s
theorem – it is the ﬁrst concrete manifestation, via a precise mathematical
statement, of the “message” which was discussed above.
I would like to conclude this rapid outline with a few words of commen-
tary on the truly unimaginable richness of a typical anabelian group such
as Sl(2, Z) – doubtless the most remarkable discrete inﬁnite group ever en-
countered,
which appears in a multiplicity of avatars (of which certain
16
17
have been brieﬂy touched on in the present report), and which from the
point of view of Galois-Teichm¨uller theory can be considered as the fun-
damental “building block” of the “Teichm¨uller tower”. The element of the
structure of Sl(2, Z) which fascinates me above all is of course the outer
action of IΓ on its proﬁnite compactiﬁcation.
By Bielyi’s theorem, tak-
ing the proﬁnite compactiﬁcations of subgroups of ﬁnite index of Sl(2, Z),
and the induced outer action (up to also passing to an open subgroup of
IΓ), we essentially ﬁnd the fundamental groups of all algebraic curves (not
necessarily compact) deﬁned over number ﬁelds K, and the outer action of
Gal(K/K) on them – at least it is true that every such fundamental group
appears as a quotient of one of the ﬁrst groups (*). Taking the “anabelian
yoga” (which remains conjectural) into account, which says that an an-
abelian algebraic curve over a number ﬁeld K (ﬁnite extension of Q) is
known up to isomorphism when we know its mixed fundamental group (or
what comes to the same thing, the outer action of Gal(K/K) on its proﬁnite
geometric fundamental group), we can thus say that all algebraic curves
deﬁned over number ﬁelds are “contained” in the proﬁnite compactiﬁcation
(*) In fact, we are considering quotients of a particularly trivial nature, by
abelian subgroups which are products of “Tate modules” ˆZ(1), correspond-
ing to “loop-groups” around points at inﬁnity.


---

Sketch of a Programme
251
\
Sl(2, Z), and in the knowledge of a certain subgroup IΓ of its group of outer
automorphisms! Passing to the abelianisations of the preceding fundamen-
tal groups, we see in particular that all the abelian ℓ-adic representations
dear to Tate and his circle, deﬁned by Jacobians and generalised Jacobians
of algebraic curves deﬁned over number ﬁelds, are contained in this single
action of IΓ on the anabelian proﬁnite group \
Sl(2, Z)! (4)
There are people who, faced with this, are content to shrug their shoul-
17
18
ders with a disillusioned air and to bet that all this will give rise to nothing,
except dreams. They forget, or ignore, that our science, and every science,
would amount to little if since its very origins it were not nourished with
the dreams and visions of those who devoted themselves to it.
4. From the very start of my reﬂection on 2-dimensional maps, I was most
particularly interested by the “regular” maps, those whose automorphism
group acts transitively (and consequently, simply transitively) on the set of
ﬂags. In the oriented case and in terms of the algebraic-geometric interpre-
tation given in the preceding paragraph, it is these maps which correspond
to Galois coverings of the projective line. Very quickly also, and even before
the appearance of the link with algebraic geometry, it appears necessary not
to exclude the inﬁnite maps, which in particular occur in a natural way as
universal coverings of ﬁnite maps. It appears (as an immediate consequence
of the “dictionary” of maps, extended to the case of maps which are not
necessarily ﬁnite) that for every pair of natural integers p, q ≥1, there exists
up to non-unique isomorphism one and only one 1-connected map of type
(p, q), i.e. all of whose vertices are of order p and whose faces are of order
q, and this map is a regular map. It is pinned down by the choice of a ﬂag,
and its automorphism group is then canonically isomorphic to the quotient
of the cartographic group (resp. of the oriented cartographic group, in the
oriented case) by the additional relations
ρp
s = ρq
f = 1.
The case where this group is ﬁnite is the “Pythagorean” case of regular
spherical maps, the case where it is inﬁnite gives the regular tilings of the
18
19
Euclidean plane or of the hyperbolic plane (*). The link between combina-
torial theory and the “conformal” theory of regular tilings of the hyperbolic
plane was foreshadowed, before the appearance of the link between ﬁnite
maps and ﬁnite coverings of the projective line. Once this link is understood,
(*) In these statements, we must not exclude the case where p, q can take
the value +∞, which is encountered in particular in a very natural way as
tilings associated to certain regular inﬁnite polyhedra, cf. below.


---

252
Alexandre Grothendieck
it becomes obvious that it should also extend to inﬁnite maps (regular or
not): every map, ﬁnite or not, can be canonically realised on a conformal
surface (compact if and only if the map is ﬁnite), as a ramiﬁed covering of
the complex projective line, ramiﬁed only over the points 0, 1 and ∞. The
only diﬃculty here was to develop the dictionary between topological maps
and sets with operators, which gave rise to some conceptual problems in
the inﬁnite case, starting with the very notion of a “topological map”. It
appears necessary in particular, both for reasons of internal coherence of the
dictionary and not to let certain interesting cases of inﬁnite maps escape,
to avoid excluding vertices and faces of inﬁnite order. This foundational
work was also done by J. Malgoire and C. Voisin, in the wake of their ﬁrst
work on ﬁnite maps, and their theory indeed gives everything that we could
rightly expect (and even more...)
In 1977 and 1978, in parallel with two C4 courses on the geometry of the
cube and that of the icosahedron, I began to become interested in regular
polyhedra, which then appeared to me as particularly concrete “geometric
realizations” of combinatorial maps, the vertices, edges and faces being
realised as points, lines and planes respectively in a suitable 3-dimensional
aﬃne space, and respecting incidence relations. This notion of a geometric
realisation
of a combinatorial map keeps its meaning over an arbitrary
19
20
base ﬁeld, and even over an arbitrary base ring. It also keeps its meaning
for regular polyhedra in any dimension, if the cartographic group C2 is
replaced by a suitable n-dimensional analogue Cn. The case n = 1, i.e.
the theory of regular polygons in any characteristic, was the subject of a
DEA course in 1977/78, and already sparks the appearance of some new
phenomena, as well as demonstrating the usefulness of working not in an
ambient aﬃne space (here the aﬃne plane), but in a projective space. This
is in particular due to the fact that in certain characteristics (in particular
in characteristic 2) the centre of a regular polyhedron is sent oﬀto inﬁnity.
Moreover, the projective context, contrarily to the aﬃne context, enables us
to easily develop a duality formalism for regular polyhedra, corresponding
to the duality formalism of combinatorial or topological maps (where the
roles of the vertices and the faces, in the case n = 2 say, are exchanged). We
ﬁnd that for every projective regular polyhedron, we can deﬁne a canonical
associated hyperplane, which plays the role of a canonical hyperplane at
inﬁnity, and allows us to consider the given polyhedron as an aﬃne regular
polyhedron.
The extension of the theory of regular polyhedra (and more generally,
of all sorts of geometrico-combinatorial conﬁgurations, including root sys-
tems...) of the base ﬁeld R or C to a general base ring, seems to me to
have an importance comparable, in this part of geometry, to the analogous


---

Sketch of a Programme
253
extension which has taken place since the beginning of the century in al-
gebraic geometry, or over the last twenty years in topology (*), with the
introduction of the language of schemes and of topoi.
My sporadic re-
20
21
ﬂection on this question, over some years, was limited to discovering some
simple basic principles, concentrating my attention ﬁrst and foremost on
the case of pinned regular polyhedra, which reduces to a minimum the nec-
essary conceptual baggage, and practically eliminates the rather delicate
questions of rationality. For such a polyhedron, we ﬁnd a canonical basis
(or ﬂag) of the ambient aﬃne or projective space, such that the operations
of the cartographic group Cn, generated by the fundamental reﬂections σi
(0 ≤i ≤n), are written in that basis by universal formulae, in terms of
the n parameters α1, . . . , αn, which can be geometrically interpreted as the
doubles of the cosines of the “fundamental angles” of the polyhedron. The
polyhedron can be reconstituted from this action, and from the aﬃne or
projective ﬂag associated to the chosen basis, by transforming this ﬂag by
all the elements of the group generated by the fundamental reﬂections. Thus
the “universal” pinned n-polyhedron is canonically deﬁned over the ring of
polynomials with n indeterminates
Z[α1, . . . , αn],
its specialisations to arbitrary base ﬁelds k (via values αi ∈k given to the
indeterminates αi) giving regular polyhedra corresponding to various com-
binatorial types. In this game, there is no question of limiting oneself to
ﬁnite regular polyhedra, nor even to regular polyhedra whose facets are of
ﬁnite order, i.e. for which the parameters αi are roots of suitable “semicy-
clotomic” equations, expressing the fact that the “fundamental angles” (in
the case where the base ﬁeld is R) are commensurable with 2π. Already
when n = 1, perhaps the most interesting regular polygon (morally the reg-
ular polygon with only one side!) is the one corresponding to α = 2, giving
rise to a parabolic circumscribed conic, i.e. tangent to the line at inﬁnity.
The ﬁnite case is the one where the group generated by the fundamental
reﬂections, which is also the automorphism group of the regular polyhedron
considered, is ﬁnite. In the case where the base ﬁeld is R (or C, which comes
21
22
to the same thing), and for n = 2, the ﬁnite cases have been well-known
since antiquity – which does not exclude that the schematic point of view
unveils new charms; we can however say that when specialising the icosahe-
dron (for example) to ﬁnite base ﬁelds of arbitrary characteristic, it remains
(*) In writing this, I am aware that rare are the topologists, even today,
who realise the existence of this conceptual and technical generalisation of
topology, and the resources it oﬀers.


---

254
Alexandre Grothendieck
an icosahedron, with its own personal combinatorics and the same simple
group of automorphisms of order 60. The same remark applies to ﬁnite reg-
ular polyhedra in higher dimension, which were systematically studied in
two beautiful books by Coxeter. The situation is entirely diﬀerent if we start
from an inﬁnite regular polyhedron, over a ﬁeld such as Q, for instance, and
“specialise” it to the prime ﬁelds Fp (a well-deﬁned operation for all p except
a ﬁnite number of primes). It is clear that every regular polyhedron over a
ﬁnite ﬁeld is ﬁnite – we thus ﬁnd an inﬁnity of ﬁnite regular polyhedra as
p varies, whose combinatorial type, or equivalently, whose automorphism
group varies “arithmetically” with p. This situation is particularly intrigu-
ing in the case where n = 2, where we can use the relation made explicit
in the preceding paragraph between combinatorial 2-maps and algebraic
curves deﬁned over number ﬁelds. In this case, an inﬁnite regular polyhe-
dron deﬁned over any inﬁnite ﬁeld (and therefore, over a sub-Z-algebra of it
with two generators) thus gives rise to an inﬁnity of algebraic curves deﬁned
over number ﬁelds, which are Galois coverings ramiﬁed only over 0, 1 and
∞of the standard projective line. The optimal case is of course the one
deduced by passage to the ﬁeld of fractions Q(α1, α2) of its base ring. This
raises a host of new questions, both vague and precise, none of which I have
up till now had leisure to examine closely – I will cite only this one: exactly
which are the ﬁnite regular 2-maps, or equivalently, the ﬁnite quotients of
22
23
the 2-cartographic group, which come from regular 2-polyhedra over ﬁnite
ﬁelds (*)? Do we obtain them all, and if yes: how?
These reﬂections shed a special light on the fact, which to me was com-
pletely unexpected, that the theory of ﬁnite regular polyhedra, already in
the case of dimension n = 2, is inﬁnitely richer, and in particular gives
inﬁnitely many more diﬀerent combinatorial forms, in the case where we
admit base ﬁelds of non-zero characteristic, than in the case considered up
to now, where the base ﬁelds were always restricted to R, or at best C (in
the case of what Coxeter calls “complex regular polyhedra”, and which I
prefer to call “regular pseudo-polyhedra deﬁned over C”) (**). Moreover,
it seems that this extension of the point of view should also shed new light
(*) These are actually the same as those coming from regular polyhedra de-
ﬁned over arbitrary ﬁelds, or algebraically closed ﬁelds, as can be seen using
standard specialisation arguments.
(**) The pinned pseudo-polyhedra are described in the same way as the pinned
polyhedra, with the only diﬀerence that the fundamental reﬂections σi (0 ≤
i ≤n) are here replaced by pseudo-reﬂections (which Coxeter assumes of
ﬁnite order, since he restricts himself to ﬁnite combinatorial structures).
This simply leads to the introduction for each of the σi of an additional
numerical invariant βi, such that the universal n-pseudo-polyhedron can


---

Sketch of a Programme
255
on the already known cases. Thus, examining the Pythagorean polyhedra
one after the other, I saw that the same small miracle was repeated each
time, which I called the combinatorial paradigm of the polyhedra under
consideration. Roughly speaking, it can be described by saying that when
we consider the specialisation of the polyhedra in the or one of the most
singular characteristic(s) (namely characteristics 2 and 5 for the icosahe-
23
24
dron, characteristic 2 for the octahedron), we read oﬀfrom the geometric
regular polyhedron over the ﬁnite ﬁeld (F4 and F5 for the icosahedron, F2
for the octahedron) a particularly elegant (and unexpected) description of
the combinatorics of the polyhedron. It seems to me that I perceived there
a principle of great generality, which I believed I found again for example in
a later reﬂection on the combinatorics of the system of 27 lines on a cubic
surface, and its relations with the root system E7. Whether it happens that
such a principle really exists, and even that we succeed in uncovering it from
its cloak of fog, or that it recedes as we pursue it and ends up vanishing like
a Fata Morgana, I ﬁnd in it for my part a force of motivation, a rare fasci-
nation, perhaps similar to that of dreams. No doubt that following such an
unformulated call, the unformulated seeking form, from an elusive glimpse
which seems to take pleasure in simultaneously hiding and revealing itself
– can only lead far, although no one could predict where...
However, occupied by other interests and tasks, I have not up to now
followed this call, nor met any other person willing to hear it, much less to
follow it. Apart from some digressions towards other types of geometrico-
combinatorial structures, my work on the question has been limited to a
ﬁrst eﬀort of reﬁning and housekeeping, which it is useless for me to de-
scribe further here (5). The only point which perhaps still deserves to be
mentioned is the existence and uniqueness of a hyperquadric circumscrib-
ing a given regular n-polyhedron, whose equation can be given explicitly
by simple formulae in terms of the fundamental parameters αi (*). The
case which interests me most is when n = 2, and the moment seems ripe
24
25
to rewrite a new version, in modern style, of Klein’s classic book on the
icosahedron and the other Pythagorean polyhedra. Writing such an expos´e
on regular 2-polyhedra would be a magniﬁcent opportunity for a young re-
searcher to familiarise himself with the geometry of polyhedra as well as
also be deﬁned over a ring of polynomials with integral coeﬃcients, in the
n + (n + 1) variables αi (1 ≤i ≤n) and βj (0 ≤i ≤n).
(*) An analogous result is valid for pseudo-polyhedra. It would seem that
the “exceptional characteristics” we discussed above, for specialisations of
a given polyhedron, are those for which the circumscribed hyperquadric is
either degenerate or tangent to the hyperplane at inﬁnity.


---

256
Alexandre Grothendieck
their connections with spherical, Euclidean and hyperbolic geometry and
with algebraic curves, and with the language and the basic techniques of
modern algebraic geometry. Will there be found one, some day, who will
seize this opportunity?
5. I would like to say a few words now about some topological consider-
ations which have made me understand the necessity of new foundations
for “geometric” topology, in a direction quite diﬀerent from the notion of
topos, and actually independent of the needs of so-called “abstract” alge-
braic geometry (over general base ﬁelds and rings). The problem I started
from, which already began to intrigue me some ﬁfteen years ago, was that of
deﬁning a theory of “d´evissage” for stratiﬁed structures, in order to rebuild
them, via a canonical process, out of “building blocks” canonically deduced
from the original structure. Probably the main example which had led me
to that question was that of the canonical stratiﬁcation of a singular alge-
braic variety (or a complex or real singular space) through the decreasing
sequence of its successive singular loci. But I probably had the premonition
of the ubiquity of stratiﬁed structures in practically all domains of geometry
(which surely others had seen clearly a long time before). Since then, I have
seen such structures appear, in particular, in any situation where “moduli”
are involved for geometric objects which may undergo not only continuous
variations, but also “degeneration” (or “specialisation”) phenomena – the
strata corresponding then to the various “levels of singularity” (or to the
associated combinatorial types) for the objects in question.
The com-
25
26
pactiﬁed modular multiplicities c
Mg,ν of Mumford-Deligne for the stable
algebraic curves of type (g, ν) provide a typical and particularly inspiring
example, which played an important motivating role when I returned to
my reﬂection about stratiﬁed structures, from December 1981 to January
1982.
Two-dimensional geometry provides many other examples of such
modular stratiﬁed structures, which all (if not using rigidiﬁcation) appear
as “multiplicities” rather than as spaces or manifolds in the usual sense
(as the points of these multiplicities may have non-trivial automorphism
groups). Among the objects of two-dimensional geometry which give rise to
such modular stratiﬁed structures in arbitrary dimensions, or even inﬁnite
dimension, I would list polygons (Euclidean, spherical or hyperbolic), sys-
tems of straight lines in a plane (say projective), systems of “pseudo straight
lines” in a projective topological plane, or more general immersed curves
with normal crossings, in a given (say compact) surface.
The simplest non-trivial example of a stratiﬁed structure is obtained by
considering a pair (X, Y ) of a space X and a closed subspace Y , with a
suitable assumption of equisingularity of X along Y , and assuming moreover


---

Sketch of a Programme
257
(to ﬁx ideas) that both strata Y and X \ Y are topological manifolds. The
naive idea, in such a situation, is to consider “the” tubular neighbourhood
T of Y in X, whose boundary ∂T should also be a smooth manifold, ﬁbred
with compact smooth ﬁbres over Y , whereas T itself can be identiﬁed with
the conical ﬁbration associated to the above one. Setting
U = X \ Int(T),
one ﬁnds a manifold with boundary, whose boundary is canonically isomor-
phic to the boundary of T. This being said, the “building blocks” are the
manifold with boundary U (compact if X is compact, and which replaces
and reﬁnes the “open” stratum X \ Y ) and the manifold (without bound-
26
27
ary) Y , together with, as an additional structure which connects them, the
“glueing” map
f : ∂U −→Y
which is a proper and smooth ﬁbration. The original situation (X, Y ) can
be recovered from (U, Y, f : ∂U →Y ) via the formula
X ∼= U
a
∂U
Y
(amalgamated sum over ∂U, mapping into U and Y by inclusion resp. the
glueing map).
This naive vision immediately encounters various diﬃculties. The ﬁrst is
the somewhat vague nature of the very notion of tubular neighbourhood,
which acquires a tolerably precise meaning only in the presence of struc-
tures which are much more rigid than the mere topological structure, such
as “piecewise linear” or Riemannian (or more generally, space with a dis-
tance function) structure; the trouble here is that in the examples which
naturally come to mind, one does not have such structures at one’s disposal
– at best an equivalence class of such structures, which makes it possible
to rigidify the situation somewhat. If on the other hand one assumes that
one might ﬁnd an expedient in order to produce a tubular neighbourhood
having the desired properties, which moreover would be unique modulo an
automorphism (say a topological one) of the situation – an automorphism
which moreover respects the ﬁbred structure provided by the glueing map,
there still remains the diﬃculty arising from the lack of canonicity of the
choices involved, as the said automorphism is obviously not unique, what-
ever may be done in order to “normalise” it. The idea here, in order to make
canonical something which is not, is to work systematically in the framework
of the “isotopic categories” associated to the categories of a topological na-
ture which are naturally present in such questions (such as the category of


---

258
Alexandre Grothendieck
admissible pairs (X, Y ) and homeomorphisms of such pairs etc.), retaining
the same objects, but deﬁning as “morphisms”
the isotopy classes (in a
27
28
sense which is dictated unambiguously by the context) of isomorphisms (or
even morphisms more general than isomorphisms). I used this idea, which
is taken up successfully in the thesis of Yves Ladegaillerie (see beginning
of par. 3), in a systematic way in all my later reﬂections on combinatorial
topology, when it came to a precise formulation of translation theorems of
topological situations in terms of combinatorial situations. In the present
situation, my hope was to be able to formulate (and prove!) a theorem
of equivalence between two suitable isotopic categories, one being the cate-
gory of “admissible pairs” (X, Y ), and the other the category of “admissible
triples” (U, Y, f), where Y is a manifold, U a manifold with boundary, and
f : ∂U →Y a smooth and proper ﬁbration. Moreover, I hoped that such a
statement could be naturally extended, modulo some essentially algebraic
work, to a more general statement, which would apply to general stratiﬁed
structures.
It soon appeared that there could be no question of getting such an am-
bitious statement in the framework of topological spaces, because of the
sempiternal “wild” phenomena. Already when X itself is a manifold and
Y is reduced to a point, one is confronted with the diﬃculty that the cone
over a compact space Z can be a manifold at its vertex, even if Z is not
homeomorphic to a sphere, nor even a manifold. It was also clear that the
contexts of the most rigid structures which existed then, such as the “piece-
wise linear” context were equally inadequate – one common disadvantage
consisting in the fact that they do not make it possible, given a pair (U, S)
of a “space” U and a closed subspace S, and a glueing map f : S →T,
to build the corresponding amalgamated sum. Some years later, I was told
of Hironaka’s theory of what he calls, I believe, (real) “semi-analytic” sets
which satisfy certain essential stability conditions (actually probably all of
them), which are necessary to develop a usable framework of “tame topo-
28
29
logy”. This triggered a renewal of the reﬂection on the foundations of such
a topology, whose necessity appears more and more clearly to me.
After some ten years, I would now say, with hindsight, that “general
topology” was developed (during the thirties and forties)by analysts and in
order to meet the needs of analysis, not for topology per se, i.e. the study
of the topological properties of the various geometrical shapes.
That the
foundations of topology are inadequate is manifest from the very beginning,
in the form of “false problems” (at least from the point of view of the topo-
logical intuition of shapes) such as the “invariance of domains”, even if the
solution to this problem by Brouwer led him to introduce new geometrical
ideas. Even now, just as in the heroic times when one anxiously witnessed


---

Sketch of a Programme
259
for the ﬁrst time curves cheerfully ﬁlling squares and cubes, when one tries
to do topological geometry in the technical context of topological spaces, one
is confronted at each step with spurious diﬃculties related to wild phenom-
ena. For instance, it is not really possible, except in very low dimensions,
to study for a given space X (say a compact manifold), the homotopy type
of (say) the automorphism group of X, or of the space of embeddings, or
immersions etc. of X into some other space Y – whereas one feels that these
invariants should be part of the toolbox of the essential invariants attached
to X, or to the pair (X, Y ), etc. just as the function space Hom(X, Y ) which
is familiar in homotopical algebra. Topologists elude the diﬃculty, without
tackling it, moving to contexts which are close to the topological one and
less subject to wildness, such as diﬀerentiable manifolds, PL spaces (piece-
wise linear) etc., of which it is clear that none is “good”, i.e. stable under
the most obvious topological operations, such as contraction-glueing opera-
29
30
tions (not to mention operations like X →Aut(X) which oblige one to leave
the paradise of ﬁnite dimensional “spaces”). This is a way of beating about
the bush! This situation, like so often already in the history of our science,
simply reveals the almost insurmountable inertia of the mind, burdened by
a heavy weight of conditioning, which makes it diﬃcult to take a real look
at a foundational question, thus at the context in which we live, breathe,
work – accepting it, rather, as immutable data. It is certainly this inertia
which explains why it tooks millenia before such childish ideas as that of
zero, of a group, of a topological shape found their place in mathematics.
It is this again which explains why the rigid framework of general topology
is patiently dragged along by generation after generation of topologists for
whom “wildness” is a fatal necessity, rooted in the nature of things.
My approach toward possible foundations for a tame topology has been
an axiomatic one. Rather than declaring (which would indeed be a perfectly
sensible thing to do) that the desired “tame spaces” are no other than (say)
Hironaka’s semianalytic spaces, and then developing in this context the
toolbox of constructions and notions which are familiar from topology, sup-
plemented with those which had not been developed up to now, for that very
reason, I preferred to work on extracting which exactly, among the geomet-
rical properties of the semianalytic sets in a space Rn, make it possible to
use these as local “models” for a notion of “tame space” (here semianalytic),
and what (hopefully!) makes this notion ﬂexible enough to use it eﬀectively
as the fundamental notion for a “tame topology” which would express with
ease the topological intuition of shapes. Thus, once this necessary founda-
tional work has been completed, there will appear not one “tame theory”,
but a vast inﬁnity, ranging from the strictest
of all, the one which deals
30
31
with “piecewise Qr-algebraic spaces” (with Qr = Q ∩R), to the one which


---

260
Alexandre Grothendieck
appears (whether rightly or not) to be likely to be the vastest of all, namely
using “piecewise real analytic spaces” (or semianalytic using Hironaka’s ter-
minology). Among the foundational theorems which I envision in my pro-
gramme, there is a comparison theorem which, to put it vaguely, would
say that one will essentially ﬁnd the same isotopic categories (or even ∞-
isotopic) whatever the tame theory one is working with. In a more precise
way, the question is to put one’s ﬁnger on a system of axioms which is rich
enough to imply (among many other things) that if one has two tame the-
ories T , T ′ with T ﬁner than T ′ (in the obvious sense), and if X, Y are
two T -tame spaces, which thus also deﬁne corresponding T ′-tame spaces,
the canonical map
IsomT (X, Y ) →IsomT ′(X, Y )
induces a bijection on the set of connected components (which will imply
that the isotopic category of the T -spaces is equivalent to the T ′-spaces),
and is even a homotopy equivalence (which means that one even has an
equivalence for the “∞-isotopic” categories, which are ﬁner than the iso-
topic categories in which one retains only the π0 of the spaces of isomor-
phisms). Here the Isom may be deﬁned in an obvious way, for instance as
semisimplicial sets, in order to give a precise meaning to the above state-
ment. Analogous statements should be true, if one replaces the “spaces”
Isom with other spaces of maps, subject to standard geometric conditions,
such as those of being embeddings, immersions, smooth, etale, ﬁbrations
etc. One also expects analogous statements where X, Y are replaced by
systems of tame spaces, such as those which occur in a theory of d´evissage
of stratiﬁed structures – so that in a precise technical sense, this d´evissage
theory will also be
essentially independent of the tame theory chosen to
31
32
express it.
The ﬁrst decisive test for a good system of axioms deﬁning the notion of
a “tame subset of Rn” seems to me to consist in the possibility of proving
such comparison theorems. I have settled for the time being for extracting
a temporary system of plausible axioms, without any assurance that other
axioms will not have to be added, which only working on speciﬁc examples
will cause to appear. The strongest among the axioms I have introduced,
whose validity is (or will be) most likely the most delicate to check in spe-
ciﬁc situations, is a triangulability axiom (in a tame sense, it goes without
saying) of a tame part of Rn. I did not try to prove the comparison theo-
rem in terms of these axioms only, however I had the impression (right or
wrong again!) that this proof, whether or not it necessitates the introduc-
tion of some additional axiom, will not present serious technical diﬃculties.
It may well be that the technical diﬃculties in the development of satis-
factory foundations for tame topology, including a theory of d´evissage for


---

Sketch of a Programme
261
tame stratiﬁed structures are actually already essentially concentrated in
the axioms, and consequently already essentially overcome by triangulabil-
ity theorems `a la Lojasiewicz and Hironaka. What is again lacking is not the
technical virtuosity of the mathematicians, which is sometimes impressive,
but the audacity (or simply innocence...) to free oneself from a familiar
context accepted by a ﬂawless consensus...
The advantages of an axiomatic approach towards the foundations of
tame topology seem to me to be obvious enough. Thus, in order to consider
a complex algebraic variety, or the set of real points of an algebraic vari-
ety deﬁned over R, as a tame space, it seems preferable to work with the
“piecewise R-algebraic” theory , maybe even the Qr-algebraic theory (with
Qr = Q ∩R) when dealing with varieties deﬁned over number ﬁelds, etc.
32
33
The introduction of a subﬁeld K ⊂R associated to the theory T (consisting
in the points of R which are T -tame, i.e. such that the corresponding one-
point set is T -tame) make it possible to introduce for any point x of a tame
space X, a residue ﬁeld k(x), which is an algebraically closed subextension
of R/K, of ﬁnite transcendence degree over K (bounded by the topological
dimension of X). When the transcendence degree of R over K is inﬁnite, we
ﬁnd a notion of transcendence degree (or “dimension”) of a point of a tame
space, close to the familiar notion in algebraic geometry. Such notions are
absent from the “semianalytic” tame topology, which however appears as
the natural topological context for the inclusion of real and complex analytic
spaces.
Among the ﬁrst theorems one expects in a framework of tame topology as
I perceive it, aside from the comparison theorems, are the statements which
establish, in a suitable sense, the existence and uniqueness of “the” tubular
neighbourhood of closed tame subspace in a tame space (say compact to
make things simpler), together with concrete ways of building it (starting
for instance from any tame map X →R+ having Y as its zero set), the
description of its “boundary” (although generally it is in no way a manifold
with boundary!) ∂T, which has in T a neighbourhood which is isomorphic to
the product of T with a segment, etc. Granted some suitable equisingularity
hypotheses, one expects that T will be endowed, in an essentially unique
way, with the structure of a locally trivial ﬁbration over Y , with ∂T as a
subﬁbration. This is one of the least clear points in my temporary intui-
tion of the situation, whereas the homotopy class of the predicted structure
map T →Y has an obvious meaning, independent of any equisingularity
hypothesis, as the homotopic inverse of the inclusion map Y →T, which
must be a homotopism. One way to a posteriori obtain such a structure
would be via the hypothetical equivalence of isotopic categories which was
considered at the beginning, taking into account the fact that the functor
33
34


---

262
Alexandre Grothendieck
(U, Y, f) 7−→(X, Y ) is well-deﬁned in an obvious way, independently of any
theory of tubular neighbourhoods.
It will perhaps be said, not without reason, that all this may be only
dreams, which will vanish in smoke as soon as one sets to work on spe-
ciﬁc examples, or even before, taking into account some known or obvious
facts which have escaped me. Indeed, only working out speciﬁc examples
will make it possible to sift the right from the wrong and to reach the true
substance. The only thing in all this which I have no doubt about, is the
very necessity of such a foundational work, in other words, the artiﬁciality
of the present foundations of topology, and the diﬃculties which they cause
at each step. It may be however that the formulation I give of a theory
of d´evissage of stratiﬁed structures in terms of an equivalence theorem of
suitable isotopic (or even ∞-isotopic) categories is actually too optimistic.
But I should add that I have no real doubts about the fact that the theory
of these d´evissages which I developed two years ago, although it remains
in part heuristic, does indeed express some very tangible reality. In some
part of my work, for want of a ready-to-use “tame” context, and in order
to have precise and provable statements, I was led to postulate some very
plausible additional structures on the stratiﬁed structure I started with, es-
pecially concerning the local retraction data, which do make it possible to
construct a canonical system of spaces, parametrised by the ordered set of
ﬂags Drap(I) of the ordered set I indexing the strata; these spaces play the
role of the spaces (U, Y ) above, and they are connected by embedding and
proper ﬁbration maps, which make it possible to reconstitute in an equally
canonical way the original stratiﬁed structure, including these “additional
structures” (7). The only trouble here, is that these appear as an additional
artiﬁcial element of structure, which is no way part of the data in the usual
geometric situations, as for example the compact moduli space c
Mg,ν with
34
35
its canonical “stratiﬁcation at inﬁnity”, deﬁned by the Mumford-Deligne di-
visor with normal crossings. Another, probably less serious diﬃculty, is that
this so-called moduli “space” is in fact a multiplicity – which can be tech-
nically expressed by the necessity of replacing the index set I for the strata
with an (essentially ﬁnite) category of indices, here the “MD graphs” which
“parametrise” the possible “combinatorial structures” of a stable curve of
type (g, ν). This said, I can assert that the general theory of d´evissage,
which has been developed especially to meet the needs of this example, has
indeed proved to be a precious guide, leading to a progressive understand-
ing, with ﬂawless coherence, of some essential aspects of the Teichm¨uller
tower (that is, essentially the “structure at inﬁnity” of the ordinary Te-
ichm¨uller groups). It is this approach which ﬁnally led me, within some
months, to the principle of a purely combinatorial construction of the tower


---

Sketch of a Programme
263
of Teichm¨uller groupoids, in the spirit sketched above (cf. par. 2).
Another satisfying test of coherence comes from the “topossic” viewpoint.
Indeed, as my interest for the multiplicities of moduli was ﬁrst prompted
by their algebrico-geometric and arithmetic meaning, I was ﬁrst and fore-
most interested by the modular algebraic multiplicities, over the absolute
baseﬁeld Q, and by a “d´evissage” at inﬁnity of their geometric fundamental
groups (i.e. of the proﬁnite Teichm¨uller groups) which would be compatible
with the natural operations of IΓ = Gal(Q/Q). This requirement seemed
to exclude from the start the possibility of a reference to a hypothetical
theory of d´evissage of stratiﬁed structures in a context of “tame topology”
(or even, at worst, of ordinary topology), beyond a purely heuristic guid-
ing thread. Thus the question arose of translating, in the context of the
topoi (here etale topoi)
which were present in the situation, the theory
35
36
of d´evissage I had arrived at in a completely diﬀerent context – with the
additional task, in the sequel, of extracting a general comparison theorem,
patterned after well-known theorems, in order to compare the invariants
(in particular the homotopy types of various tubular neighbourhoods) ob-
tained in the transcendent and schematic frameworks.
I have been able
to convince myself that such a formalism of d´evissage indeed had some
meaning in the (so-called “abstract”!) context of general topoi, or at least
noetherian topoi (like those occurring in this situation), via a suitable no-
tion of canonical tubular neighbourhood of a subtopos in an ambient topos.
Once this notion is acquired, together with some simple formal properties,
the description of the “d´evissage” of a stratiﬁed topos is even considerably
simpler in that framework than in the (tame) topological one. True, there
is foundational work to be done here too, especially around the very notion
of the tubular neighbourhood of a subtopos – and it is actually surprising
that this work (as far as I know) has still never been done, i.e. that no one
(since the context of etale topology appeared, more than twenty years ago)
apparently ever felt the need for it; surely a sign that the understanding of
the topological structure of schemes has not made much progress since the
work of Artin-Mazur...
Once I had accomplished this (more or less heuristic) double work of re-
ﬁning the notion of d´evissage of a stratiﬁed space or topos, which was a
crucial step in my understanding of the modular multiplicities, it actually
appeared that, as far as these are concerned, one can actually take a short
cut for at least a large part of the theory, via direct geometric arguments.
Nonetheless, the formalism of d´evissage which I reached has proved its use-
fulness and its coherence to me, independently of any question about the
most adequate foundations which make it completely meaningful.


---

264
Alexandre Grothendieck
6. One of the most interesting foundational theorems of (tame) topology
36
37
which should be developed would be a theorem of “d´evissage” (again!) of a
proper tame map of tame spaces
f : X →Y,
via a decreasing ﬁltration of Y by closed tame subspaces Y i, such that
above the “open strata” Y i\Y i−1 of this ﬁltration, f induces a locally trivial
ﬁbration (from the tame point of view, it goes without saying). It should be
possible to generalise such a statement even further and to make it precise
in various ways, in particular by requiring the existence of an analogous
simultaneous d´evissage for X and for a given ﬁnite family of (tame) closed
subspaces of X. Also the very notion of locally trivial ﬁbration in the tame
sense can be made considerably stronger, taking into account the fact that
the open strata Ui are better than spaces whose tame structure is purely
local, because they are obtained as diﬀerences of two tame spaces, compact
if Y is compact. Between the notion of a compact tame space (which is
realised as one of the starting “models” in an Rn) and that of a “locally
tame” (locally compact) space which can be deduced from it in a relatively
obvious way, there is a somewhat more delicate notion of a “globally tame”
space X, obtained as the diﬀerence ˆX\Y of two compact tame spaces, it
being understood that we do not distinguish between the space deﬁned by
a pair ( ˆX, Y ) and that deﬁned by a pair ( ˆX′, Y ′) deduced from it by a
(necessarily proper) tame map
g : ˆX′ →ˆX
inducing a bijection g−1(X) →X, taking Y ′ = g−1(Y ). Perhaps the most
interesting natural example is the one where we start from a separated
scheme of ﬁnite type over C or R, taking
for X the set of its real or
37
38
complex points, which inherits a global tame structure with the help of
schematic compactiﬁcations (which exist according to Nagata) of the scheme
we started with. This notion of a globally tame space is associated to a
notion of a globally tame map, which in turn allows us to strengthen the
notion of a locally trivial ﬁbration, in stating a theorem of d´evissage for a
map f : X →Y (now not necessarily proper) in the context of globally
tame spaces.
I was informed last summer by Zoghman Mebkhout that a theorem of
d´evissage in this spirit has been recently obtained in the context of real
and/or complex analytic spaces, with Y i which here are analytic subspaces
of Y . This result makes it plausible that we already have at our disposal
techniques which are powerful enough to also prove a d´evissage theorem in
the tame context, apparently more general, but probably less arduous.


---

Sketch of a Programme
265
The context of tame topology should also, it seems to me, make it pos-
sible to formulate with precision a certain very general principle which I
frequently use in a great variety of geometric situations, which I call the
“principle of anodine choices” – as useful as vague in appearance! It says
that when for the needs of some construction of a geometric object in terms
of others, we are led to make a certain number of arbitrary choices along the
way, so that the ﬁnal object appears to depend on these choices, and is thus
stained with a defect of canonicity, that this defect is indeed serious (and
to be removed requires a more careful analysis of the situation, the notions
used, the data introduced etc.) whenever at least one of these choices is
made in a space which is not “contractible”, i.e. whose π0 or one of whose
higher invariants πi is non-trivial, and that this defect is on the contrary
merely apparent, and the construction itself is “essentially” canonical and
will not bring along any troubles, whenever the choices made are all “an-
38
39
odine”, i.e. made in contractible spaces. When we try in actual examples
to really understand this principle, it seems that each time we stumble onto
the same notion of “∞-isotopic categories” expressing a given situation,
and ﬁner than the more naive isotopic (= 0-isotopic) categories obtained
by considering only the π0 of the spaces of isomorphisms introduced in the
situation, while the ∞-isotopic point of view considers all of their homotopy
type. For example, the naive isotopic point of view for compact surfaces
with boundary of type (g, ν) is “good” (without any hidden boomerangs!)
exactly in the cases which I call “anabelian” (and which Thurston calls
“hyperbolic”), i.e. distinct from (0, 0), (0, 1) (0, 2), (1, 0) – which are also
exactly the cases where the connected component of the identity of the au-
tomorphism group of the surface is contractible. In the other cases, except
for the case (0, 0) of the sphere without holes, it suﬃces to work with 1-
isotopic categories to express in a satisfying way via algebra the essential
geometrico-topological facts, since the said connected component is then a
K(π, 1). Working in a 1-isotopic category actually comes down to working
in a bicategory, i.e. with Hom(X, Y ) which are (no longer discrete sets as
in the 0-isotopic point of view, but) groupoids (whose π0 are exactly the
0-isotopic Hom). This is the description in purely algebraic terms of this
bicategory which is given in the last part of the thesis of Yves Ladegaillerie
(cf. par. 3).
If I allowed myself to dwell here at some length on the theme of the
foundations of tame topology, which is not one of those to which I intend to
devote myself prioritarily in the coming years, it is doubtless because I feel
that it is yet another cause which needs to be pleaded, or rather: a work of
great current importance which needs hands! Just as years ago for the new
foundations of algebraic geometry, it is not pleadings which will surmount
39
40


---

266
Alexandre Grothendieck
the inertia of acquired habits, but tenacious, meticulous long-term work,
which will from day to day bring eloquent harvests.
I would like to say some last words on an older reﬂection (end of the
sixties?), very close to the one I just discussed, inspired by ideas of Nash
which I found very striking. Instead of axiomatically deﬁning a notion of
“tame theory” via a notion of a “tame part of Rn” satisfying certain con-
ditions (mainly of stability), I was interested by an axiomatisation of the
notion of “non-singular variety” via, for each natural integer n, a subring
An of the ring of germs of real functions at the origin in Rn. These are
the functions which will be admitted to express the “change of chart” for
the corresponding notion of An-variety, and I was ﬁrst concerned with un-
covering a system of axioms on the system A = (An)n∈N which ensures
for this notion of variety a suppleness comparable to that of a C∞variety,
or a real analytic one (or a Nash one). According to the familiar type of
construction which one wants to be able to do in the context of A-varieties,
the relevant system of axioms is more or less reduced or rich. One doesn’t
need much if one only wants to develop the diﬀerential formalism, with
the construction of jet bundles, De Rham complexes etc.
If we want a
statement of the type “quasi-ﬁnite implies ﬁnite” (for a map in the neigh-
bourhood of a point), which appeared as a key statement in the local theory
of analytic spaces, we need a more delicate stability axiom, in Weierstrass’
“Vorbereitungssatz” (*).
In other questions, a stability axiom by analytic
40
41
continuation (in Cn) appears necessary. The most Draconian axiom which
I was led to introduce, also a stability axiom, concerns the integration of
Pfaﬀsystems, ensuring that certain (even all) Lie groups are A-varieties.
In all this, I took care not to suppose that the An are R-algebras, so a con-
stant function on a A-variety is “admissible” only if its value belongs to a
certain subﬁeld K of R (which is, if one likes, A0). This subﬁeld can very
well be Q, or its algebraic closure Qr in R, or any other subextension of
R/Q, preferably even of ﬁnite or at least countable transcendence degree
over Q. This makes it possible, for example, as before for tame spaces, to
have every point x of a variety (of type A) correspond to a residue ﬁeld
k(x), which is a subextension of R/K. A fact which appears important to
me here, is that even in its strongest form, the system of axioms does not
imply that we must have K = R. More precisely, because all the axioms are
stability axioms, it follows that for a given set S of germs of real analytic
functions at the origin (in various spaces Rn), there exists a smaller theory
(*) It could seem simpler to say that the (local) rings An are Henselian, which
is equivalent. But it is not at all clear a priori in this latter form that the
condition in question is in the nature of a stability condition, and this is an
important circumstance as will appear in the following reﬂections.


---

Sketch of a Programme
267
A for which these germs are admissible, and that it is “countable”, i.e. the
An are countable, whenever S is. A fortiori, K is then countable, i.e. of
countable transcendence degree over Q.
The idea here is to introduce, via this axiomatic system, a notion of an
“elementary” (real analytic) function, or rather, a whole hierarchy of such
notions.
For a function of 0 variables i.e.
a constant, this notion gives
that of an “elementary constant”, including in particular (in the case of the
strongest axiomatic system) constants such as π, e and many others, taking
values of admissible functions (such as exponentials, logarithms etc.) for
systems of “admissible” values of the argument. One feels that the relation
between the system A = (An)n∈N and the corresponding rationality ﬁeld
K
must be very tight, at least for A which can be generated by a ﬁnite
41
42
“system of generators” S – but one must fear that even the least of the
interesting questions one could ask about this situation still remains out of
reach (1).
These old reﬂections have taken on some current interest for me due to
my more recent reﬂection on tame theories. Indeed, it seems to me that
it is possible to associate in a natural way to a “diﬀerentiable theory” A
a tame theory T (doubtless having the same ﬁeld of constants), in such a
way that every A-variety is automatically equipped with a T -tame struc-
ture and conversely for every T -tame compact space X, we can ﬁnd a rare
tame closed subset Y in X, such that X\Y comes from an A-variety, and
moreover such that this A-variety structure is unique at least in the follow-
ing sense: two such structures coincide in the complement of a rare tame
subset Y ′ ⊃Y of X. The theory of d´evissage of stratiﬁed tame structures
(which was discussed in the preceding par.), in the case of smooth strata,
should moreover raise much more precise questions of comparison of tame
structures with structures of diﬀerentiable (or rather, R-analytic) type. I
suspect that the type of axiomatisation proposed here for the notion of “dif-
ferentiable theory” would give a natural framework for the formulation of
such questions with all desirable precision and generality.
7. Since the month of March last year, so nearly a year ago, the greater part
of my energy has been devoted to a work of reﬂection on the foundations of
non-commutative (co)homological algebra, or what is the same, after all, of
homotopic algebra. These reﬂections have taken the concrete form of a vo-
luminous stack of typed notes, destined to form the ﬁrst volume (now being
ﬁnished) of a work in two volumes to be published by Hermann, under the
42
43
overall title “Pursuing Stacks”. I now foresee (after successive extensions
of the initial project) that the manuscript of the whole of the two volumes,
which I hope to ﬁnish deﬁnitively in the course of this year, will be about


---

268
Alexandre Grothendieck
1500 typed pages in length. These two volumes are moreover for me the
ﬁrst in a vaster series, under the overall title “Mathematical Reﬂections”,
in which I intend to develop some of the themes sketched in the present
report.
Since I am speaking here of work which is actually now being written
up and is even almost ﬁnished, the ﬁrst volume of which will doubtless
appear this year and will contain a detailed introduction, it is undoubtedly
less interesting for me to develop this theme of reﬂection here, and I will
content myself with speaking of it only very brieﬂy. This work seems to me
to be somewhat marginal with respect to the themes I sketched before, and
does not (it seems to me) represent a real renewal of viewpoint or approach
with respect to my interests and my mathematical vision of before 1970. If I
suddenly resolved to do it, it is almost out of desperation, for nearly twenty
years have gone by since certain visibly fundamental questions, which were
ripe to be thoroughly investigated, without anyone seeing them or taking
the trouble to fathom them. Still today, the basic structures which occur
in the homotopic point of view in topology are not understood, and to
my knowledge, after the work of Verdier, Giraud and Illusie on this theme
(which are so many beginnings still waiting for continuations...) there has
been no eﬀort in this direction. I should probably make an exception for
the axiomatisation work done by Quillen on the notion of a category of
models, at the end of the sixties, and taken up in various forms by various
authors. At that time, and still now, this work seduced me and taught me
a great deal, even while going in quite a diﬀerent direction from the one
43
44
which was and still is close to my heart. Certainly, it introduces derived
categories in various non-commutative contexts, but without entering into
the question of the essential internal structures of such a category, also
left open in the commutative case by Verdier, and after him by Illusie.
Similarly, the question of putting one’s ﬁnger on the natural “coeﬃcients”
for a non-commutative cohomological formalism, beyond the stacks (which
should be called 1-stacks) studied in the book by Giraud, remained open
– or rather, the rich and precise intuitions concerning it, taken from the
numerous examples coming in particular from algebraic geometry, are still
waiting for a precise and supple language to give them form.
I returned to certain aspects of these foundational questions in 1975, on
the occasion (I seem to remember) of a correspondence with Larry Breen
(two letters from this correspondence will be reproduced as an appendix to
Chap. I of volume 1, “History of Models”, of Pursuing Stacks). At that
moment the intuition appeared that ∞-groupoids should constitute partic-
ularly adequate models for homotopy types, the n-groupoids corresponding
to truncated homotopy types (with πi = 0 pour i > n). This same intu-


---

Sketch of a Programme
269
ition, via very diﬀerent routes, was discovered by Ronnie Brown and some of
his students in Bangor, but using a rather restrictive notion of ∞-groupoid
(which, among the 1-connected homotopy types, model only products of
Eilenberg-Mac Lane spaces). Stimulated by a rather haphazard correspon-
dence with Ronnie Brown, I ﬁnally began this reﬂection, starting with an
attempt to deﬁne a wider notion of ∞-groupoid (later rebaptised stack in
∞-groupoids or simply “stack”, the implication being: over the 1-point
topos), and which, from one thing to another, led me to Pursuing Stacks.
The volume “History of Models” is actually a completely unintended digres-
sion with respect to the initial project (the famous stacks being temporarily
forgotten, and supposed to reappear only around page 1000...).
44
45
This work is not completely isolated with respect to my more recent
interests. For example, my reﬂection on the modular multiplicities c
Mg,ν
and their stratiﬁed structure renewed the reﬂection on a theorem of van
Kampen in dimension > 1 (also one of the preferred themes of the group
in Bangor), and perhaps also contributed to preparing the ground for the
more important work of the following year. This also links up from time
to time with a reﬂection dating from the same year 1975 (or the following
year) on a “De Rham complex with divided powers”, which was the subject
of my last public lecture, at the IHES in 1976; I lent the manuscript of
it to I don’t remember whom after the talk, and it is now lost. It was at
the moment of this reﬂection that the intuition of a “schematisation” of
homotopy types germinated, and seven years later I am trying to make it
precise in a (particularly hypothetical) chapter of the History of Models.
The work of reﬂection undertaken in Pursuing Stacks is a little like a debt
which I am paying towards a scientiﬁc past where, for about ﬁfteen years
(from 1955 to 1970), the development of cohomological tools was the con-
stant Leitmotiv in my foundational work on algebraic geometry. If in this
renewal of my interest in this theme, it has taken on unexpected dimensions,
it is however not out of pity for a past, but because of the numerous un-
expected phenomena which ceaselessly appear and unceremoniously shatter
the previously laid plans and projects – rather like in the thousand and one
nights, where one awaits with bated breath through twenty other tales the
ﬁnal end of the ﬁrst.
8. Up to now I have spoken very little of the more down-to-earth reﬂections
on two-dimensional topological geometry, directly associated to my activ-
ities of teaching and “directing research”. Several times, I saw
opening
45
46
before me vast and rich ﬁelds ripe for the harvest, without ever succeeding
in communicating this vision, and the spark which accompanies it, to one
of my students, and having it open out into a more or less long-term com-


---

270
Alexandre Grothendieck
mon exploration. Each time up through today, after a few days or weeks of
investigating where I, as scout, discovered riches at ﬁrst unsuspected, the
voyage suddenly stopped, upon its becoming clear that I would be pursu-
ing it alone. Stronger interests then took precedence over a voyage which
at that point appeared more as a digression or even a dispersion, than a
common adventure.
One of these themes was that of planar polygons, centred around the
modular varieties which can be associated to them. One of the surprises
here was the irruption of algebraic geometry in a context which had seemed
to me quite distant. This kind of surprise, linked to the omnipresence of
algebraic geometry in plain geometry, occurred several times.
Another theme was that of curves (in particular circles) immersed in a
surface, with particular attention devoted to the “stable” case where the sin-
gular points are ordinary double points (and also the more general theme
where the diﬀerent branches at a point mutually cross), often with the addi-
tional hypothesis that the immersion is “cellular”, i.e. gives rise to a map.
A variation on the situations of this type is that of immersions of a sur-
face with non-empty boundary, and ﬁrst of all a disk (which was pointed
out to me by A’Campo around ten years ago).
Beyond the question of
the various combinatorial formulations of such situations, which really rep-
resent no more than an exercise of syntax, I was mainly interested in a
dynamical vision of the possible conﬁgurations, with the passage from one
to another via continuous deformations, which can be decomposed into com-
positions of two types of elementary operations and their inverses, namely
the “sweeping” of a branch of a curve over a double point, and the erasing
or the creation of a bigon. (The ﬁrst of these operations also plays a key
46
47
role in the “dynamical” theory of systems of pseudo-lines in a real projective
plane.) One of the ﬁrst questions to be asked here is that of determining
the diﬀerent classes of immersions of a circle or a disk (say) modulo these
elementary operations; another, that of seeing which are the immersions of
the boundary of the disk which come from an immersion of the disk, and
to what extent the ﬁrst determine the second. Here also, it seems to me
that it is a systematic study of the relevant modular varieties (of inﬁnite
dimension here, unless a purely combinatorial description of them can be
given) which should give the most eﬃcient “focus”, forcing us in some sense
to ask ourselves the most relevant questions. Unfortunately, the reﬂection
on even the most obvious and down-to-earth questions has remained in an
embryonic state. As the only tangible result, I can cite a theory of canonical
“d´evissage” of a stable cellular immersion of a circle in a surface into “unde-
composable” immersions, by “telescoping” such immersions. Unfortunately
I did not succeed in transforming my lights on the question into a DEA


---

Sketch of a Programme
271
thesis, nor other lights (on a complete theoretical description, in terms of
fundamental groups of topological 1-complexes, of the immersions of a sur-
face with boundary which extend a given immersion of its boundary) into
the beginnings of a doctoral thesis...
A third theme, pursued simultaneously over the last three years at dif-
ferent levels of teaching (from the option for ﬁrst year students to the
three third-cycle theses now being written on this theme) deals with the
topologico-combinatorial classiﬁcation of systems of lines or pseudo-lines.
Altogether, the participation of my students here has been less disappoint-
ing than elsewhere, and I have had the pleasure of occasionally learning
interesting things from them which I would not have thought of. Things
being what they are, however, our common
reﬂection was limited to a
47
48
very elementary level. Lately, I ﬁnally devoted a month of intensive reﬂec-
tion to the development of a purely combinatorial construction of a sort of
“modular surface” associated to a system of n pseudo-lines, which classiﬁes
the diﬀerent possible “relative positions” (stable or not) of an (n + 1)-st
pseudo-line with respect to the given system, in other words: the diﬀerent
possible “aﬃnisations” of this system, by the diﬀerent possible choices of a
“pseudo-line at inﬁnity”. I have the impression of having put my ﬁnger on
a remarkable object, causing an unexpected order to appear in questions
of classiﬁcation which up to now appeared fairly chaotic! But the present
report is not the place to dwell further on this subject.
Since 1977, in all the questions (such as the two last themes evoked above)
where two-dimensional maps occur, the possibility of realising them canoni-
cally on a conformal surface, so on a complex algebraic curve in the compact
oriented case, remains constantly in ﬁligree throughout my reﬂection. In
practically every case (in fact, in all cases except that of certain spherical
maps with “few automorphisms”) such a conformal realisation implies in
fact a canonical Riemannian metric, or at least, canonical up to a multi-
plicative constant. These new elements of structure (without even taking
into account the arithmetic element which was considered in par. 3) are of
a nature to deeply transform the initial aspect of the questions considered,
and the methods of approaching them. A beginning of familiarisation with
the beautiful ideas of Thurston on the construction of Teichm¨uller space,
in terms of a very simple game of hyperbolic Riemannian surgery, conﬁrms
me in this presentiment. Unfortunately, the very modest level of culture
of almost all the students who have worked with me over these last ten
years does not allow me to investigate these possibilities with them even by
allusion, since the assimilation of even a minimal combinatorial language al-
ready frequently encounters considerable psychical obstacles. This is why,
48
49
in some respect and more and more in these last years, my teaching activity


---

272
Alexandre Grothendieck
has often acted like a weight, rather than a stimulus for the unfolding of a
somewhat advanced or even merely delicate geometric reﬂection.
9. The occasion appears to be auspicious for a brief assessment of my teach-
ing activity since 1970, that is, since it has taken place in a university. This
contact with a very diﬀerent reality taught me many things, of a completely
diﬀerent order than simply pedagogic or scientiﬁc. Here is not the place to
dwell on this subject. I also mentioned at the beginning of this report the
role which this change of professional milieu played in the renewal of my
approach to mathematics, and that of my centres of interest in mathemat-
ics. If I pursue this assessment of my teaching activity on the research level,
I come to the conclusion of a clear and solid failure. In the more than ten
years that this activity has taken place, year after year in the same univer-
sity, I was never at any moment able to suscitate a place where “something
happened” – where something “passed”, even among the smallest group of
people, linked together by a common adventure. Twice, it is true, around
the years 1974 to 1976, I had the pleasure and the privilege of awakening
a student to a work of some consequence, pursued with enthusiasm: Yves
Ladegaillerie in the work mentioned earlier (par. 3) on questions of isotopy
in dimension 2, and Carlos Contou-Carr`ere (whose mathematical passion
did not await a meeting with myself to blossom) an unpublished work on
the local and global Jacobians over general base schemes (of which one part
was announced in a note in the CR). Apart from these two cases, my role
has been limited throughout these ten years to somehow or other conveying
the rudiments of the mathematician’s trade to about twenty students on
the research level,
or at least to those among them who persevered with
49
50
me, reputed to be more demanding than others, long enough to arrive at a
ﬁrst acceptable work written black on white (and even, sometimes, at some-
thing better than acceptable and more than just one, done with pleasure
and worked out through to the end). Given the circumstances, among the
rare people who persevered, even rarer are those who will have the chance
of carrying on the trade, and thus, while earning their bread, learning it
ever more deeply.
10. Since last year, I feel that as regards my teaching activity at the uni-
versity, I have learned everything I have to learn and taught everything I
can teach there, and that it has ceased to be really useful, to myself and to
others. To insist on continuing it under these circumstances would appear
to me to be a waste both of human resources and of public funds. This
is why I have applied for a position in the CNRS (which I left in 1959 as
freshly named director of research, to enter the IHES). I know moreover


---

Sketch of a Programme
273
that the employment situation is tight in the CNRS as everywhere else,
that the result of my request is doubtful, and that if a position were to be
attributed to me, it would be at the expense of a younger researcher who
would remain without a position. But it is also true that it would free my
position at the USTL to the beneﬁt of someone else. This is why I do not
scruple to make this request, and to renew it if is not accepted this year.
In any case, this application will have been the occasion for me to write
this sketch of a programme, which otherwise would probably never have
seen the light of day. I have tried to be brief without being sybilline and
also, afterwards, to make it easier reading by the addition of a summary. If
in spite of this it still appears rather long for the circumstances, I beg to
be excused. It seems short to me for its content, knowing that ten years
of work would not be too much to explore even the least
of the themes
50
51
sketched here through to the end (assuming that there is an “end”...), and
one hundred years would be little for the richest among them!
Behind the apparent disparity of the themes evoked here, an attentive
reader will perceive as I do a profound unity. This manifests itself particu-
larly by a common source of inspiration, namely the geometry of surfaces,
present in all of these themes, and most often front and centre. This source,
with respect to my mathematical “past”, represents a renewal, but certainly
not a rupture. Rather, it indicates the path to a new approach to the still
mysterious reality of “motives”, which fascinated me more than any other
in the last years of this past (*). This fascination has certainly not vanished,
rather it is a part of the fascination with the most burning of all the themes
evoked above. But today I am no longer, as I used to be, the voluntary
prisoner of interminable tasks, which so often prevented me from springing
into the unknown, mathematical or not. The time of tasks is over for me.
If age has brought me something, it is lightness.
Janvier 1984
(*) On this subject, see my commentaries in the “Thematic Sketch” of 1972
attached to the present report, in the last section “motivic digressions”,
(loc. cit. pages 17-18).


---

274
Alexandre Grothendieck
(1) The expression
“out of reach” here (and also later for a completely
51
52
diﬀerent question), appears to me to be decidedly hasty and unfounded.
I have noted myself on other occasions that when oracles (here myself!)
declare with an air of deep understanding (or doubt) that such and such a
problem is “out of reach”, it is actually an entirely subjective aﬃrmation. It
simply means, apart from the fact that the problem is supposed to be not yet
solved, that the person speaking has no ideas on the question, or probably
more precisely, that he has no feelings and no motivation with regard to it,
that it “does nothing to him” and that he has no desire to do anything with
it – which is frequently a suﬃcient reason to want to discourage others. As in
the remark of M. de la Palisse, this did not stop the beautiful and regretted
conjectures of Mordell, Tate, and Shafarevitch from succumbing although
they were all reputed to be “out of reach”, poor things ! – Besides, in the
very days which followed the writing up of the present report, which put me
into contact with questions from which I had distanced myself during the
last year, I noticed a new and remarkable property of the outer action of
an absolute Galois group on the fundamental group of an algebraic curve,
which had escaped me until now and which undoubtedly constitutes at
least a new step towards the formulation of an algebraic characterisation of
Gal(Q/Q). This, with the “fundamental conjecture” (mentioned in par. 3
below) appears at present as the principal open question for the foundation
of an “anabelian algebraic geometry”, which starting a few years ago, has
represented (by far) my strongest centre of interest in mathematics.
(2) With the exception of another “fact”, at the time when, around the
age of twelve, I was interned in the concentration camp of Rieucros (near
Mende). It is there that I learnt, from another prisoner, Maria, who gave
me free private lessons,
the deﬁnition of the circle. It impressed me by
52
53
its simplicity and its evidence, whereas the property of “perfect rotundity”
of the circle previously had appeared to me as a reality mysterious beyond
words. It is at that moment, I believe, that I glimpsed for the ﬁrst time
(without of course formulating it to myself in these terms) the creative power
of a “good” mathematical deﬁnition, of a formulation which describes the
essence. Still today, it seems that the fascination which this power exercised
on me has lost nothing of its force.
(3) More generally, beyond the so-called “anabelian” varieties, over ﬁelds
of ﬁnite type, anabelian algebraic geometry (as it revealed itself some years
ago) leads to a description, uniquely in terms of proﬁnite groups, of the cate-
gory of schemes of ﬁnite type over the absolute base Q (or even Z), and from
there, in principle, of the category of all schemes (by suitable passages to
limits). It is thus a construction which “pretends” to ignore the rings (such


---

Sketch of a Programme
275
as Q, algebras of ﬁnite type over Q, etc.) and the algebraic equations which
traditionally serve to describe schemes, while working directly with their
etale topoi, which can be expressed in terms of systems of proﬁnite groups.
A grain of salt nevertheless: to be able to hope to reconstitute a scheme (of
ﬁnite type over Q say) from its etale topos, which is a purely topological
invariant, we must place ourselves not in the category of schemes (here of
ﬁnite type over Q), but in the one which is deduced from it by “localisa-
tion”, by making the morphisms which are “universal homeomorphisms”,
i.e. ﬁnite, radicial and surjective, be invertible. The development of such a
translation of a “geometric world” (namely that of schemes, schematic mul-
tiplicities etc.) in terms of an “algebraic world” (that of proﬁnite groups and
systems of proﬁnite groups describing suitable topoi (called “etale”) can be
considered as the ultimate goal of Galois theory, doubtless even in the very
53
54
spirit of Galois. The sempiternal question “and why all this?” seems to me
to have neither more nor less meaning in the case of the anabelian geometry
now in the process of birth, than in the case of Galois theory in the time
of Galois (or even today, when the question is asked by an overwhelmed
student...); the same goes for the commentary which usually accompanies
it, namely “all this is very general indeed!”.
(4) We thus easily conceive that a group like Sl(2, Z), with its “arithmetic”
structure, is positively a machine for constructing “motivic” representations
of Gal(Q/Q) and its open subgroups, and that we thus obtain, at least in
principle, all the motivic representations which are of weight 1, or contained
in a tensor product of such representations (which already makes quite a
packet!) In 1981 I began to experiment with this machine in a few speciﬁc
cases, obtaining various remarkable representations of IΓ in groups G(ˆZ),
where G is a (not necessarily reductive) group scheme over Z, starting from
suitable homomorphisms
Sl(2, Z) →G0(Z),
where G0 is a group scheme over Z, and G is constructed as an extension
of G0 by a suitable group scheme. In the “tautological” case G0 = Sl(2)Z,
we ﬁnd for G a remarkable extension of Gl(2)Z by a torus of dimension 2,
with a motivic representation which “covers” those associated to the class
ﬁelds of the extensions Q(i) and Q(j) (as if by chance, the “ﬁelds of complex
multiplication” of the two “anharmonic” elliptic curves). There is here a
principle of construction which seemed to me very general and very eﬃcient,
but I didn’t have (or take) the leisure to unravel it and follow it through
to the end – this is one of the numerous “hot points” in the foundational
programme of anabelian algebraic geometry (or “Galois theory”, extended


---

276
Alexandre Grothendieck
version) which I propose to develop. At this time, and in an order of priority
which is probably very temporary, these points are:
54
55
a) Combinatorial construction of the Teichm¨uller tower.
b) Description of the automorphism group of the proﬁnite compactiﬁca-
tion of this tower, and reﬂection on a characterisation of IΓ = Gal(Q/Q) as
a subgroup of the latter.
c) The “motive machine” Sl(2, Z) and its variations.
d) The anabelian dictionary, and the fundamental conjecture (which is
perhaps not so “out of reach” as all that!). Among the crucial points of
this dictionary, I foresee the “proﬁnite paradigm” for the ﬁelds Q (cf. b)),
R and C, for which a plausible formalism remains to be uncovered, as well
as a description of the inertia subgroups of IΓ, via which the passage from
characteristic zero to characteristic p > 0 begins, and to the absolute ring
Z.
e) Fermat’s problem.
(5) I would like to point out, however, a more delicate task (apart from the
task pointed out in passing on cubic complexes), on the combinatorial in-
terpretation of regular maps associated to congruence subgroups of Sl(2, Z).
This work was developed with a view to expressing the “arithmetic” oper-
ation of IΓ = Gal(Q/Q) on these “congruence maps”, which is essentially
done via the intermediary of the cyclotomic character of IΓ.
A point of
departure was the combinatorial theory of the “bi-icosahedron” developed
in a C4 course starting from purely geometric motivations, and which (it
afterwards proved) gives rise to a very convenient expression for the action
of IΓ on the category of icosahedral maps (i.e. congruence maps of index 5).
(6) Let us note in relation to this that the isomorphism classes of com-
pact tame spaces are the same as in the “piecewise linear” theory (which
is not, I recall, a tame theory). This is in some sense a rehabilitation of
the “Hauptvermutung”, which is “false” only because for historical reasons
which it would undoubtedly be interesting to determine more precisely,
55
56
the foundations of topology used to formulate it did not exclude wild phe-
nomena. It need (I hope) not be said that the necessity of developing new
foundations for “geometric” topology does not at all exclude the fact that
the phenomena in question, like everything else under the sun, have their
own reason for being and their own beauty. More adequate foundations
would not suppress these phenomena, but would allow us to situate them
in a suitable place, like “limiting cases” of phenomena of “true” topology.


---

Sketch of a Programme
277
(7) In fact, to reconstruct the system of spaces
(i0, . . . , in) 7→Xi0,...,in
contravariant on Drap(I) (for the inclusion of ﬂags), it suﬃces to know
the Xi (or “unfolded strata”) and the Xij (or “joining tubes”) for i, j ∈I,
i < j, and the morphisms Xij →Xj (which are “bounding” inclusions)
and Xij →Xi (which are proper ﬁbrations, whose ﬁbres Fij are called
“joining ﬁbres” for the strata of index i and j). In the case of a tame multi-
plicity, however, we must also know the “junction spaces” Xijk (i < j < k)
and their morphisms in Xij, Xjk and above all Xi,k, included in the fol-
lowing hexagonal commutative diagram, where the two squares on the right
are Cartesian, the arrows ,→are immersions (not necessarily embeddings
here), and the other arrows are proper ﬁbrations:
56
57
Xik
⊂
> Xk
	
      I
@@@
@@@
I
@@@
@@@
Xi
Xijk
⊂
> Xjk
I
@@@
@@@
	
      	
      Xij
⊂
> Xj
(N.B. This diagram deﬁnes Xijk in terms of Xij and Xjk over Xj, but not
the arrow Xijk →Xik, since Xik →Xk is not necessarily an embedding.)
In the case of actual stratiﬁed tame spaces (which are not, strictly speak-
ing, multiplicities) we can conveniently express the unfolding of this struc-
ture, i.e. the system of spaces Xi0,...,in in terms of the tame space X∗sum
of the Xi, which is equipped with a structure of an ordered object (in the
category of tame spaces) having as graph X∗∗of the order relation the
sum of the Xij and the Xi (the latter being on the diagonal). Among the
essential properties of this ordered structure, let us only note here that
pr1 : X∗∗→X∗is a (locally trivial) proper ﬁbration, and pr2 : X∗∗→X∗
is a “bounding” embedding. We have an analogous interpretation of the
unfolding of a stratiﬁed tame multiplicity, in terms of a category structure
(replacing a simple ordered structure) “in the sense of tame multiplicities”,
such that the composition map is given by the morphisms Xijk →Xik
above.


---
