---
type: manuscript
title: "La Longue Marche à travers la théorie de Galois"
author: "Alexander Grothendieck"
date: "2024"
language: en
tags: ["wet-math", "category-theory", "cellular-automata"]
source: "longue-marche"
word_count: 41661
l0: "Abstract not available."
relations:
  cites: []
  cited_by: []
  related: []
---

<!-- L1: Overview (~2k tokens) -->
## Overview

# L1-Summary: Homomorphismes de M0,3, les groupes Mρ,σ généraux

**Titre**: 49. Homomorphismes de M0,3, les groupes Mρ,σ généraux
**Auteur**: Alexander Grothendieck
**Date**: 11 mars 2005
**Contexte**: Ce texte est la section 49 d'un manuscrit de recherche plus vaste, probablement lié à "La Longue Marche à travers la Théorie de Galois". Le style est exploratoire, l'auteur construisant et affinant un formalisme complexe. Les notes de bas de page et les remarques de l'auteur, comme le qualitatif de "tâtonnement", indiquent une pensée en cours d'élaboration.

### Résumé

Ce document développe une construction axiomatique et fonctorielle d'une famille de groupes profinis, notés $M_{\rho,\sigma}$, associés à un groupe profini $S$ engendré par deux éléments $\rho$ et $\sigma$. La construction est motivée par l'étude des homomorphismes du groupe de Grothendieck-Teichmüller $M_{0,3}^{\sim}$. Le groupe $M_{\rho,\sigma}$ est assemblé comme un produit fibré (fiber product) de groupes plus simples (centralisateurs, normalisateurs) au-dessus d'un groupe quotient commun $\Upsilon_{\rho,\sigma}$. La structure est entièrement déterminée par des relations sur les commutateurs (commutators) des générateurs. Le cas "universel", où $S$ est une extension de $S_{0,3}^{\wedge}$ liée à $GL(2, \hat{\mathbb{Z}})$, permet d'identifier ces groupes abstraits à des variantes du groupe de Grothendieck-Teichmüller, établissant un pont entre cette construction algébrique et la géométrie anabélienne.

### Structure du Texte

Le texte est divisé en six sections principales, montrant une progression de l'exploration initiale vers une théorie générale et raffinée.

*   **Section I**: Exploration préliminaire et mise en place du problème des homomorphismes d'un sous-groupe de $M_{0,3}^{\sim}$. L'auteur la qualifie de "tâtonnement".
*   **Section II**: Définition axiomatique des groupes $B_{\rho, \sigma}$ et $G_{\rho, \sigma}$ à partir d'un groupe profini $S$ et de deux générateurs $\rho, \sigma$. Cette section pose l' "hypothèse fondamentale" qui est au cœur de la construction.
*   **Section III**: Étude d'un cas particulier motivant : l'extension $N_{1,1}^{\sim}$ de $M_{0,3}^{\sim}$ par $\{\pm 1\}$, liée à $GL(2, \hat{\mathbb{Z}})$.
*   **Section IV**: Généralisation de la construction à des groupes $S$ de type $SL(2, \mathbb{Z})^{\wedge}$ (où $\rho^6 = \sigma^4 = 1, \rho^3 = \sigma^2$) et introduction d'un automorphisme externe $\tau$.
*   **Section V**: Construction systématique et fonctorielle des groupes $Z_{\rho, \sigma}$, $G_{\rho, \sigma}$, $M_{\rho, \sigma}$ et $\Gamma_{\rho, \sigma}$ par produits fibrés au-dessus d'un groupe de base commun $\Upsilon_{\rho, \sigma}$.
*   **Section VI**: Récapitulation, raffinement des constructions en les relativisant à un sous-groupe invariant $S^{\natural}$, et application détaillée au cas universel $S = GL(2, \mathbb{Z})^{\wedge}$.

### Thèse Principale et Idées Clés

La thèse centrale est la construction d'une machine algébrique, les groupes $M_{\rho, \sigma}$, qui généralise la structure du groupe de Grothendieck-Teichmüller.

1.  **Construction par Commutateurs**: La structure est entièrement encodée par le comportement des commutateurs. L' "hypothèse fondamentale" (II, (10)) postule une bijection entre un groupe d'automorphismes $B_{\rho, \sigma}$ et un ensemble de paires de commutateurs $\Sigma_{\rho, \sigma} = \{([u, \rho], [u, \sigma]) \mid u \in B_{\rho, \sigma}\}$. Ceci permet de transporter la structure de groupe de $B_{\rho, \sigma}$ à $\Sigma_{\rho, \sigma}$.
2.  **Structure de Produit Fibré**: Le groupe principal $M_{\rho, \sigma}$ est construit comme un produit fibré $N_\rho \times_{\Upsilon_{\rho, \sigma}} N_\sigma \times_{\Upsilon_{\rho, \sigma}} G_{\rho, \sigma}$. Cette architecture, rappelant celle des groupes de Teichmüller, assure la cohérence des actions sur les générateurs $\rho$ et $\sigma$. Le groupe $\Upsilon_{\rho, \sigma}$ joue le rôle d'un "groupe de Galois externe" ou d'un groupe de composantes connexes.
3.  **Fonctorialité**: La construction est fonctorielle. Un homomorphisme surjectif $\phi: S \to S'$ induit un homomorphisme $\phi_M: M_{\rho, \sigma} \to M_{\phi(\rho), \phi(\sigma)}$, sous certaines conditions de "prolongeabilité".
4.  **Cas Universel**: Le cas où $S = GL(2, \mathbb{Z})^{\wedge}$ est universel. Les groupes abstraits $M_{\rho, \sigma}$, $G_{\rho, \sigma}$, etc., s'identifient alors à des objets connus : $M \cong N_{1,1}^{\sim}$ (une extension centrale de $M_{0,3}^{\sim}$), $\Upsilon_{\rho, \sigma} \cong \Gamma_{0,3}^{\sim}$, et les sous-groupes de section $M(\rho)$, $M(\sigma)$ correspondent à des points spéciaux (comme $-\jmath$, $1/2$) sur l'espace de modules $M_{0,3}$.

### Objets Mathématiques Clés

*   $S$: Un groupe profini (profinite group), typiquement un quotient de $S_{0,3}^{\wedge}$ ou $GL(2, \mathbb{Z})^{\wedge}$.
*   $\rho, \sigma$: Deux générateurs topologiques de $S$.
*   $L_0, L_1$: Sous-groupes engendrés par $\varepsilon_0 = \sigma^{-1}\rho$ et $\varepsilon_1 = \rho\sigma^{-1}$.
*   $B_{\rho, \sigma}$: Groupe d'automorphismes de $S$ qui normalise $L_0$ et préserve les classes de conjugaison de $\rho$ et $\sigma$.
*   $\Sigma_{\rho, \sigma}$: Ensemble des paires de commutateurs $([u, \rho], [u, \sigma])$ pour $u \in B_{\rho, \sigma}$, satisfaisant la "relation des lacets" (loop relation) $\xi = \eta \varepsilon_1^\nu$.
*   $G_{\rho, \sigma}$: Extension de $\Upsilon_{\rho, \sigma}$ par $S$, construite à partir de $B_{\rho, \sigma}$ et $S$.
*   $Z_\rho, Z_\sigma$: Centralisateurs (centralizers) de $\rho$ et $\sigma$ dans $G_{\rho, \sigma}$.
*   $N_\rho, N_\sigma$: Normalisateurs (normalizers) des sous-groupes $\langle\rho\rangle$ et $\langle\sigma\rangle$ dans $G_{\rho, \sigma}$.
*   $\Upsilon_{\rho, \sigma}$: Le groupe quotient (quotient group) $G_{\rho, \sigma} / S$, base des produits fibrés.
*   $M_{\rho, \sigma}, \Gamma_{\rho, \sigma}$: Les objets principaux, définis comme produits fibrés de $N_\rho, N_\sigma, G_{\rho, \sigma}$ (ou $Z_{\rho, \sigma}$) au-dessus de $\Upsilon_{\rho, \sigma}$.

### Pertinence et Connexions

*   **Théorie des Catégories Supérieures, $\infty$-Groupoïdes, Types d'Homotopie**: Le groupe $M_{0,3}$ est le $\pi_1$ de l'espace de modules des sphères à 3 points. La construction de Grothendieck fournit un modèle algébrique pour ce type d'homotopie. Le formalisme des $M_{\rho, \sigma}$ peut être vu comme une tentative de capturer algébriquement la structure d'objets homotopiques (types d'homotopie 1) de manière fonctorielle, une idée centrale dans la poursuite des "types d'homotopie anabéliens" et des $\infty$-groupoïdes.
*   **Non-commutativité et Commutateurs**: La non-commutativité est au cœur du sujet. Les structures sont définies et contraintes par des relations entre commutateurs, qui mesurent l'obstruction à la commutativité. Les groupes $M_{\rho, \sigma}$ sont des exemples fondamentaux de groupes non-commutatifs dont la structure interne est riche.
*   **Théorie de Galois**: Le lien est direct via le cas universel. Le groupe $\Upsilon_{\rho, \sigma}$ s'identifie à $\Gamma_{0,3}^{\sim}$, qui est étroitement lié au groupe de Galois absolu $\text{Gal}(\overline{\mathbb{Q}}/\mathbb{Q})$. L'étude de ces groupes et de leurs représentations est un thème central de la géométrie anabélienne de Grothendieck.
*   **Géométrie des Échelles (Scale Geometry)**: Le "multiplicateur" (multiplier) $\mu \in \hat{\mathbb{Z}}^*$ qui apparaît systématiquement, notamment dans la relation $u(\varepsilon_0) = \varepsilon_0^\mu$, est une manifestation de la "géométrie des échelles". Il représente une action de dilatation sur un "générateur infinitésimal" $\varepsilon_0$, une caractéristique fondamentale du groupe de Grothendieck-Teichmüller.
*   **Clôture Algébrique (Algebraic Closure)**: La connexion se fait par la théorie de Galois. Le groupe $\text{Gal}(\overline{\mathbb{Q}}/\mathbb{Q})$ agit sur la clôture algébrique $\overline{\mathbb{Q}}$. Le formalisme de Grothendieck vise à comprendre cette action via ses manifestations géométriques sur les espaces de modules et leurs groupes fondamentaux, fournissant ainsi un chemin vers une description de $\overline{\mathbb{Q}}$ et de son groupe de Galois.

### Key Concepts
- [[cellular-automata]] — brief description
- [[anabelian-geometry]] — brief description

### Connections
- Builds on general wet-math framework.

<!-- L2: Full Content -->
## Full Text

49. Homomorphismes de M0,3, les groupes Mρ,σ
g´en´eraux
A. Grothendieck
March 11, 2005
1


---

2
[Les remarques entre crochets sont ins´er´ees par la r´edaction.]
[page 550]
49. Homomorphismes de M0,3, les groupes Mρ,σ g´en´eraux.
I) (1). Consid´erons un sous-groupe ferm´e G de M0,3, contenant S+ ∧
0,3 , donc image inverse
d’un sous-groupe ferm´e de Γ0,3
∼. On suppose que celui-ci est ‘suﬃsament gros’ – disons
qu’il contienne un sous-groupe d’indice ﬁni de ΓQ ⊆Γ0,3
∼. Pour le moment, on suppose
pour simpliﬁer que G ⊆Ker ε3. En r´esum´e :
(1)
S+ ∧
0,3
⊆G ⊆M∼
0,3 ,
u ∈G =⇒µ(u) ≡1 (3) .
Cette derni`ere hypoth`ese signiﬁe donc que pour tout u ∈G, on a α0(u) ∈S+ ∧
0,3 , donc on a
(2)
G
-
-
α0
β0
S+ ∧
0,3 ,
caract´eris´es par
(2′)



u(ρ)
=
int(α0)ρ ,
α0
=
α0(u) ,
u(σ)
=
int(β0)σ ,
β0
=
β0(u) .
On consid`ere
(3)
G(0) = G ∩M∼
0,3(0)
  G[0] = G ∩M∼
0,3[0] = NormG(LS
0 ) ,
de sorte que
(4)
G = G(0) · S+ ∧
0,3
(produit semidirect)
(5)
G[0] = G(0) · LS
0
idem
(6)
G[0] ∩S+ ∧
0,3
= LS
0 .
On a pos´e
(7)
LS
0
= sous-groupe ferm´e de S+ ∧
0,3 engendr´e par ε0 ,
et on d´eﬁnit de mˆeme LS
1 , LS
∞.
Consid´erons un groupe proﬁni M, et un homomorphisme (continu) surjectif
(8)
ϕ : G
- M .
On pose
(9)















ϕ(S+ ∧
0,3 )
=
S
sous-groupe distingu´e de M
ϕ(G(0))
=
M(0)
ϕ(G[0])
=
M[0]
ϕ(LS
0 )
=
L0 .
1O`u on se met dans le bain . . . Toute cette section I semble enti`erement inutile pour la suite, c’est un
tˆatonnement pr´eliminaire qui d´ebouche sur la section II, p. 553.


---

3
Donc ce sont des sous-groupes ferm´es de M, satisfaisant
(10)
M(0) ⊆M[0] ⊆NormM(L0)
(11)
L0 ⊆S ∩M[0] .
Par abus de langage, on d´esigne encore par ρ, σ, ε0, ε1 . . . les images de ces ´el´ements
dans S, qui y satisfont donc les relations connues dans S+ ∧
0,3 , en particulier
(12)
σ2 = ρ3 = 1 ,
σρ = ε0 ,
ρσ = ε1 ,
ε1 = σ(ε0) = ρ(ε0) .
Les restrictions des applications α0, β0 de (2, 2′) `a Mρ,σ[0] seront plutˆot not´ees α, β, o`u
α, β sont en fait des applications
(13)
SG
def
= image inverse de G dans SM∼
0,3
|
{z
}
={(u,f)∈G×S+ ∧
0,3 | fu∈G[0]}
-
-
α
β S+ ∧
0,3
dont on regarde les restrictions au sous-groupe (≃Mρ,σ[0]) de SG d´eﬁni par la relation
f = 1.
Composant α, β : G[0]
-
- S+ ∧
0,3 avec ϕ|S+ ∧
0,3 , on trouve des applications, encore not´ees α,
β (ou αM, βM en cas de confusion possible)
(14)
G[0]
-
-
α
β
S ,
satisfaisant donc
(15)



u(ρ)
=
int(α)ρ
u(σ)
=
int(β)σ
pour u ∈M[0] de la forme ϕ(u0),
et α = α(u0), β = β(u0) .
[page 551]
A priori, α et β d´ependent du choix de u0 dont u provient, pas seulement de u – mais
(16)



αρ(α)−1
=
[u, ρ]
βσ(β)−1
=
[u, σ]
n’en d´ependent pas. Si on pose
(17)
Tρ = CentrM(ρ) ,
Tσ = CentrM(σ) ,
on sait donc que, modulo Tρ resp. Tσ, α, β ne d´ependent pas de u.
Hypoth`ese. α = α(u0), β = β(u0) ne d´ependent que de u = ϕ(u0) (pour u0 ∈G[0]).
On va exprimer cette hypoth`ese de fa¸con un peu diﬀ´erente, en introduisant
(18)
J = Ker(G[0]
- M[0]) ,
on veut donc que pour
u′
0 = δ0u0 ,


---

4
avec u0 ∈G[0], δ0 ∈J, on ait
α(u′
0) = α(u0) ,
β(u′
0) = β(u0) .
Soient α0 = α(u0), β0 = β(u0), α′
0 = α(u′
0), β′
0 = β(u′
0), α0 = α(δ0), β0 = β(δ0) dans G,
de sorte qu’on aura, par les formules de cocycles dans G,
α′
0 = δ0(α0)α0 ,
β′
0 = δ0(β0)β0 ,
d’o`u, en appliquant ϕ et notant que
ϕ(δ0(α0)) = ϕ(δ0)
| {z }
= 1
(ϕ(α0)) = ϕ(α0)
def
= α ,
et de mˆeme
ϕ(δ0(β0)) = ϕ(β0)
def
= β
(19)
α′ = αα ,
β′ = ββ
dans S ,
o`u α, β, α′, β′, α, β sont les images par ϕ des quantit´es α0 etc. dans S+∧
0,3 . Donc l’hypoth`ese
signiﬁe aussi
(20)
∀δ0 ∈J
def
= Ker(G[0]
- M[0]), on a απ(δ0), βπ(δ0) ∈Ker ϕ.
Quand cette hypoth`ese est satisfaite, on a donc des applications
(21)
M[0]
-
-
α
β
S
factorisant (14), et satisfaisant donc
(22)



u(ρ)
=
int(α)ρ
u(σ)
=
int(β)σ
pour u ∈M[0], α = α(u), β = β(u) ,
qui paraphrasent (21).
D’ailleurs, posant
(23)
ξ = αρ(α)−1 ,
η = βσ(β)−1 ,
les relations (22) s’´ecrivent aussi
(24)
u(ρ) = ξρ ,
u(σ) = ησ
et on aura
(25)
ξ = [u, ρ] ,
η = [u, σ] ,
et de plus
(26)
ξ = ηlν
1 ,
o`u ν = µ−1
2
∈ˆZ
(µ le multiplicateur de u) ,
qui provient de la relation analogue dans S+
0,3.
(On suppose pour ﬁxer les id´ees que
l’homomorphisme
G
-
χG
ˆZ∗
(‘multiplicateur’)


---

5
se factorise par
(27)
G
- M
-
χM ˆZ∗,
de sorte qu’on a une notion de multiplicateur (∈ˆZ∗) pour les u ∈M.)
Consid´erons l’homomorphisme naturel
(28)
M[0]
-
Aut(S)
u
-
int(u)|S ,
on voit sur (22) ou sur (24) qu’il est connu quand on connaˆıt
[page 552]
les fonctions α, β : M[0]
- S, et mˆeme quand on connaˆıt seulement ξ, η : M[0]
- S
(2). Si d’ailleurs on pose
(29)
M′[0] = Im(M[0]
- Aut(S)) ,
ces derni`eres fonctions ξ, η sont d´ej`a d´eﬁnies sur M′[0] – alors qu’il n’est pas clair qu’il
en soit de mˆeme de α, β, quand M[0] n’op`ere pas ﬁd`element sur S. On a ainsi une
application (ξ, η) d’un certain sous-groupe M′[0] ⊆NormAut(S)(L0) dans l’ensemble des
solutions de l’´equation en ξ, η (26) qu’on ´ecrira simplement
(31)
η−1ξ ∈L1
[3] ,
relation qui implique (26) (avec la forme pr´ecise de l’exposant ν) si on suppose p.ex. S
assez gros pour que S+ ∧
0,3
- SL(2, ˆZ) se factorise par S – ce qu’on va supposer, pour
nous simpliﬁer la vie.
De fa¸con plus pr´ecise, soit
(32)
Σ = ΣS,ρ,σ
=

















(ξ, η)

a)
ξρ conjugu´e `a ρ dans S, i.e. ξ de la forme
[α, ρ] = αρ(α)−1.
b)
ξσ conjugu´e `a σ dans S, i.e. η de la forme
[β, σ] = βσ(β)−1.
c)
η−1ξ ∈L1, i.e. ∃ν′ ∈ˆZ tel que ξ = ηεν′
1 .

















⊆
S × S
[plut^ot ησ conjugu´e `a σ dans b)], et soit u ∈Aut(S) un automorphisme de S, et
posons
(34)



ξ = [u, ρ] = uρu−1ρ−1 = u(ρ)ρ−1 ,
i.e. u(ρ) = ξρ
η = [u, σ] = u(σ)σ−1 ,
i.e. u(σ) = ησ
,
cf. (24), (25),
[4] ,
alors dire que ξρ (= u(ρ)) est conjugu´e `a ρ signiﬁe que u ﬁxe la classe de conjugaison de
ρ, dire que ησ (= u(σ)) est conjugu´e de σ signiﬁe que u ﬁxe la classe de conjugaison de
2car ρ, σ engendrent topologiquement S.
3[(30) n’existe pas.]
4[(33) n’existe pas.]


---

6
σ. Enﬁn la condition η−1ξ ∈L1 s’´ecrit aussi, comme
η−1ξ
=
(σu(σ−1))(u(ρ)ρ−1)
=
σu(σ−1ρ)ρ−1
=
σ

u(σ−1ρ
|{z}
= ε0
) (ρ−1σ)
| {z }
= ε−1
0

=
σ(u(ε0)ε−1
0 ) ,
(5)
sous la forme
σ(u(ε0)ε−1
0 ) ∈L1 ,
i.e. u(ε0)ε−1
0
∈L0
(puisque L0 = σ−1(L1)), ou encore (puisque ε0 ∈L0) u(ε0) ∈L0, soit (puisque ε0 engendre
L0)
u(L0) = L0 ,
i.e. que u normalise L0 (6).
Soit donc
(35)
˜B′
0
def
=


u ∈Aut(S)

u ﬁxe [la] classe de conjugaison de ρ et celle de σ
u normalise L0



⊆
Aut(S) ,
de sorte qu’on a une application (injective parce que ρ, σ engendrent S)
(36)
˜B′
0
-

Σ
u
-

[u, ρ] = u(ρ)ρ−1 , [u, σ] = u(σ)σ−1
.
[page 553]
(37)
Hypoth`ese fondamentale sur S, muni de ρ, σ, d’o`u ε0 = σ−1ρ, ε1 = ρσ−1 =
σ(ε0) = ρ(ε0) :
a)
S est engendr´e topologiquement par ρ, σ.
b)
L’application (36) (injective par a)) est bijective.
La condition b) signiﬁe donc que pour (α, β) ∈S × S, satisfaisant une relation
αρ(α)−1
|
{z
}
= ξ
= βσ(β)−1
|
{z
}
= η
εν′
1 ,
ν′ convenable,
il existe u ∈Aut(S) tel qu’on ait
[u, ρ]
=
αρ(α)−1 ,
i.e.
u(ρ)
=
int(α)(ρ) ,
i.e.
u(ρ)
=
ξρ
[u, σ]
=
βσ(β)−1 ,
i.e.
u(σ)
=
int(β)(σ) ,
i.e.
u(σ)
=
ησ
5NB σ−1 = σ.
6Dans cet argument, on n’a utilis´e que la relation σ−1
0 ρ = ε0 [plut^ot σ−1ρ = ε0] et le fait que ε0
engendre L0, et pas que σ2 = 1 ou ρ3 = 1 p.ex.


---

7
(on aura donc n´ecessairement u ∈˜B′
0, et u sera unique si on a a)).
Ainsi, sur l’ensemble des Rρ,σ des (ξ, η) satisfaisant a) b) c), on aura une structure de
groupe, d´eduite par transport de structure de celle de ˜B′
0 etc.
II) Les groupes M′
ρ,σ etc.
Reprenons la situation ab ovo, en oubliant (au moins pour le moment) G, ϕ etc.
(7). Soit S un groupe – on se place pour le moment, soit dans le contexte des groupes
discr`etes, soit dans celui des groupes proﬁnis, au choix.
On va (pour ﬁxer les id´ees)
prendre celui des groupes proﬁnis. On suppose donn´es
(1)
ρ, σ ∈S ,
on pose
(2)
ε0 = σ−1ρ ,
ε1 = ρσ−1 = σ(ε0) = ρ(ε0)
(8)
(3)
L0
=
sous-groupe ferm´e engendr´e par ε0
L1
=
sous-groupe ferm´e engendr´e par ε1 ,
donc L1 = ρ(L0) = σ(L0) .
On consid`ere
(4)
Aut(S)
-
Φ = (ξ,η)
S × S
d´eﬁni par
(5)















ξ(u)
=
[u, ρ]
=
uρu−1ρ−1
=
u(ρ)ρ−1
donc u(ρ) = ξρ
=
uρ(u)−1
(ξ = ξ(u))
η(u)
=
[u, σ]
=
uσu−1σ−1
=
u(σ)σ−1
donc u(σ) = ησ
=
uσ(u)−1
(η = η(u)) .
Donc pour u ∈Aut(S), et ξ = ξ(u), η = η(u), on a
(6)





















u ﬁxe la classe de S-conjugaison de ρ
⇐⇒
ξρ conjugu´e `a ρ
⇐⇒
ξ = αρ(α)−1 (α ∈S)
u ﬁxe la classe de S-conjugaison de σ
⇐⇒
ησ conjugu´e `a σ
⇐⇒
η = βρ(β)−1 (β ∈S)
u normalise L0 ⇐⇒η−1ξ ∈L1 ⇐⇒ξ = ηεν
1 avec ν ∈ˆZ convenable.
7Pour une rectiﬁcation syst´ematique des notations qui suivent, cf. page 564, remarques.
8I.e. on a entre ε0 = l′
0, σ = l′
1 et ρ−1 = l′
∞une relation l′
∞l′
1l′
0 = 1.


---

8
[page 554]
Soient
(7)
Bρ,σ = {u | satisfaisant les trois conditions (6)} ⊆Aut(S)
(8)
Σρ,σ =









(ξ, η)

ξ = αρ(α)−1, i.e. ξρ conjugu´e `a ρ,
η = βσ(β)−1, i.e. ησ conjugu´e `a σ (α, β ∈S)
η−1ξ ∈L1, i.e. ξ = ηεν
1 (ν ∈ˆZ)









,
de sorte que Bρ,σ est l’image inverse de Σρ,σ par (4), et on a une application induite
(9)
Bρ,σ
-
ϕ0 = ϕρ,σ
Σρ,σ .
On suppose
(10)



a)
ρ, σ engendrent S topologiquement.
b)
L’application (9) (injective par a)) est surjective (donc bijective).
(9) .
On transporte alors par ϕ la structure de groupe de Bρ,σ `a Σρ,σ. On pose
(11)
uξ,η = ϕ−1(ξ, η) ∈Bρ,σ
((ξ, η) ∈Σρ,σ) ,
de sorte que uξ,η est caract´eris´e par
(12)



uξ,η(ρ)
=
ξρ
uξ,η(σ)
=
ησ .
L’hypoth`ese b) signiﬁe donc que , d`es que (ξ, η) ∈Σρ,σ, i.e. ξρ conjugu´e `a η, ησ conjugu´e
`a η, et η−1ξ ∈L1, il existe un automorphisme uξ,η de S satisfaisant (12) (et qui sera
unique par (10 a)). La loi de groupe sur Σρ,σ s’explicite ainsi :
(13)
(ξ′, η′)(ξ, η) = (ξ′′, η′′)
avec



ξ′′
=
uξ′,η′(ξ)ξ′
η′′
=
uξ′,η′(η)η′
.
Consid´erons l’homomorphisme
S
-
Aut(S)
g
-
int(g) ,
l’image inverse de Bρ,σ n’est autre que le normalisateur de L0 dans S, soit N0.
On
veut construire alors un groupe Gρ,σ, contenant S comme sous-groupe invariant, et dans
lequel s’envoie Bρ,σ, de fa¸con que l’action tautologique de Bρ,σ sur S soit d´eduite de
cet homomorphisme, et que Gρ,σ soit engendr´e par S et l’image de Bρ,σ, not´ee B′
ρ,σ, qui
9Attention, cette condition est satisfaite pour S = SL(2, ˆZ)′ ! (Le signe ε = ε3(µ) ne gˆene pas au
niveau ξ, η . . . )


---

9
contient N0. Si le centre de S est trivial, i.e. S
-

Aut(S) (S sous-groupe distingu´e), il
suﬃt de prendre le sous-groupe Gρ,σ de Aut(S) engendr´e par S et Bρ,σ. Mais l’hypoth`ese
que le centre de S est trivial n’est pas heureuse – p.ex. elle n’est pas satisfaite si S =
SL(2, ˆZ)/ ± 1. Il me semble que l’introduction de N0 (sur lequel en pratique nous n’avons
aucun contrˆole)
[page 555]
n’´etait pas non plus judicieuse, et la condition B′
ρ,σ ⊇N0 – il suﬃra de B′
ρ,σ ⊇L0. Je vais
donc consid´erer
(14)









S0Gρ,σ
def
= Bρ,σ · S
le produit semi-direct, et
L0
-

i
S0Gρ,σ
g
-
int(g) · g−1 .
L’image de cet homomorphisme est un sous-groupe distingu´e, car
a) il commute `a S (trivial), et
b) il est invari´e par Bρ,σ, car on aura pour u ∈Bρ,σ
int(u) (i(g)) = int(u)
 int(g) · g−1
= int(u(g)) · int(u(g−1))
|
{z
}
u(g−1) = u(g)−1
= i(u(g))
(i.e. i commute aux actions de Bρ,σ, op´erant sur L0 par restriction `a L0 de l’op´eration
tautologique de Bρ,σ sur S, et sur S0Gρ,σ ⊇Bρ,σ par automorphisme int´erieur).
On peut donc consid´erer
(15)
Gρ,σ
def
= S0Gρ,σ/i(L0) ,
alors les homomorphismes d’inclusion
Bρ,σ
-

S0Gρ,σ ,
S
- S0Gρ,σ
donnent, par composition avec S0Gρ,σ
- Gρ,σ, des homomorphismes
(16)
S
-

Gρ,σ ,
Bρ,σ
-

Gρ,σ ,
rendant commutatif le diagramme
(17)
L0 HHHH
j

*
Bρ,σ
S HHHH
j

* Gρ,σ .
On notera
(18)
Ker(S
- Gρ,σ) = L0 ∩Centr(S) = Ker(L0
- Bρ,σ) .


---

10
Donc le cas S = SL(2, ˆZ)′ (avec ρ, σ comme `a l’accoutum´ee on aura L0 ∩Centr(S) = 1.
Donc il ne semble pas a priori qu’il y ait des inconv´enients majeurs `a supposer que
(18)
L0 ∩Centr(S) = {1} ,
i.e. S
-

Gρ,σ injectif
[10] .
Notons que l’image de
L0
-
Bρ,σ
l
-
int(l)
(compos´e de (14) et de la projection S0Gρ,σ
- Bρ,σ) est ´evidemment invariante, et posant
(19)
Υρ,σ = Bρ,σ/ Im L0
on trouve
(20)
Gρ,σ/Sρ,σ ≃Bρ,σ/L0 ≃Υρ,σ ,
i.e. [on a un] homomorphisme de suites exactes
(20 bis)
1
- L0
- Bρ,σ
- Υρ,σ
- 1
?
  ?
  1
- S
|{z}
= SGρ,σ
- Gρ,σ
- Υρ,σ
- 1
NB Dans le cas S = SL(2, ˆZ)′, etc., Bρ,σ ⊆GL(ˆZ) est le groupe not´e pr´ec´edemment B′
0
(alors plutˆot son image isomorphique ˜B′
0), et l’homomorphisme det |B′
0 = Bρ,σ (trivial sur
L0), induit par passage au quotient un isomorphisme
(21)
Υρ,σ
-
∼
Gm ,
et on voit, utilisant l’isomorphisme
B′
0
=
Υ0 · L0 (semi-direct) ,
o`u Υ0
-
∼B′
0/L0 ≃Gm
i.e.
Bρ,σ
≃
Υρ,σ · L0 ,
que dans ce cas on a
(22)
Gρ,σ = GL(2, ˆZ)′ .
(11)
[page 556]
Mais dans les cas plus g´en´eraux auxquels nous aspirons, il ne faut pas du tout s’attendre
`a ce que Υρ,σ soit aussi petit – p.ex. qu’il soit commutatif.
Par exemple dans le cas
‘universel’ S = S+ ∧
0,3 , on aura
(23)
Bρ,σ = M0,3
∼[0]′ = Ker(M0,3
∼[0]
-
ε3 {±1}) ,
10[Deux fois (18).]
11Dans le cas o`u on part de SL(2, ˆZ), ρ, σ, on tombe sur Gρ,σ = GL(2, ˆZ) [?] . . .


---

11
donc
(24)
Υρ,σ ≃Γ0,3
∼′
(⊇Γ′
Q !) .
Par contre, on doit pouvoir sans inconv´enient postuler l’existence d’un scindage canonique
de l’extension Bρ,σ de Γρ,σ [plut^ot Υρ,σ] par L0. En fait, si on suppose, dans le cas
g´en´eral, o`u n´eanmoins on suppose σ2 = ρ3 = 1, i.e. S quotient de S+ ∧
0,3 , que le quotient
S de S+ ∧
0,3 est assez grand pour s’envoyer dans GL(ˆZ), alors Bρ,σ ≃Σρ,σ s’envoie dans
˜B′
0, et l’image inverse de ˜T0 est un sous-groupe (qu’on pourrait noter Tρ,σ)
(25)
Tρ,σ ⊆Bρ,σ ,
Tρ,σ
-
∼
Υρ,σ ,
qui est un sous-groupe section, pour Bρ,σ
- Υρ,σ, et aussi (en tant que sous-groupe de
Gρ,σ) pour Gρ,σ
- Υρ,σ, de sorte qu’on aura
(26)
Bρ,σ ≃Tρ,σ · L0 ,
Gρ,σ ≃Tρ,σ · S
(produits semi-directs) .
Soit maintenant
(27)







SGρ,σ
def
=
{(α, β) | αρ(α)−1
|
{z
}
= ξ
= βσ(β)−1
|
{z
}
= η
εν
1, pour ν ∈ˆZ convenable, i.e. η−1ξ ∈L0}
⊆
S × S .
On a une application canonique
(28)
SGρ,σ
-
Σρ,σ
(α, β)
-
(ξ, η) ,
ξ = αρ(α)−1, η = βσ(β)−1 ,
qui est surjective par d´eﬁnition de Σρ,σ, et en fait par l’hypoth`ese (10), on a presque une
section canonique
Σρ,σ
-
SGρ,σ
(ξ, η)
-
uξ,η
[c.`a.d. (uξ,η, uξ,η)], `a cela pr`es que uξ,η n’est pas dans S, mais seulement dans Gρ,σ.
Nous allons consid´erer alors l’ensemble plus gros
(29)







Gρ,σ
def
=
{(α, β) | αρ(α)−1
|
{z
}
= ξ
= βσ(β)−1
|
{z
}
= η
εν
1 ,
pour ν ∈ˆZ convenable}
⊆
Gρ,σ × Gρ,σ
(12) ,
de sorte que l’on aura
(30)
SGρ,σ = Gρ,σ ∩(S × S)
(en supposant (18) pour simpliﬁer).
12NB On aura aussi ξ = α(ρ)ρ−1, η = β(σ)σ−1, donc ξ, η ∈S (puisque S invariant dans Gρ,σ)


---

12
[page 557]
On trouve encore
(31)









Gρ,σ
-
Σρ,σ
(α, β)
-
(ξ, η) ,
ξ
=
αρ(α)−1
=
[α, ρ]
=
α(ρ)ρ−1
η
=
βσ(β)−1
=
[β, σ]
=
β(σ)σ−1
(par d´eﬁnition de Bρ,σ on trouve bien que les (ξ, η) associ´es aux (α, β) sont dans Σρ,σ).
Cette fois-ci l’hypoth`ese (10) implique qu’on a une section canonique
(32)
Σρ,σ
-
Gρ,σ
(ξ, η)
-
(uξ,η, uξ,η)
et on trouve (comme dans §48 III) :
Th´eor`eme. Consid´erons les sous-groupes de Gρ,σ
(33)



Zρ
=
CentrGρ,σ(ρ)
Zσ
=
CentrGρ,σ(σ) ,
(13)
et le groupe produit
Bρ,σ × Tρ × Tσ ,
alors on a une application bijective
(34)
Bρ,σ × Tρ × Tσ
-
∼
Gρ,σ
(u, a, b)
-
(ua−1, ub−1).
Corollaire. Consid´erons les homomorphismes de groupes
(35)
δB : Bρ,σ
- Υρ,σ , δG : Gρ,σ
- Υρ,σ , δρ : Zρ
- Υρ,σ , δσ : Zσ
- Υρ,σ ,
o`u δG est l’homomorphisme canonique de passage au quotient par Sρ,σ = S, et δρ, δσ,
δB sont les compos´es de δG avec les inclusions Zρ
-

Gρ,σ, Zσ
-

Gρ,σ, [une ligne
manque] (14). Soit
(36)
S0Γ0
ρ,σ
def
= {(u, a, b) | δG(u) = δρ(a) = δσ(b)} ⊆Bρ,σ × Zρ × Zσ
(15, 16)
I.e.
(37)
S0Γ0
ρ,σ = Bρ,σ ×Υρ,σ Zρ ×Υρ,σ Zσ .
13NB dans le cas S = SL(2, ˆZ)′ etc., on aura
Zρ
=
Tρ
Zσ
=
Nσ .
14Par d´eﬁnition de Bρ,σ (7), on voit que Zρ
- Bρ,σ et Zσ
- Bρ,σ sont ´epimorphes, donc aussi leurs
compos´es δρ, δσ avec Bρ,σ
- Υρ,σ, donc les quatre homomorphismes (35) sont ´epimorphes . . .
15Not´e S0Tρ,σ dans le §48, IX ﬀ.
16NB La lettre S ici est inspir´ee de l’usage de cette lettre pour les ‘groupes de Teichm¨uller sp´eciaux’, et
n’a pas donc le mˆeme sens que dans SZρ, SZσ, o`u elle indique que l’on prend le noyau de δρ, δσ (jouant
le rˆole d’un d´eterminant . . . ).


---

13
Alors on a une bijection
(38)



S0Γ0
ρ,σ
-
∼
S0Gρ,σ
(d´eﬁni dans (27))
(u, a, b)
-
(ξ, η) ,
avec ξ = ua−1, η = ub−1 .
Scholie. Par les bijections (34), (38), on transporte sur Gρ,σ, S0Gρ,σ les structures de
groupe naturelles de Γ0 ∼
ρ,σ, Γ0
ρ,σ. Explicitant cette structure de groupe, on trouve notam-
ment pour SGρ,σ
(39)















(α′, β′)(α, β) = (α′′, β′′) ,
avec
α′′ = u′(α)α′, β′′ = u′(β)β′
u′ = uξ′,η′ : S
- S ,
d´eﬁni par



u(ρ)
=
ξρ
=
int(α)ρ
u(σ)
=
ησ
=
int(β)σ
(avec ξ = αρ(α)−1, η = βσ(β)−1)
Dans SΓ0
ρ,σ, on a un sous-groupe isomorphe `a L0, via
[page 558]
(40)
L0
-
SΓ0
ρ,σ ⊆Bρ,σ × Zρ × Zσ
l
-
(l, 1, 1) ,
et l’action de L0 par translation `a gauche sur SΓ0
ρ,σ devient, par (39), l’action sur SGρ,σ
donn´ee par
(41)
(α, β)
- (lα, lβ) .
Posant donc
(42)
Γ0
ρ,σ
def
= SΓ0
ρ,σ/ Im L0 ≃Zρ ×Υρ,σ Zσ
(17) ,
on trouve que (39) induit une bijection canonique
(43)
Γ0
ρ,σ
-
∼
L0\SGρ,σ .
Posant
(44)



SZρ
def
=
Ker(Zρ
- Γρ,σ)
=
CentrS(ρ)
SZρ
=
Ker(Zρ
- Γρ,σ)
=
CentrS(σ)
(18)
[plut^ot SZσ
def
= Ker(Zσ
- Γρ,σ) = CentrS(σ)], on a donc des suites exactes
(45)



1
- SZρ
- Zρ
- Γρ,σ
- 1
1
- SZσ
- Zσ
- Γρ,σ
- 1 ,
17Not´e T 0
ρ,σ dans §48, IX ﬀ.
18Introduire aussi
SΓρ,σ
=
Ker(Γρ,σ
- Υρ,σ)
SGρ,σ
=
Ker(Gρ,σ
- Υρ,σ)
=
Sρ,σ = S


---

14
et les expressions (37), (42) de S0Γ0
ρ,σ, Γ0
ρ,σ donnent
(46)
1
- L0 × SZρ × SZσ
- S0Γ0
ρ,σ
- Υρ,σ
- 1 ,
(47)
1
- SZρ × SZσ
- Γ0
ρ,σ
- Υρ,σ
- 1 .
NB Dans le cas S = SL(2, ˆZ), ρ et σ ‘modulaires’, on retrouve les S0Γ0
ρ,σ et Γ0
ρ,σ de §48
IX.
[page 559]
Soit maintenant
(49)
[SM0
ρ,σ =] S0M0
ρ,σ
def
=
{(u, a, b, U) | δB(u) = δρ(a) = δσ(b) = δG(U)
|
{z
}
relation dans Υρ,σ, cf. (19)
}
⊆
SΓ0
ρ,σ × Gρ,σ
(⊆Bρ,σ × Zρ × Zσ × Gρ,σ)
[19] ,
(50)
M0
ρ,σ
def
=
{(a, b, U) | δρ(a) = δσ(b) = δG(U)
|
{z
}
relation dans Υρ,σ
}
⊆
Tρ × Tσ × Gρ,σ
[plut^ot . . . ⊆Zρ × Zσ × Gρ,σ]. On a donc un homomorphisme canonique
(51)
SM0
ρ,σ
-
M0
ρ,σ
(u, a, b, U)
-
(a, b, U) ,
dont le noyau est form´e des (u, 1, 1, 1) avec u ∈Bρ,σ tel que δB(u) = 1, i.e. u ∈L0, d’o`u
une suite exacte
(52)
1
- L0
- SM0
ρ,σ
- M0
ρ,σ
- 1
et des homomorphismes canoniques
(53)
M0
ρ,σ


*
θG
Gρ,σ
-
θρ
Zρ
HHH
H
j
θσ
Zσ

resp.
(a, b, U)


* U
- a
HHH
H
j b

,
redonnant les homomorphismes analogues sur SM0
ρ,σ par composition avec (41), et de
plus on a un homomorphisme canonique
(54)
SM0
ρ,σ
-
θB
Bρ,σ
(u, a, b, U)
-
u .
19[(48) n’existe pas.]


---

15
On a aussi l’interpr´etation
(55)
S0M0
ρ,σ ≃M0
ρ,σ ×Υρ,σ Bρ,σ ;
S0M0
ρ,σ s’exprime `a l’aide de M0
ρ,σ et Bρ,σ, et en tant qu’extension de Mρ,σ par L0 est
l’image inverse de l’extension Bρ,σ de Υρ,σ par L0. Et on a
(56)
M0
ρ,σ ≃Zρ ×Υρ,σ Zσ
|
{z
}
= Γ0ρ,σ
×Υρ,σGρ,σ ,
d’o`u on d´eduit (comme δρ, δσ, δG sont ´epimorphes)
(57)
1
- SZρ × SZσ × S
|
{z
}
def
= M0 +
ρ,σ
- M0
ρ,σ
-
δM Υρ,σ
- 1 ,
o`u on a (44)



SZρ
=
Zρ ∩S
=
CentrS(ρ)
SZσ
=
Zσ ∩S
=
CentrS(σ) .
De mˆeme, on a
(49)
S0M0
ρ,σ ≃Bρ,σ ×Υρ,σ Zρ ×Υρ,σ Zσ
|
{z
}
= S0Γ0ρ,σ
×Υρ,σGρ,σ
[20] ,
donc on a une suite exacte canonique
(50)
1
- L0 × SZρ × SZσ × S
- S0M0
ρ,σ
- Γρ,σ
- 1 .
Consid´erons l’homomorphisme canonique
(51)
S
-
iS
M0
ρ,σ
U
-
(1, 1, U) ,
[page 560]
son image est le troisi`eme facteur dans le noyau de (57), et on a une suite exacte canonique
(d´eduite de (56) et (57))
(52)
1
-
S
|{z}
parfois not´e
Sρ,σ ?
- M0
ρ,σ
- Γ0
ρ,σ
- 1 ,
et de mˆeme on a (via (49) ou (50))
(53)
1
- S
- S0M0
ρ,σ
- S0Γ0
ρ,σ
- 1 ,
(53′)
1
- SZρ × SZσ
- M0
ρ,σ
- G
- 1 .
20[Saut dans la num´erotation.]


---

16
Consid´erons l’application
(54)
S0M0
ρ,σ
-
S × S × S
(u, a, b, U)
-
(ua−1, ub−1, uU −1) = (α, β, f) ,
on voit par le corollaire p. 557 (cf. (37)) que cela induit une bijection
(55)
S0M0
ρ,σ ≃(SGρ,σ) × S .
On a ainsi pour un x ∈S0M0
ρ,σ, d’une part pour les quantit´es
(56)
u
|{z}
∈Bρ,σ
,
a
|{z}
∈Zσ
,
b
|{z}
∈Zρ
,
U
|{z}
∈Gρ,σ
associ´es, d’autre part les ´el´ements
(57)
α, β, f, ξ, η, α0, β0, g, h
tous dans S ,
o`u (α, β, f) [sont] d´eﬁnis en termes de (56) dans (54), et o`u on a pos´e
(58)



ξ = αρ(α)−1, η = βσ(β)−1, α0 = f −1α, β0 = f −1β
g = α0ρ(α0)−1 = f −1ξρ(f), h = β0σ(β)−1 = f −1ησ(f) .
On aura, en termes de α, β, f, les expressions suivantes de l’action de U sur S :
(59)



U(ρ)
=
int(f −1α)(ρ)
=
int(f −1)(ξρ)
U(σ)
=
int(f −1β)(σ)
=
int(f −1)(ησ) .
Remords. Finalement, dans tous ces d´eveloppements, on n’a pas vraiment utilis´e la
soi-disante ‘hypoth`ese fondamentale’ (20), sauf la partie a). En l’absence de b), il y a lieu
d’introduire
(60) Σeﬀ
ρ,σ = {(ξ, η) ∈S × S | ∃u ∈Bρ,σ, u(ρ) = ξρ, u(σ) = ησ} ⊆Σρ,σ ⊆S × S ,
qui n’est donc autre que l’image de l’application (9) : couples eﬀectifs (ξ, η) satisfaisant
les conditions d´eﬁnissant Σρ,σ (cf. (8)). On notera
(61)
SGeﬀ
ρ,σ = Image inverse de Σeﬀ
ρ,σ par SGρ,σ
- Σρ,σ (28) ,
et c’est sur SGeﬀ
ρ,σ qu’on aura une structure
[page 561]
de groupe isomorphe `a S0Γ0
ρ,σ, par l’isomorphisme (qui remplace (38))
(62)
S0Γ0
ρ,σ
-
∼
S0Geﬀ
ρ,σ
(u, a, b)
-
(ua−1
|{z}
= ξ
, ub−1
|{z}
= η
) .
Ceci pos´e, revenons `a M∼
ρ,σ, et la suite exacte
(63)
1
- S+ ∧
0,3
- M∼
ρ,σ
-
Γ∼
0,3
|{z}
= Γ∼
Q
- 1 .


---

17
Consid´erons le sous-groupe
(64)
Γ′∼
Q
=
Ker(Γ∼
0,3
-
ε3 {±1})
=
{γ ∈Γ∼
0,3 | µ(γ) ≡1 (3)} ,
et soit
(65)
M′∼
0,3 = Image inverse de Γ′∼
0,3 dans M∼
0,3 .
Soit S un groupe proﬁni, et
(66)
ψ : S+ ∧
0,3
- S
un homomorphisme continu surjectif – ce qui revient au mˆeme que de se donner deux
´el´ements
(67)
ρS , σS ∈S
(les images de ρ, σ par ψ) satisfaisant
(68)
ρ3
S = σ2
S = 1
[et qui engendrent S].
D´eﬁnition (21). On dira que ψ est eﬀectif si pour tout u ∈M′∼
0,3[0], posant u(ρ) = ξρ,
u(σ) = ησ, le couple
(ξS, ηS) = (u(ξ), u(η)) ∈Σρ,σ
est eﬀectif, i.e. dans Σeﬀ
ρ,σ, i.e. ∃uS automorphisme de S tel que
(69)
uS(ρS) = ξSρS ,
uS(σS) = ηSσS ,
ou, ce qui revient au mˆeme, qu’on a commutativit´e
(70)
S+ ∧
0,3
-
u
S+ ∧
0,3
?
ψ
?
ψ
S
-
uS
S .
Donc dire que c’est le cas pour tout u ∈M′∼
0,3[0] signiﬁe que ces u transforment Ker ψ
en lui-mˆeme – ou aussi, que M′∼
0,3 (= M′∼
0,3[0] · S+ ∧
0,3 ) tout entier stabilise Ker ψ. Cette
condition est donc automatiquement remplie quand S, ρS, σS satisfont la condition b)
de (20).
21L’introduire par conditions ´equivalentes :
a) M′∼
0,3[0]
- Σ eﬀ
ρ,σ.
  
b) ∀u ∈M′∼
0,3, ∃uS ∈Aut S tel que uS ◦ψ = ψ ◦u.
b′) Itou avec u ∈M′∼
0,3[0].
c) ∃ψM qui prolonge ψ.
c′) ∃ψS qui prolonge ψ.
On dira alors que ψ est eﬀective. C’est automatique si (20) b) [est] satisfait.


---

18
On a fait ce qu’il fallait pour avoir le
[page 562]
Th´eor`eme.
Soit ψ = ψS : S+ ∧
0,3
- S un homomorphisme surjectif eﬀectif (cf. ci-
dessus). Alors il existe un homomorphisme unique
(71)
ψM : M′∼
0,3
- M0
ρS,σS
ayant la propri´et´e suivante : Si u ∈M′∼
0,3 est de la forme uα,β,f (α, β, f ∈S+ ∧
0,3 , sa-
tisfaisant l’´equation des lacets αρ(α)−1 = βσ(β)−1lν
1), alors ψM(u) est l’´el´ement de M0
ψ
d´eﬁni par les invariants ψ(α), ψ(β), ψ(f) (22).
Corollaire. On a alors des homorphismes des suites exactes
(72)
1
- S+ ∧
0,3
- M′∼
0,3
- Γ′∼
Q
- 1
?
ψS
?
ψM
?
ψT
1
- S
- M0
ψ
- Γ0
ψ
- 1 .
L’homomorphisme ψM s’explicite `a l’aide des trois homomorphismes
(73)



ψTρ :
Γ′∼
Q
-
Zρ
ψTσ :
Γ′∼
Q
-
Zσ
(74)
ψG : M′∼
0,3
- Gρ,σ
(23)
Pour x ∈M′∼
0,3, ˙x son image dans Γ′∼
Q, et
(75)
a = ψΓρ( ˙x) ,
b = ψΓσ( ˙x) ,
U = ψG(x) ,
on a
(76)
δρ(a) = δσ(b) = δG(U)
dans Υρ,σ ,
i.e. les trois homomorphismes compos´es
(77)
M′∼
0,3
    
can.
-
can.
QQQQQQQ
s
ψG
Γ′∼
Q
-
ψΓρ
Γρ
Γ′∼
Q
-
ψΓσ
Γσ
Gρ,σ
@
@
@@
R
δρ
-
δσ

3
δG
Υρ,σ
22En fait, on a bien sˆur en premier lieu un homomorphisme
S0M′∼
0,3
- S0M0
ψ .
23NB on ´ecrit pour simpliﬁer ρ, σ au lieu de ρS, σS en indices.


---

19
sont ´egaux. De plus, on aura d’apr`es (76)
(78)
ψG|S+ ∧
0,3
= ψS ,
et enﬁn ceci :
(79)
Si x ∈M′∼
0,3 , U = ψG(x) , on a commutativit´e dans
(80)
S+ ∧
0,3
-
ψ
S
?
int(x)|S+ ∧
0,3
?
int(U)|S
S+ ∧
0,3
-
ψ
S .
[page 563]
On peut reprendre tout ceci comme un ´enonc´e de fonctorialit´e des constructions faites,
par rapport `a un homomorphisme surjectif
(81)
S
-
ϕ = ϕS
S′ ,
transformant le couple (ρ, σ) de g´en´erateurs topologiques de S en un couple (ρ′, σ′) (24).
Il y a alors un unique homomorphisme
(82)
S0M0
S
-
ϕSM0
S0M0
S′
[ϕS0M0 = ϕS0M0 = ϕSM0 = ϕSM dans ce qui suit], satisfaisant les conditions suiv-
antes :
a) ϕSM passe au quotient en des homomorphismes
(83)















ϕB :
Bρ,σ
-
Zρ,σ
[plut^ot Bρ,σ
- Bρ′, σ′]
ϕρ :
Zρ
-
Zρ′
ϕσ :
Zσ
-
Zσ′
ϕG :
Gρ,σ
-
Gρ′, σ′
(25) .
b)
(84)
(
Les homomorphismes ϕB, ϕρ, ϕσ sont induits par ϕG (ce qui montre
que la connaisance de ϕSM se ram`ene `a celle de ϕG) ;
c) On a commutativit´e dans
(85)
S
- Gρ,σ
?
ϕ = ϕS
?
ϕG
S′
- Gρ′, σ′
(ce qui montre, puisque Gρ,σ = Bρ,σ · S, que ϕG est connu quand on connaˆıt ϕB) ;
24Il aurait mieux valu prendre S′
-
ϕ
S pour pouvoir sp´ecialiser en S′.
25Ceci montre que ϕSM est d´etermin´e quand on connaˆıt les quatre homomorphismes ϕB, ϕρ, ϕσ, ϕG.


---

20
d) Pour u ∈Bρ,σ, posant u′ = ϕB(u), on a commutativit´e dans
(86)
S
-
u
S
?
ϕS
?
ϕS
S′
-
u′
S′
(ce qui d´etermine ϕB en termes de ϕ = ϕS, donc cela d´etermine ϕSM, et par passage
au quotient, aussi
(87)
ϕM : Mρ,σ
- Mρ′, σ′
.)
Une autre fa¸con, plus directe, de d´ecrire ϕS0M0 ou ϕM, en termes des ‘param`etres’ (α, β, f)
au lieu de (u, a, b, U), est de dire que ψS0M0 [plut^ot ϕS0M0] transforme un uα,β,f en
uα′,β′,f′, o`u α′, β′, f ′ sont les images de α, β, f par ϕ :
(88)
ϕS0M0( uα,β,f
| {z }
∈S0M0ρ,σ
) = uα′,β′,f′ ,









α′
=
ϕ(α)
β′
=
ϕ(β)
f ′
=
ϕ(f)
.
On retrouve ainsi, sous une forme un peu plus pr´ecise, le th´eor`eme pr´ec´edent en l’appliquant
au cas o`u S = S+ ∧
0,3 (le ‘cas universel’ (26)), S′ quelconque – il vaut mieux dans la nota-
tion (81) interchanger le rˆole de S et S′. Il est bon d’expliciter les invariants essentiels
dans le cas ‘universel’ :
(90)
S′
=
S+ ∧
0,3 ,
B′
ρ′, σ′
=
M′! ∼
0,3[0] ,
Υ′
ρ′, σ′
=
Γ′∼
Q ,
G′
ρ′, σ′
=
M′∼
0,3 ,
Z′
ρ
=
M′∼
0,3(−) ,
Z′
σ
=
M′∼
0,3(1/2) ,
Γ′
ρ′, σ′
=
Γ′
Q ,
[27] ,
[page 564]
(91)
Γ′
ρ′, σ′
-
∼
Υ′
ρ′, σ′ ,
Z′
ρ′
-
∼
Υ′
ρ′, σ′ ,
Z′
σ′
-
∼
Υ′
ρ′, σ′ ,
donc SZ′
ρ′ = SZ′
σ′ = SΓ′
ρ′, σ′ = 1, et
(92)
S0M′
ρ′, σ′ ≃S0G′
ρ′, σ′ ≃S0M′∼
0,3 ,
M′
ρ′, σ′
-
∼
Gρ′, σ′
-
∼
M′∼
0,3 .
Remarque. En ´ecrivant les relations (80) [(90)?], il devenait ´evident que les notations
utilis´ees dans toute cette section II (depuis page 553) ´etaient inad´equates (28), et qu’il
convient de les modiﬁer de la fa¸con suivante :
(93)
Σρ,σ , Bρ,σ , S0Gρ,σ , Gρ,σ , Υρ,σ , Zρ , Zσ , Gρ,σ , SGρ,σ ,
Zρ , Zσ , S0Γ0
ρ,σ , Γ0
ρ,σ , SZρ , SZσ , S0M0
ρ,σ , M0
ρ,σ .
26Tout au moins ‘universel’ par rapport `a l’hypoth`ese suppl´ementaire ρ3 = 1, σ2 = 1 dans S.
27[(89) n’existe pas.]
28Car je m’y ´etais inspir´e du cas S = SL(2, Z), couple modulaire ρ, σ (qui ne re¸coit pas mˆeme S+ ∧
0,3 , `a
cause de {±1} !) et non du cas universel, qui aurait dˆu me servir de ﬁl conducteur pour mes notations.


---

21
On met partout un accent ′ pour en faire Σ′
ρ,σ, B′
ρ,σ etc., et on enl`eve l’exposant 0 de
S0Γ0
ρ,σ, Γ0
ρ,σ, S0M0
ρ,σ, M0
ρ,σ (qui se trouve donc remplac´e par un ′).
Autres cas particuliers importants explicit´es en :
2o) S = SL(2, ˆZ)/ ± 1, (ρ, σ) couple modulaire.
(94)













































B′
ρ,σ
=
n µ λ
0 1
  µ ∈ˆZ∗, µ ≡1 (3), λ ∈ˆZ
o
L0
=
n 1 λ
0 1
  λ ∈ˆZ
o
G′
ρ,σ
=
GL′(2, ˆZ)/ ± 1 , o`u
GL′(2, ˆZ)
def
= {u ∈GL(2, ˆZ) | det ≡1 (3)}
≃Tρ(ˆZ)/µ2(Z)
(29)
Z′
ρ
=
{cρ + d | c2 + cd + d2 ∈ˆZ∗}/ ± 1
Z′
σ
=
N ′
σ(ˆZ)/µ2(Z)
avec notations de §48
S0M′
ρ,σ
≃
SM′
ρ,σ(ˆZ)/Σ
idem
M′
ρ,σ
≃
M′
ρ,σ(ˆZ)/Σ
idem
[-]
≃
T ′
ρ,σ(ˆZ)/Σ0
idem
30) Prenons S = SL(2, ˆZ), avec couple modulaire [(ρ, σ)].
(95)













































B′
ρ,σ
=
n µ λ
0 1
  µ ∈ˆZ∗, µ ≡1 (3), λ ∈ˆZ
o
G′
ρ,σ
=
GL′(2, ˆZ) , o`u
GL′(2, ˆZ)
def
= {u ∈GL(2, ˆZ) | det ≡1 (3)}
Z′
ρ
=
{cρ + d | c, d ∈ˆZ, c2 + cd + d2 ∈ˆZ∗}
Z′
σ
=
T ′
σ · {1, τ∞}, o`u



T ′
σ
def
=
{tσ + u | t, u ∈ˆZ, t2 + u2 ∈ˆZ∗}
τ∞
=
 −1 0
0 1

S0M′
ρ,σ
≃
SM′
ρ,σ(ˆZ)/Σ0
avec notations de §48
M′
ρ,σ
≃
M′
ρ,σ(ˆZ)/Σ0
idem
S0Γ′
ρ,σ
≃
S0T ′
ρ,σ(ˆZ)/Σ0
idem
Γρ,σ
≃
T ′
ρ,σ(ˆZ)/Σ0
idem
[page 565]
III) Consid´erons l’extension GL(2, Z)∧de S∧
0,3 par {±1} :
29C’est G(Z)/µ2(Z) avec notations du §48.


---

22
(1)
1
1
?
?
1
- {±1}
- SL(2, ˆZ)
- S+ ∧
0,3
- 1
?
  ?
1
- {±1}
- GL(2, ˆZ)
- S∧
0,3
- 1
?
?
{±1}
- {±1}
?
?
1
1
On s’int´eresse au groupe N ∼
1,1, d´eﬁni comme extension de M∼
0,3 par {±1}, image inverse
de l’extension GL(2, ˆZ) de GL(2, ˆZ)/ ± 1 par {±1}, via l’homomorphisme canonique
(2)
M∼
0,3
- GL(2, ˆZ)′ = GL(2, ˆZ)/ ± 1
(cf. §45 . . . ), de sorte qu’on trouve un homomorphisme de suites exactes
(3)
1
- {±1}
- N ∼
1,1
- M∼
0,3
- 1
?
?
1
- {±1}
- GL(2, ˆZ)
- GL(2, ˆZ)′
- 1 .
On trouve un isomorphisme canonique entre l’image inverse T ∧
1,1 de S∧
0,3 ⊆M∼
0,3 dans
N1,1, avec GL(2, Z)∧(30), induisant un homomorphisme
(4)
SL(2, Z)∧
- N ∼
1,1 ,
dont la restriction `a SL(2, Z)∧s’ins`ere dans une suite exacte canonique
(5)
1
- SL(2, Z)∧
|
{z
}
= T + ∧
1,1
-

N ∼
1,1
-
Γ∼
Q
|{z}
= Γ∼
0,3
- 1 ,
qui `a son tour s’ins`ere dans le diagramme
(6)
1
- SL(2, Z)∧
- N ∼
1,1
- Γ∼
Q
- 1
?
´epi
?
´epi
?
´epi
χ
1
- SL(2, ˆZ)
- GL(2, ˆZ)
- ˆZ∗
- 1 .
30NB T1,1 ≃GL(2, Z).


---

23
On peut ´ecrire
(7)
M∼
0,3 ≃
≃Γ∼
Q
z }| {
M∼
0,3(0) ·
≃SL(2,Z)∧′ ≃SL(2,Z)∧/±1
z}|{
S+ ∧
0,3
|
{z
}
(semi-direct)
en termes de cette d´ecomposition, et compte tenu qu’on a un homomorphisme canonique
(8)
M∼
0,3(0)
- GL(2, ˆZ)
qui remonte la restriction de (2) `a M∼
0,3(0), on trouve un isomorphisme canonique
[page 566]
(9)
N ∼
1,1 ≃N ∼
1,1(0)
| {z }
≃M∼
0,3(0) ≃Γ∼
Q
· SL(2, Z)∧.
Ainsi on a une op´eration de N ∼
1,1(0) ≃Γ∼
Q sur SL(2, Z)∧que je voudrais expliciter, en
utilisant le diagramme cart´esien
(10)
SL(2, Z)∧
- S+ ∧
0,3
-
∼
SL(2, Z)∧/ ± 1
?
cart.
?
induit
par(2)
    	
can.
SL(2, ˆZ)
- SL(2, ˆZ)/ ± 1 .
Un ´el´ement u de Γ∼
Q correspond `a un couple
(11)
(α, β) ∈
ˆπ′
0,3
|{z}
{1,τ∞}·ˆπ0,3
×ˆπ0,3
satisfaisant l’´equation des lacets
(12)
αρ(α)−1 = βρ(β)−1lν
1
(ν ∈ˆZ) ,
qui op`ere sur S+ ∧
0,3 ≃SL(2, Z)∧′ par
(13)



u(ρ)
=
int(α)ρ
=
ξρ ,
ξ
=
αρ(α)−1 ,
u(σ)
=
int(β)σ
=
ησ ,
η
=
βσ(β)−1 ,
ce qui est compatible avec l’op´eration (not´ee u) sur SL(2, ˆZ) induit par int(u), o`u u ∈
SL(2, ˆZ) est l’´el´ement d´eﬁni comme l’image de u par (8), de fa¸con pr´ecise :
(14)
˜u = iT0(µ) ,
o`u µ = χ(u) est le multiplicateur, et
(15)



iT0 : Gm
-
GL(2, ˆZ)
µ
-
 µ 0
0 1

.


---

24
On aura, de fa¸con pr´ecise,
(16)



u(ρ)
=
ξ(ρ) ,
o`u
ξ
=
αρ(α)−1
u(σ)
=
η(ρ) ,
o`u
η
=
εβρ(β)−1 ,
(31)
avec, pour m´emoire,
(17)
ε = ε2(µ) ∈{±1}



ε
=
+1
si et seulement si
µ
≡
1
(4)
ε
=
−1
si et seulement si
µ
≡
−1
(4) .
Bien entendu, SL(2, Z)∧est engendr´e aussi topologiquement par ρ et σ, et on identiﬁe
±1 au sous-groupe central de SL(2, Z), donc de SL(2, Z)∧, en ´ecrivant aussi −g pour le
produit de g ∈SL(2, Z)∧par −1. On aura donc dans SL(2, Z)∧
(18)



u(ρ)
=
int(˜α)(ρ)
=
ξρ
et u(σ)
=
ε int(˜β)(σ)
=
ησ
avec
(19)



ξ = ˜αρ(˜α)−1 ,
η = ε˜βσ(˜β)−1
ε = ε2(µ) ∈{±1} ⊆SL(2, Z)∧,
[page 567]
o`u maintenant ˜α et ˜β d´esignent des rel`evements arbitraires de α et β `a SL(2, Z)∧– ils
ne sont d´etermin´es qu’au signe pr`es, mais int(˜α), int(˜β), ξ et η sont d´etermin´es sans
ambiguit´e par u. Notons aussi
(20)
u(ε0) = εµ
0 .
Si maintenant on a un homomorphisme surjectif
(20)
N ∼
1,1
-
Ψ
G
[32]
induisant un homomorphisme
(21)
SL(2, Z)∧
-
´epi
S
|{z}
= Im Ψ
⊆G ,
les images de ρ, σ dans S (not´ees par les mˆemes lettres) satisferont
(22)
ρ6 = σ4 = 1 ,
ρ3 = σ2 ,
et par suite [ρ3, σ] = [σ2, ρ] = 1, i.e. ρ3, σ2 sont centraux (33) ,
31Les soulign´es d´esignent des ´el´ements dans GL(2, ˆZ) – α et β ne sont d´etermin´es qu’au signe pr`es,
mais ξ, η sans ambiguit´e.
32[Deux fois (20).]


---

25
et on peut, pour u ∈N ∼
1,1(0), correspondant `a des ´el´ements ˜α, ˜β de SL(2, Z)∧(d´etermin´es
modulo signe), d’o`u ξ, η, essayer de trouver un automorphisme uS de S, satisfaisant les
relations idoines
(23)
uS(ρS) = ξSρS ,
uS(σS) = ηSσS ,
et faire joujou avec ˜α et ˜β. Mais on est oblig´e, comme on n’a pas n´ecessairement ˜α ∈
SL(2, Z)∧, seulement ˜α ∈GL(2, Z)∧, de faire intervenir l’´el´ement τ∞de GL(2, Z)∧, et
l’action de son image τ dans G sur S. On aura, en posant maintenant
(24)
ε0 S
=
σSρS ,
ε1 S
=
ρSσS
=
σS(ε0 S)
=
ρS(ε0 S)
=
−σ−1
S ρS
=
−ρSσ−1
S
(34) ,
des relations
(25)
τ(σ) = σ−1 ,
τ(ρ) = σ(ρ)−1 ,
(35)
qui impliquent, via (24) et (22),
(26)
τ(ε0) = ε−1
0
,
τ(ε1) = ε−1
1
,
et on introduit le groupe
(27)
S
def
= {1, τ} · S
|
{z
}
semi-direct
,
o`u {1, τ} op`ere sur S par les formules (25). Ceci dit, on est en mesure de paraphraser
des constructions d´ej`a faites par ailleurs.
[page 568]
IV)
1◦) Soit donc S un groupe proﬁni, muni de g´en´erateurs ρ, σ ∈S satisfaisant les relations
(1)
ρ6 = σ4 = 1 ,
ρ3 = σ2 (
def
= ‘−1’)(36)
— un cas particuli`erement int´eressant ´etant celui o`u ρ3 = σ2 = 1, auquel n´eanmoins je
ne voudrais me limiter. Soit τ un automorphisme de S satisfaisant
(2)
τ(σ) = σ−1 = −σ ,
τ(ρ) = σ(ρ−1)
(37)
(ce qui signiﬁe que τ∞‘passe au quotient’ en automorphisme τ de S), ce qui implique
(3)
τ 2 = 1
(4)
τ(ε0) = ε−1
0
,
τ(ε1) = ε−1
1
,
33Donc dans S il y a un ´el´ement central canonique involutif, not´e −1 . . .
34Ce qui n’est pas la convention habituelle jusqu’`a pr´esent . . .
35Je laisse tomber les indices S.
36Ceci signiﬁe simplement qu’on se donne un homomorphisme surjectif SL(2, Z)∧
- S
37Introduire tout de suite l’´el´ement ´equivalent τ ′ = σ−1τ satisfaisant τ ′(ρ) = ρ−1, τ ′(σ) = σ−1 (τ ′(ε0) =
ε−1
1 , τ ′(ε1) = ε−1
0 ).


---

26
o`u
(5)
ε0 = σρ = −σ−1ρ ,
ε1 = ρσ = σ(ε0) = σ−1(ε0) = ρ(ε0)
(38) .
Posons
(5)
S′ = {1, τ} · S
[39] ,
donc on a
(6)
1
- S
- S′
- {1, τ}
- 1 .
Soit
(7)
Bρ,σ =









(u, µ)

u(ε0) = εµ
0
u(σ) conjugu´e dans S `a σµ
u(ρ) conjugu´e dans S `a ρµ









⊆Aut(S) × ˆZ∗,
qui est ´evidemment un sous-groupe. La troisi`eme condition signiﬁe d’ailleurs, puisque
ρ6 = 1, i.e. ρµ ne d´epend que de l’image de µ dans (Z/6Z)∗≃(Z/2Z)∗× (Z/3Z)∗≃
(Z/3Z)∗≃{±1}, donc
(8)
ρµ = ρε3(µ) ,
que pour ε3(µ) = 1, u(µ) est conjugu´e `a ρ dans S, et pour ε3(µ) = −1, il est conjugu´e `a
ρ−1 dans S, ou encore `a ρ par un ´el´ement de S′−, i.e. un ´el´ement de la forme α1τ∞, avec
α1 ∈S (puisque τ∞(ρ) = σ(ρ−1) justement . . . ). On voit de mˆeme qu’on a
(9)
σµ = σε2(µ) = ε2(µ)σ =



= σ
si µ ≡1 (4)
= σ−1 = −σ
si µ ≡−1 (4)
.
Ainsi :
Proposition. Pour que (u, µ) ∈Aut(S) × ˆZ soit dans Bρ,σ, il faut et il suﬃt qu’il existe
α ∈S′, β ∈S tels qu’on ait
[page 569]
(10)
u(ρ) = int(α)(ρ) ,
u(σ) = ε2(µ)
| {z }
= ε
int(β)(σ) ,
et enﬁn
(11)
u(ε0) = εµ
0 ,
o`u de plus on a
(12)
α ∈S
si et seulement si
µ ≡1 (3)
(40) .
38On fera attention au signe −, alors que pr´ec´edemment on supposait souvent ε0 = σ−1ρ . . .
39[Deux fois (5).]


---

27
On notera que (u, µ) est uniquement d´etermin´e par µ et la connaissance de α et de β, et
mˆeme seulement par µ et
(13)
ξ = αρ(α)−1 ,
η = ε2(µ)βσ(β)−1 ,
puisqu’on aura alors u par
(14)
u(ρ) = ξρ ,
u(σ) = ησ .
D’ailleurs, dans le cas o`u
(15)
ˆZ
-
S
n
-
εn
0
est injectif, µ est d´etermin´e en fonction de u comme multiplicateur de l’action de u sur
LS
0 ⊆S, image de (15), donc (u, µ) est d´etermin´e par u, donc par (α, β, ε = ε2(µ)).
D’ailleurs, si S est assez gros pour s’envoyer dans SL(2, ˆZ)′ (de fa¸con `a envoyer (ρ, τ)
sur les ´el´ements habituels), on a vu que α `a lui tout seul d´etermine d´ej`a µ, donc ε, donc
l’´el´ement de Bρ,σ est d´etermin´e `a l’aide de α, β seulement.
Mais quelles conditions doivent satisfaire (α, β, µ) pour d´eterminer un ´el´ement de Bρ,σ ?
Tout d’abord, il faut qu’il existe bien un automorphisme u (n´ecessairement unique) satis-
faisant (14) – c’est une condition sur ξ, η seuls. Il faut ensuite exprimer (11). Introduisant
(∗)
ε′
0 = σ−1ρ = −ε0 ,
d’o`u
ε′
0
µ = (−1)µεµ
0 = −εµ
0
(car µ ≡1 (2))
u(ε′
0) = −u(ε0)
(car u(−1) = −1, cf. ci-dessous) ,
donc la relation (11) ´equivaut aussi `a
(∗∗)
u(ε′
0) = ε′
0
µ ,
qui, par le sempiternel calcul, s’´ecrit ainsi :
[page 570]
η−1ξ = ε′
1
2ν ,
o`u ν = (µ −1)/2 , ε′
1 = −ε1 = ρσ−1 .
Or on a ε′
1
2ν = (−1)2νε2ν
1 = ε2ν
1
= lν
1, donc la relation des lacets garde la forme
(16)
ξ = ηlν
1 ,
o`u ν = (µ −1)/2 .
On doit encore prouver le
Lemme. Soit u un automorphisme de S tel que u(σ) soit conjugu´e dans S `a σ ou `a σ−1,
alors
(17)
u(−1) = −1 .
40I.e. α ≡τ.


---

28
On aura en eﬀet u(σ) = int(α)(σ′), o`u σ′ = σ ou = σ−1, donc u(σ2) = int(α)(σ′2) =
int(α)(−1) = −1, OK.
Reste `a exprimer enﬁn que u(ρ) = int(α)(ρ) est conjugu´e `a ρµ, et u(σ) `a σµ, et cela est
automatique pour σ, puisque u(σ) = int(β)(ε2(µ)σ) = int(β)(σµ) (par (19)), et pour ρ
cela signiﬁe que l’on a
(17) α ≡τ ν3(µ) (S)
(41) ,
o`u ν3(µ) ∈Z/2 est l’expression additive de ε3(µ) . . .
[42] .
Donc on trouve :
Corollaire. L’application
(18)
Bρ,σ
-
S
×
S
×
ˆZ∗
(u, µ)
-
([u, ρ]
,
[u, σ]
,
µ)
est injective, et elle a comme image l’ensemble Σeﬀ
ρ,σ des triples (ξ, η, µ) satisfaisant les
conditions suivantes :
1◦) ξρ conjugu´e `a ρµ = ρε3(µ) dans S.
2◦) ξσ [plut^ot ησ] conjugu´e `a σµ = σε2(µ) dans S.
3◦) On a la relation des lacets (16).
4◦) Il existe un automorphisme u de S, satisfaisant u(ρ) = ξρ, u(σ) = ησ.
La conjonction des conditions 1◦), 2◦), 3◦) est ´equivalente aussi `a celle-ci :
(A) Il existe (α, β) ∈S′ × S avec α ∈S si et seulement si µ ≡1 (3), i.e. α mod S =
τ ν3(µ), et tel qu’on ait ξ = αρ(α)−1, η = ε2(µ).
Consid´erons l’homomorphisme de groupes
(19)
L0
-
iL0,β
Bρ,σ
l
-
(int(l), 1) ,
il est injectif si on suppose toujours
(20)
L0 ∩Centr(S) = {1} ,
son image est invariante, car on a
(21)
u(iL0,β(l)) = iL0,β(u(l)) = iL0,β(lµ) ,
o`u µ est le multiplicateur. On pose
(22)
Υρ,σ = Bρ,σ/ Im L0 ,
41qu’on ´ecrit aussi τ ν3(µ)α ∈S.
42[Deux fois (17).]


---

29
d’o`u [une] suite exacte canonique
(23)
1
- L0
- Bρ,σ
- Υρ,σ
- 1 ,
et on a un homomorphisme (d´eduit de (u, µ)
- µ en factorisant par Υρ,σ)
(24)
Υρ,σ
-
χΥ
ˆZ∗,
dont le noyau est not´e Υ+
ρ,σ :
(25)
1
- Υ+
ρ,σ
- Υρ,σ
- ˆZ∗
- 1 .
[page 571]
Consid´erons les homomorphismes compos´es
(26)
Υρ,σ
-
χΥ
ˆZ∗
-
ε2
±1
Υρ,σ
-
χΥ
ˆZ∗
-
ε3
±1
et surtout
(27)



Υ′
ρ,σ, Υ′′
ρ,σ ⊆Υρ,σ
sous-groupes d’indice 2, d´eﬁnis par
Υ′
ρ,σ = Ker(ε3 ◦χΥ) ,
Υ′′
ρ,σ = Ker(ε2 ◦χΥ) .
Soit maintenant
(28)
Gρ,σ = ( Bρ,σ · S
| {z }
semi-direct, isomorphique `a S0Gρ,σ
)/L0 ,
o`u
(29)
L0
-
iL0,B
Bρ,σ
·
Gρ,σ
l
-
int(l)
·
l−1 ,
dont l’image est invariante. On a un diagramme commutatif
(30)
L0

*
HHHH
j
S
Bρ,σ
HHHH
j

* Gρ,σ ,
o`u Ker(S
- Gρ,σ) ≃Ker(L0
- Bρ,σ) ≃L0 ∩Centr(S) est trivial si et seulement si on
a (20), ce qu’on va supposer par la suite. On a un homomorphisme de suites exactes
(31)
1
- L0
- Bρ,σ
-
δB
Υρ,σ
- 1
?
  1
- S
- Gρ,σ
-
δG
Υρ,σ
@
@
@@
R
χG
?
χΥ
ˆZ .






---

30
Posons
(32)



Zρ
=
CentrGρ,σ(ρ)
Zσ
=
CentrGρ,σ(σ) ,
alors les homomorphismes induits par δG
(33)
Zρ
-
δρ
Υρ,σ ,
Zσ
-
δσ
Υρ,σ
ont des images qui contiennent Υ′
ρ,σ et Υ′′
ρ,σ respectivement.
[page 572]
Proposition.
1◦) L’image δρ(Zρ) contient Υ′
ρ,σ, et est r´eduite `a Υ′
ρ,σ si et seulement si ρ et ρ−1 non
conjugu´es dans S – donc elle est ´egale `a Υρ,σ ; i.e. δρ : Zρ
- Υρ,σ ´epimorphique si
et seulement si ρ et ρ−1 sont conjugu´es dans S.
2◦) L’image δσ(Zσ) contient Υ′′
ρ,σ, et elle est r´eduite `a Υ′′
ρ,σ si et seulement si σ et
σ−1 = −σ non conjugu´es dans S – donc elle est ´egale `a Υρ,σ ; i.e. δσ : Zσ
- Υρ,σ
´epimorphique si et seulement si σ et σ−1 = −σ sont conjugu´es dans S.
Corollaire 1. Si S contient comme quotient SL(2, Z/3Z)′, avec ρ =
 0 1
−1 1

, σ =
 0 −1
1
0

(modulo ±1), alors l’image de δρ est Υ′
ρ,σ.
En eﬀet, on voit que ρ et ±ρ−1 ne sont conjugu´es dans S, car ils ne le sont pas dans
SL(2, Z/3Z)′. V´eriﬁons le : ρ et −ρ−1 ont d´ej`a des traces distinctes 1 et −1 dans Z/3Z,
ils ne sont pas conjugu´es. On a ( τσ
|{z}
τ ′∞
)(ρ) = ρ−1, donc les ´el´ements de GL(2, Z/3Z) qui
conjuguent ρ en ρ−1 sont de la forme fτ ′
∞, avec f = cρ + d, on veut det(fτ ′
∞) = 1, i.e.
det(f) = −1 (car det(τ ′
∞) = −1), i.e. c2 + cd + d2 = −1, impossible.
Corollaire 2. Si σ2 = 1, alors Zσ
- Υρ,σ est surjectif. Si par contre S contient comme
quotient SL(2, Z/4Z) (sans
′ !), avec ρ, σ comme d’habitude, alors Im(δσ) = Υ′′
ρ,σ.
Il faut voir que σ et σ−1 = −σ non conjugu´es dans SL(2, Z/4Z), en utilisant que τ∞(σ) =
σ−1, donc les ´el´ements de GL(2, Z/4Z) qui conjuguent σ en σ−1 sont les g = fτ∞avec
f = tσ + u, et dire que det(g) = 1 signiﬁe det(f) = −1, i.e. t2 + u2 = −1, impossible.
[page 573]
Notons que d’apr`es (2), (4), on a
(35)
τB
def
= (τ, −1) ∈Bρ,σ
[43] ,
et ´evidemment τB ̸∈L0 = Bρ,σ ∩S. Donc on a un plongement
(36)









S′ = {1, τ} · S
-

Gρ,σ
τ
-
τB
g
-
g
si g ∈S
(44) ,
43[(34) n’existe pas.]


---

31
donc l’automorphisme τ de S sera consid´er´e comme induit par int(τB), o`u τB est consid´er´e
lui-mˆeme comme un ´el´ement de Gρ,σ. En relation avec l’´egalit´e
τB(σ) = σ−1 ( = −σ ) ,
qui montre que τB normalise le sous-groupe Lσ engendr´e par σ (isomorphe `a un quotient
de Z/4Z), donc normalise Zσ = CentrGρ,σ(Lσ), introduisons
(37)
Nσ = {1, τB} · Zσ
|
{z
}
semi-direct
,
et l’homomorphisme canonique
(38)









Nσ
-
iσ
Gρ,σ
τB
-
τB
x
-
x
si x ∈Zσ .
L’image de cet homomorphisme n’est autre que le normalisateur de σ dans Gρ,σ, car un
g ∈Gρ,σ qui normalise Lσ doit transformer σ en un g´en´erateur de Lσ, i.e. en σ ou σ−1 ;
dans le premier cas on aura g ∈Zσ, dans le deuxi`eme g(σ) = τB(σ), i.e. τ −1
B g ∈Zσ, i.e.
g ∈τBZσ. L’homomorphisme (38) est injectif si et seulement si τB ̸∈Zσ, i.e. σ ̸= σ−1, i.e.
σ2 ̸= 1, i.e. “ −1” ̸= 1.
Puisqu’on y est, proﬁtons de la formule
τB(ρ) = σ(ρ−1)
pour introduire
(39)
τ ′ = σ−1τ ∈S′ ⊆Gρ,σ
(qui correspond `a l’´el´ement
(40)
τ ′
∞= σ−1
∞τ∞= −σ∞τ∞=
 0 1
1 0

∈GL(2, Z)
|
{z
}
= T1,1
)
(45) ,
on aura donc
(40)
τ ′2 = 1 ,
τ ′(ρ) = ρ−1
[46] .
Ainsi τ ′ normalise le sous-groupe Lρ (isomorphe `a un quotient de Z/6Z) engendr´e par ρ,
donc il normalise le centralisateur Zρ de Lρ, et on peut construire
(41)
Nρ
def
= {1, τ ′} · Zρ
|
{z
}
(semi-direct)
,
44NB S′ est un quotient de GL(2, Z)∧, et τ y correspond `a l’image de l’´el´ement τ∞=
 −1 0
0 1

de
GL(2, Z)−.
45NB On a en mˆeme temps τ ′(σ) = σ−1, donc on peut consid´erer τ ′ comme ´el´ement de Nσ, et on a
Nσ = {1, τ ′} · Zσ (produit semi-direct).
46[Deux fois (40).]


---

32
et un homomorphisme canonique
(42)









Nρ
-
iρ
Gρ,σ
τ ′
-
τ ′
x
-
x
pour x ∈Zρ .
L’image de cet homomorphisme est le normalisateur de Lρ dans Gρ,σ – on le voit comme
tantˆot pour iσ, en notant que ρ, ρ−1 sont les seuls g´en´erateurs de Lρ. L’homomorphisme
iρ est injectif si et seulement si τ ′ ̸∈Zρ, i.e. ρ ̸= ρ−1, i.e. ρ2 ̸= 1, i.e. ρ ̸= −1 (NB ρ = −1
implique que ρ commute `a σ, et que S est un quotient de Z/12Z, avec ρ correspondant
`a 2 et σ `a 3, mais ici 2ρ = 0, donc S est un quotient de Z/4Z avec ρ correspondant `a 2,
σ `a 3 = −1 . . . ).
‘On a fait ce qu’il fallait’ pour avoir des ´epimorphismes
(43)



Nρ
-
δρ = δG◦iρ
Υρ,σ
Nσ
-
δσ = δG◦iσ
Υρ,σ .
[page 574]
Soit
(44)
SGρ,σ
=







(α, β, µ)

α ≡τ ν3(µ) mod S, i.e. χ(α) = ε3(µ),
αρ(α)−1
|
{z
}
= ξ
= ε2(µ)βσ(β)−1
|
{z
}
= η
lν
1, o`u ν = (µ −1)/2 (l1 = ε2
1)







⊆
S′ × S × ˆZ∗,
d’o`u
(45)





















SGρ,σ
-
Σρ,σ
def
=









(ξ, η, µ)

ξρ conjugu´e dans S `a ρµ
ξσ conjugu´e dans S `a σµ
ξ = ηlν
1 , o`u ν = (µ −1)/2









⊆S × S × ˆZ∗
(α, β, µ)
-
(
= [α,ρ]
z
}|
{
αρ(α)−1, ε2(µ),
= [β,σ]
z
}|
{
βρ(β)−1, µ) .
On d´esigne par Geﬀ
ρ,σ l’image inverse de Σeﬀ
ρ,σ (cf. cor. p. 570), isomorphe `a Bρ,σ.
Par
construction, on trouve donc une application surjective
(46)
SGeﬀ
ρ,σ
-
´epi Σeﬀ
ρ,σ .
On consid`ere SGρ,σ comme contenu dans un ensemble plus gros
(47)
Gρ,σ =







(α, β, µ)

χ(α) ≡ε3(µ)χ(β)
αρ(α)−1
|
{z
}
= α(ρ)ρ−1 = ξ
=
ε2(µ)βσ(β)−1
|
{z
}
= ε2(µ)β(σ)σ−1 = η
lν
1







⊆Gρ,σ × Gρ,σ × ˆZ∗,


---

33
de sorte que l’on aura
(48)
SGρ,σ
=
Gρ,σ ∩(S′ × S × ˆZ∗)
=


(α, β, µ)

δσ(β)
=
1
δρ(ατ ν3(µ))
=
1


,
et on a encore une application canonique
(49)



Gρ,σ
-
Σρ,σ
(α, β, µ)
-
([α, ρ], ε2(µ)[β, σ], µ) .
On note Geﬀ
ρ,σ l’image inverse de Σeﬀ
ρ,σ, et on trouve
(50)
SGeﬀ
ρ,σ
=
Geﬀ
ρ,σ ∩(S′ × S × ˆZ∗)
=


(α, β, µ) ∈Geﬀ
ρ,σ

δσ(β)
=
1
δρ(ατ ′ν3(µ))
=
1


.
Or on a une section de
(51)
Geﬀ
ρ,σ
- Σeﬀ
ρ,σ
6
≀
@
@
@
@
I
section
Bρ,σ
u
6
(ξ = [u, ρ], η = [u, σ], µ = χB(u))
don´ee par
(52)
u
- (u, uτ ′ν2(µ), µ = χB(u)) ,
puisqu’on aura (posant ε = ε2(µ) = (−1)ν2)
[u, ρ] = uρ(u)−1 = ξ
ε[uτ ′
= ν2
z}|{
ν2(µ), σ] = εuτ ′ν2σ(uτ ν2)−1 = εu(τ ′ν2σ(τ ν2)−1
|
{z
}
= ε
)σ(u)−1 = uσ(u)−1 = η ,
OK. Donc l’ensemble Gρ,σ(u, µ) = ε des (α, β, µ) au dessus d’un (ξ, η, µ) = ([u, ρ], [u, σ], µ =
χB(u)) sera exactement
[page 575]
(53)
Gρ,σ(u, µ) = {
(
= α
z}|{
ua−1
0 ,
= β
z
}|
{
uτ ′ν2b−1
0 , µ)
|
{z
}
= (ua−1
0 , ub−1, µ) avec b = b0τ ′ν2
| a0 ∈Zρ, b0 ∈Zσ, ν2 = ν2(µ)} ,
qu’on ´ecrit aussi
(54)
Gρ,σ(u, µ) = {(ua−1
0
|{z}
= α
, uiσ(b)
| {z }
= β
, µ) | a0 ∈Zρ,
b ∈Nσ
| {z }
(cf. (37), (38))
, εσ(b) = ε2(µ) } ,


---

34
o`u εσ : Nσ
- {±1} est d´eﬁni sur (37) comme l’homomorphisme canonique s’ins´erant
dans la suite exacte canonique
(55)
1
- Zσ
- Nσ
-
εσ
{±1}
| {z }
≃{1,τ ′}
- 1 .
Si on cherche l’ensemble des ´el´ements de SGeﬀ
ρ,σ au dessus de (ξ, η, µ), il faut de plus imposer
les conditions
(56)
ua−1
0 τ ′ν3(µ) ∈S ,
uiσ(b) ∈S ,
i.e.
δG(ua−1
0 τ ′ν3) = 1 ,
δG(uiσ(b)) = 1 ,
soit encore
(57)
δG(u) = δσ(b)
|{z}
cf. (43)
=
δρ
|{z}
cf. (43)
(τ ′ν3 · a0) .
Posons donc
a = τ ′ν3 · a0
dans Nρ
(donc a0 = τ ′ν3a) ,
on voit que
(54)
Gρ,σ(u, µ) =









(ua−1τ ′ν3, ub−1, µ)

a ∈Nρ, b ∈Nσ
tels que
ερ(a) = ε3(µ), εσ(b) = ε2(µ),
δρ(a) = δσ(b) = δG(u)









[47] .
Introduisons donc le groupe
(55)
Mρ,σ[0] = Bρ,σ ×Υρ,σ Nρ ×Υρ,σ Nσ
et les homomorphismes compos´es
(56)



Mρ,σ[0]
-
Nρ
-
ερ
{±1}
Mρ,σ[0]
-
Nσ
-
εσ
{±1}
(encore not´es ερ, εσ par abus de notation), et
(57)
Mρ,σ[0]
-
δSM Υρ,σ
-
χΥ
ˆZ∗,
soit χSM (ou simplement χ), consid´erons
(58)
Mρ,σ[0]
-
ερ,σ = (εσ,ερ) {±1} × {±1}
et
(59)
Mρ,σ[0]
-
ε2,3
{±1}
×
{±1}
x
-
(ε2(χ(x))
,
ε3(χ(x))) ,
47[Saut dans la num´erotation.]


---

35
et consid´erons le sous-groupe de co¨ıncidence des deux homomorphismes pr´ec´edents
(60)
Meﬀ
ρ,σ[0]
def
=
{x ∈S0Mρ,σ | ερ,σ(x) = ε2,3(x)}
=


( u
|{z}
∈Bρ,σ
,
a
|{z}
∈Nρ
,
b
|{z}
∈Zσ
)

δB(u) = δρ(a) = δσ(b),
soit ∆∈Υρ,σ
ερ(a) = ε3(χΥ(∆)), εσ(b) = ε2(χΥ(∆))


.
On a une application naturelle
(61)
Meﬀ
ρ,σ[0]
-
S′ × S × ˆZ∗
(u, a, b)
-
(α, β, µ) ,
avec
α
=
ua−1τ ′νρ(a)
β
=
ub−1
µ
=
χB(u) = χρ(a) = χσ(b) .
(48, 49) ,
et on a fait ce qu’il fallait pour que celle-ci soit injective et ait comme image SGeﬀ
ρ,σ, donc
induise une bijection
(62)
Meﬀ
ρ,σ[0]
-
∼
SGeﬀ
ρ,σ .
Remarque. En fait, les formules pour (61) d´eﬁnissent mˆeme une application
(62)
Mρ,σ[0]
- S′ × S × ˆZ∗
[50] ,
et pour un (u, a, b) ∈Mρ,σ[0], son image (α, β, µ) est li´ee `a u ∈Bρ,σ par les formules
[page 576]
(63)



u(ρ)
=
int(α)(ρ)
(S-conjugu´e `a ρε′, o`u ε′ = ερ(a))
u(σ)
=
ε int(β)(σ)
(S-conjugu´e `a σε, o`u ε′ = εσ(b))
(mais sans qu’on ait n´ecessairement ε′ = ε3(µ), ε = ε2(µ)).
Ceci sugg`ere une d´eﬁnition d’un groupe un peu plus gros que Bρ,σ, dans lequel Bρ,σ sera
inclus comme sous-groupe d’indice 1, 2 ou 4 – et qui aura l’avantage, dans les ‘bons cas’,
d’ˆetre le groupe des points ad´eliques d’un sch´ema en groupes convenable sur Z. D’autre
part, pour ´eliminer le signe ε dans (63) (qui est pr´esent mˆeme si (u, a, b) ∈Meﬀ
ρ,σ[0]), j’ai
envie de remplacer β par
(64)
β′ = τ ′νβ
(o`u ν ∈Z/2Z tel que (−1)ν = ε) .
De sorte qu’on aura
(65)
[u, σ] = int(β′)(σ) ,
i.e. [u, σ] = β′σ(β′)−1 .
48NB On a pos´e νρ(a) ∈Z/2 tel que (−1)νρ(a) = ερ(a).
49NB On a identiﬁ´e a ∈Nρ, b ∈Nσ avec leurs images iρ(a), iσ(b) dans Gρ,σ.
50[Deux fois (62).]


---

36
Ceci est li´e `a la convention qu’un u ∈Γ∼
Q, que nous rep´erions par le couple (α, β) ∈
π∧
0,3
′ × π∧
0,3, sera d´esormais rep´er´e par ce couple (α, β′) ∈π∧
0,3 × π∧
0,3
′, avec
(66)
χ(α) = ε3(µ) ,
χ(β′) = ε2(µ)
(o`u µ = χ(u) est le multiplicateur) ,
ce qui pour l’op´eration de u sur
S+ ∧
0,3
= SL(2, Z)∧′ = SL(2, Z)∧/ ± 1
e
ne change pas essentiellement les formules pertinentes
(67)



u(ρ) = int(α)ρ ,
u(σ) = int(β)σ ( = int(β′)σ )
αρ(α)−1 = βσ(β)−1lν
1 ( = β′σ(β′)−1lν
1) ,
ν = µ−1
2
,
mais pour l’op´eration dans
T + ∧
1,1
≃SL(2, Z)∧
lui-mˆeme
donne des formules plus simples, savoir, au lieu de
(68)



u(ρ) = int(α)ρ ,
u(σ) = ε · int(β)σ
αρ(α)−1 = εβσ(β)−1lν
1 ,
les formules plus sympathiques
(69)



u(ρ) = int(α)ρ ,
u(σ) = int(β′)σ
αρ(α)−1 = β′σ(β′)−1lν
1 ,
o`u le signe ε = ε2(µ) a disparu. Il apparaˆıt dans les formules
(70)
χ(α) = ε3(µ) ,
χ(β′) = ε2(µ) .
Il me semble en avoir vu assez pour pouvoir reprendre ‘`a main lev´ee’ les constructions
pr´ec´edentes et les achever, avec des notations plus ad´equates.
Le groupe S′, quotient de T ∧
1,1 ≃GL(2, Z)∧, prend d’ailleurs une importance croissante
dans nos calculs, c’est lui qui m´erite la notation simple S, le sous-groupe ferm´e engendr´e
par ρ, σ devenant S+ – il correspond `a T + ∧
1,1
≃SL(2, Z)∧. On supposera simplement que
τ ̸∈S+ (τ ´etant l’image de τ∞), ou ce qui revient au mˆeme, que
(71)
τ ′ ̸∈S+ .
[page 577]
C’est ﬁnalement cet ´el´ement, qui normalise `a la fois Lρ et Lσ via les formules remarquables
(∗)
τ ′(ρ) = ρ−1 ,
τ ′(σ) = σ−1 ,
qui prend le pas sur τ, qui satisfait `a
(∗∗)
τ(ε0) = ε−1
0
,
τ(ε1) = ε−1
1
,
et mˆeme τ(σ) = σ−1


---

37
(ce qui est ´evidemment tr`es vertueux !), mais dont l’action sur ρ
τ(ρ) = σ(ρ−1)
est moins commode (51).
V) Donn´ees pr´eliminaires.
1◦) Soit donc S un groupe proﬁni, muni d’un homomorphisme surjectif
(1)
T ∧
1,1 ≃GL(2, Z)∧
-
´epi S ,
ce que nous exprimerons par la donn´ee de trois g´en´erateurs topologiques ρ, σ, τ ′ ∈S,
satisfaisant
(2)
ρ6 = σ4 = τ ′2 = 1 ,
ρ3 = σ2
|
{z
}
(not´e −1)
,
τ ′ρτ ′−1 = ρ−1 ,
τ ′στ ′−1 = σ−1 .
On d´esigne par S+ le sous-groupe ferm´e engendr´e par ρ, σ, qui est donc l’image de
T + ∧
1,1
≃SL(2, Z)∧,
et on suppose que S+ ̸= S, donc
(3)
S ≃{1, τ ′} · S+
|
{z
}
(semi-direct)
,
et on a une suite exacte canonique
(4)
1
- S+
- S
-
εS
{±1}
- 1 .
On d´esigne aussi par νS le compos´e
(5)
S
-
εS
{±1}  ∼
Z/2Z .
ν

(−1)ν
z
νS
De fa¸con g´en´erale, on d´esigne (par abus de langage) par une mˆeme lettre des ´el´ements de
GL(2, Z) – tels ε0, ε1, τ = τ∞, τ ′ = τ ′
∞, σ = σ∞, ρ = ρ∞etc. – et leurs images dans S.
2◦) Les groupes Zρ,σ, Υρ,σ.
Soit
(6)
Zρ,σ
def
=









(u, µ, ε, ε′)

u(ε0) = εµ
0
u(ρ) conjugu´e dans S+ `a ρε′
u(σ) conjugu´e dans S+ `a σε









⊆
Aut(S+) × ˆZ∗× {±1} × {±1} .
51N´eanmoins, τ ′ a sur τ le d´esavantage s´erieux de ne pas ˆetre ´el´ement du groupe π′∧
0,3 = {1, τ} · π∧
0,3,
o`u on a la relation de rigidit´e π′∧
0,3
σ = π′∧
0,3
ρ = {1} [o`u U σ est le centralisateur de σ dans le
groupe U] – alors que dans {1, τ ′}·π∧
0,3, le centralisateur de σ n’est pas r´eduit `a 1, mais est ´egal `a {1, τ ′}.
De plus, τ ′ a le d´esavantage de ne pas ˆetre dans M! ∼
0,3 . . .


---

38
C’est un sous-groupe du groupe produit. Posons
(7)



Lρ
=
sous-groupe de S engendr´e par ρ
Lσ
=
sous-groupe de S engendr´e par σ ,
de sorte qu’on a des ´epimorphismes
(8)



Z/6Z
-
´epi
Lρ ,
n
-
ρn ,
Z/4Z
-
Lσ ,
n
-
σn ,
[page 578]
et un diagramme commutatif d’homomorphismes
(9)
{±1}

*
HHHH
j
Lρ
Lσ
HHHH
j

* S+
– si S est ‘assez gros’, on aura d’ailleurs que {±1}
-

S+, i.e. “ −1” ̸= 1 dans S+, et
mˆeme
Lρ ∩Lσ = {±1} .
Les conditions (6) impliquent donc que
(10)



u(Lρ)
S+-conjugu´e `a Lρ
u(Lσ)
S+-conjugu´e `a Lσ .
Si S+ est ‘assez gros’ pour que ρ et ρ−1, σ et σ−1 n’y soient pas conjugu´es, alors un
´el´ement (u, µ, ε, ε′) de Zρ,σ est connu par la seule connaissance de (u, µ). Si d’autre part
l’homomorphisme
(11)
ˆZ
-
S+
n
-
εn
0
est injectif, alors µ est connu quand on connaˆıt u. Donc si S+ est assez gros pour satisfaire
aux trois conditions envisag´es, p.ex. pour qu’on ait un ‘homomorphisme modulaire’
(12)
S
- GL(2, ˆZ)
(transformant ρ, σ, τ ′ en les ´el´ements de mˆeme nom), alors un ´el´ement de Zρ,σ est connu
par la seule connaissance de u ∈Aut(S+).
On a un homomorphisme
(13)
L0
-
iL0,Z
Zρ,σ
l
-
(int(l), 1, 1, 1) ,


---

39
dont l’image est invariante, le noyau n’´etant autre que L0 ∩Cent(S+). Notons que l’on a
(14)
L0 ∩Cent(S+) ⊆L0 ∩CentS+(ρ) ⊆L0 ∩L1 .
Car si l ∈L0 et ρ commutent, i.e. si l = ρ(l), comme ρ(L0) = L1, on aura l ∈L1. Donc
si L0 ∩L1 = {1}, ce qui est le cas si (12) existe, et mˆeme s’il existe seulement
(12′)
S
- GL(2, ˆZ)′
modulaire ,
alors on aura
(15)
L0 ∩Cent(S+) = {1} ,
et (13) sera injectif. Nous allons le supposer, pour ﬁxer les id´ees.
On pose
(16)
Υρ,σ = Zρ,σ/ Im L0 ,
de sorte qu’on aura une suite exacte canonique
(17)
1
- L0
-
iL0,Z Zρ,σ
-
δZ
Υρ,σ
- 1 .
Les homomorphismes canoniques de projection (u, µ, ε, ε′)
- µ, ε, ε′ se factorisent par
Υρ,σ et fournissent des homomorphismes canoniques
[page 579]
(18)









Υρ,σ
-
χΥ
ˆZ∗
Υρ,σ
-
εΥ
{±1}
Υρ,σ
-
ε′
Υ
{±1}
,
soit Υρ,σ
-
(χΥ,εΥ,ε′
Υ)
ˆZ∗× {±1} × {±1} ,
les compos´es de ceux-ci avec Zρ,σ
- Υρ,σ sont not´es
(19)
χZ = χΥ ◦δZ ,
εZ = εΥ ◦δZ ,
ε′
Z = ε′
Υ ◦δZ ,
de sorte que
(20)
χZ(u, µ, ε, ε′) = µ ,
εZ(u, µ, ε, ε′) = ε ,
ε′
Z(u, µ, ε, ε′) = ε′ .
On aurait envie de d´esigner par Υ0
ρ,σ le noyau de (εΥ, ε′
Υ), par Υ+
ρ,σ celui de χΥ, par Υ0 +
ρ,σ
leur intersection, et d’introduire par les notations Z0
ρ,σ, Z+
ρ,σ, Z0 +
ρ,σ leurs images inverses
dans Zρ,σ, i.e. les noyaux respectivement de (εZ, ε′
Z), de χZ et de (χZ, εZ, ε′
Z).
3◦) Les groupes S0Gρ,σ, Gρ,σ.
On a un homomorphisme tautologique
(21)
Zρ,σ
-
Aut(S+)
(u, µ, ε, ε′)
-
u ,


---

40
donc Zρ,σ op`ere sur S+, et on peut donc consid´erer le produit semi-direct
(22)
S0Gρ,σ = Zρ,σ · S+
|
{z
}
(semi-direct)
.
On a un homomorphisme
(23)
L0
-
iL0,SG S0Gρ,σ = Zρ,σ · S+
l
-
iL0,Z(l) · l−1 ,
dont l’image est encore invariante. On pose
(24)
Gρ,σ = S0Gρ,σ
| {z }
Zρ,σ·S+
/ Im L0 ,
de sorte qu’on aura une suite exacte
(25)
1
- L0
-
iL0,SG S0Gρ,σ
- Gρ,σ
- 1 ,
et un diagramme commutatif d’homomorphismes
(26)
L0

*

iL0,Z
HHHH
j

iL0,S
Zρ,σ
S+
HHHH
j
iZ

*
iS+
Gρ,σ
(a priori Ker(S+
- Gρ,σ) ≃Ker(L0
- Zρ,σ) = L0 ∩Cent(S+), mais par hypoth`ese (15)
il est r´eduit `a {1}), s’ins´erant dans un diagramme commutatif de suites exactes
(27)
1
- L0
-
iL0,Z
Zρ,σ
-
δZ
Υρ,σ
- 1
?
  iL0,S
?
  1
- S+
-
iS+
Gρ,σ
-
δG
Υρ,σ
- 1 .
On posera
(28)
χG = χΥ ◦δG ,
εG = εΥ ◦δG ,
[ε′
G = ] ε′
Υ ◦δG ,
[page 580]
d’o`u un homomorphisme
(29)
Gρ,σ
-
(χG,εG,ε′
G)
ˆZ∗× {±1} × {±1} ,
nous conduisant `a introduire G+
ρ,σ, G−
ρ,σ, G+,0
ρ,σ comme d’habitude.
L’injection iS+ : S+
-

Gρ,σ peut se prolonger en un plongement (not´e iS)
(30)
iS : S
-

Gρ,σ ,


---

41
que je d´eﬁnis par sa valeur sur τ = στ ′, par
(31)
iS(τ) = iZ(τZ) ,
o`u
(32)







τZ ∈Zρ,σ d´eﬁni comme
τZ = (int(τ)|S+
|
{z
}
∈Aut(S+)
, −1
|{z}
∈ˆZ∗
, −1
|{z}
∈{±1}
, −1
|{z}
∈{±1}
)
(52) .
D´esormais nous identiﬁons S `a un sous-groupe de Gρ,σ, et nous d´esignons par la mˆeme
lettre des ´el´ements de S (tels que τ, τ ′, ρ, σ, ε0, ε1 etc.) et leurs images dans Gρ,σ (53).
On aura d’ailleurs
(32 bis)
χG|S = εG|S = ε′
G|S = εS :



trivial sur S+
−1 sur S−= S ∖S+ .
4◦) Les groupes Zρ, Zσ, Nρ, Nσ, SNρ, SNσ . . .
On note que l’´el´ement τ ′ de S ⊆Gρ,σ normalise Lρ et Lσ, donc normalise aussi
(33)



Zρ
def
=
CentGρ,σ(ρ)
=
CentGρ,σ(Lρ)
Zσ
def
=
CentGρ,σ(σ)
=
CentGρ,σ(Lσ) ,
donc {1, τ ′} op`ere sur ces groupes, et on peut consid´erer
(34)



Nρ
=
{1, τ ′} · Zρ
Nσ
=
{1, τ ′} · Zσ
(produits semi-directs) .
On a des suites exactes canoniques
(35)
1
- Zρ
- Nρ
-
ερ
{±1}
- 1
1
- Zσ
- Nσ
-
εσ
{±1}
- 1 ,
et un diagramme commutatif d’homomorphismes canoniques
(36)
{1, τ ′} × {±1}

*

HHHH
j

Dρ
Dσ
-
-
Nρ
Nσ
HHHH
j
iρ

*
iσ
Gρ,σ ,
o`u
(37)









Dρ ≃D6 ⊆GL(2, Z) engendr´e par ρ, τ ′
Dσ ≃D4 ⊆GL(2, Z) engendr´e par σ, τ ′
{1, τ ′} × {±1} = Dρ ∩Dσ dans GL(2, Z) ,
52Si τΥ d´esigne l’image de τ = τG ∈Gρ,σ dans Υρ,σ = Gρ,σ/S+, S s’identiﬁe `a l’image inverse dans
Gρ,σ du sous-groupe {1, τΥ} de Υρ,σ.
53Notons que τ ′
G ̸∈Zρ,σ, par contre on a τG ∈Zρ,σ.


---

42
donc
(38)



Dρ
=
{1, τ ′} · Lρ
(du moins si ρ d’ordre 6 dans S)
Dσ
=
{1, τ ′} · Lσ
(du moins si σ d’ordre 4 dans S) ,
et les homomorphismes
Dρ
- Nρ ,
Dσ
- Nσ
sont ´evidents. Les homomorphismes iρ, iσ aussi, bien sˆur. Rappelons que
(39)









iρ injectif
⇐⇒
τ ′ ̸∈Zρ
⇐⇒
ρ2 ̸= 1
⇐⇒
ρ ̸= −1
⇐⇒
S+ est isomorphe `a un quotient de Z/4Z
iσ injectif
⇐⇒
τ ′ ̸∈Zσ
⇐⇒
σ2 ̸= 1 .
[page 581]
Faisant op´erer Gρ,σ sur S+, sous-groupe distingu´e, via automorphismes int´erieurs, on voit
que tout ´el´ement de Gρ,σ transforme Lρ ⊆S+ en un sous-groupe S+ conjugu´e, donc est
congru mod S+ `a un ´el´ement de NormS(Lρ) = iρ(Nρ), et de mˆeme pour Lσ.
Si g ∈Gρ,σ, et ε = εG(g), ε′ = ε′
G(g), alors int(g)(ρ) ∼
S+ ρε′ = τ ν′(ρ), int(g)(σ) ∼
S+ σε =
τ ν(σ) (o`u (−1)ν = ε, (−1)ν′ = ε′), donc ∃a = τ ν′ · a0 ∈Nρ (o`u a0 = τ νg) tel que
a) g ≡a (S+)
et
b) ερ(a) = ε′ = εG(g)
(et itou pour Nσ . . . ) – donc Im(N (+1)
ρ
- Υρ,σ) ⊇Υ′
ρ,σ, Im(N (−1)
ρ
- Υρ,σ) ⊇Υρ,σ∖Υ′
ρ,σ.
Mais cela ne prouve pas que l’on ait commutativit´e ici – c’est sans doute [phrase incom-
pl`ete].
En d’autres termes, posant
(40) N ∗
ρ
def
= {x ∈Nρ | ερ(x) = ε′
G(iρ(x))} ,
N ∗
σ
def
= {x ∈Nσ | εσ(x) = ε′
G(iσ(x))} ,
les homomorphismes compos´es
(41)



N ∗
ρ
-
iρ
Gρ,σ
-
δG
Υρ,σ ,
δρ
def
=
δG ◦iρ
N ∗
σ
-
iσ
Gρ,σ
-
δG
Υρ,σ ,
δσ
def
=
δG ◦iσ
sont des ´epimorphismes. On a donc [un] diagramme commutatif de suites exactes
(41)
1
- Zρ
- N ∗
ρ
-
ερ
{±1}
- 1
?
´epi
?
´epi
1
- Υ′
ρ,σ
- Υρ,σ
-
ε′
Υ
{±1}
- 1
[54] ,
o`u on a pos´e
(42)
Υ′
ρ,σ = Ker(Υρ,σ
-
ε′
Υ {±1}) .
54[Deux fois (41).]


---

43
De mˆeme [un] diagramme de suites exactes
(43)
1
- Zσ
- N ∗
σ
-
ερ
{±1}
- 1
?
´epi
?
´epi
1
- Υ′′
ρ,σ
- Υρ,σ
-
εΥ
{±1}
- 1 ,
o`u
(44)
Υ′′
ρ,σ = Ker(Υρ,σ
-
εΥ {±1}) .
NB Les notations εΥ, ε′
Υ : Υρ,σ
- {±1} peuvent prˆeter `a confusion, la premi`ere r´ef´erant
`a l’action d’un u sur Lσ (non sur Lρ). Une notation un peu plus lourde, mais ne prˆetant
pas `a confusion, serait εΥ,ρ, εΥ,σ – ou mˆeme seulement ερ, εσ, la confusion avec les homo-
morphismes de ce nom Nρ
- {±1}, Nσ
- {±1} ´etant anodine lorsque ρ2 ̸= 1, σ2 ̸= 1,
`a cause des compatibilit´es (41), (43).
On a donc construit, `a l’aide de (1), i.e. de S muni de ρ, σ, τ ′, des groupes S+, Gρ,σ,
Υρ,σ, Zρ,σ, N ′
ρ, N ′
σ, s’ins´erant dans un diagramme commutatif de groupes
(45)
1
- S+ 
-
iS+
Gρ,σ
-
δG
Υρ,σ
- 1
    
(χΥ,εΥ,ρ,εΥ,σ)
ˆZ∗× {±1} × {±1}
@
@@
R

S
   

L0 ≃SZρ,σ
B
B
B
B
B
B
B
B
BBN
  - Zρ,σ
BB
B
BB
B
B
B
BBN
  ?
δZ
SN ∗
ρ
- N ∗
ρ
?
?
?
δρ
SN ∗
σ
- N ∗
σ






?
δσ
o`u on a pos´e
(46)









SZρ,σ
=
iL0,ι(L0) = Ker(δZ : Zρ,σ
- Υρ,σ)
SN ′
ρ
=
Ker(δρ : N ∗
ρ
- Υρ,σ) = CentS+(ρ)
SN ′
σ
=
Ker(δσ : N ∗
σ
- Υρ,σ) = CentS+(σ)
(55) ,
[page 582]
de sorte qu’on a des suites exactes
(47)



1
-
SN ∗
ρ
-
N ∗
ρ
-
δρ
Υρ,σ
-
1
1
-
SN ∗
σ
-
N ∗
σ
-
δσ
Υρ,σ
-
1
(56) ,
55NB On peut donc aussi les noter SZρ, SZσ au lieu de SN ∗
ρ , SN ∗
σ.


---

44
s’envoyant dans la suite exacte
1
- S+
- Gρ,σ
- Υρ,σ
- 1 ,
de fa¸con analogue `a (27). De plus, les homomorphismes iρ : N ∗
ρ
- Gρ,σ et iσ : N ∗
σ
- Gρ,σ
ont une nette tendance `a ˆetre injectifs (cf. (39)), ce qu’on a indiqu´e sur le diagramme (45)
par le signe
- (signe d’inclusion pointill´e). On introduit aussi
(48)



χρ
=
χΥ ◦δρ
:
N ∗
ρ
-
ˆZ∗
χσ
=
χΥ ◦δσ
:
N ∗
σ
-
ˆZ∗,
dont les noyaux (qui contiennent SNρ resp. SNσ, et qu’on se gardera de confondre avec
eux) sont not´es comme de juste N ∗+
ρ
, N ∗+
σ
.
NB Il faudrait encore examiner les compos´es
(49)



N ∗
ρ
-
Υρ,σ
-
εΥ,σ
{±1}
N ∗
σ
-
Υρ,σ
-
εΥ,ρ
{±1} ,
on verra que dans les ‘bons cas’, les restrictions de ces homomorphismes `a Zρ, Zσ respec-
tivement sont ´epimorphiques.
[page 583]
5◦) Les groupes S0Mρ,σ, Mρ,σ, S0Γρ,σ, Γρ,σ.
On pose
(50)



S0Mρ,σ
=
Zρ,σ ×Υρ,σ N ∗
ρ ×Υρ,σ N ∗
σ ×Υρ,σ Gρ,σ
Mρ,σ
=
N ∗
ρ ×Υρ,σ N ∗
σ ×Υρ,σ Gρ,σ
(51)



S0Γρ,σ
=
Zρ,σ ×Υρ,σ N ∗
ρ ×Υρ,σ N ∗
σ
Γρ,σ
=
N ∗
ρ ×Υρ,σ N ∗
σ ,
56On a
(47 bis)



Im(SNρ
- S+)
=
NormS+(Lρ)
Im(SNσ
- S+)
=
NormS+(Lσ)
(ou encore, si ρ2 ̸= 1 resp. σ2 ̸= 1, ce sont Nρ ∩S et Nσ ∩S).


---

45
d’o`u [un] diagramme de suites exactes
(52)
1
?
L0
?
1
?
L0
?
1
- S+
- S0Mρ,σ
- S0Γρ,σ
- 1
?
?
1
- S+
- Mρ,σ
- Γρ,σ
- 1 ,
?
1
?
1
et des suites exactes
(53)
1
- SZρ,σ
| {z }
≃L0
×SN ∗
ρ × SN ∗
σ × S+
- S0Mρ,σ
- Υρ,σ
- 1 ,
(54)
1
- SN ∗
ρ × SN ∗
σ × S+
- Mρ,σ
- Υρ,σ
- 1 ,
(55)
1
- SZρ,σ
| {z }
≃L0
×SN ∗
ρ × SN ∗
σ
- S0Γρ,σ
- Υρ,σ
- 1 ,
(56)
1
- SN ∗
ρ × SN ∗
σ
- Γρ,σ
- Υρ,σ
- 1 .
On a aussi
(57)
S0Mρ,σ ≃Mρ,σ ×Υρ,σ Zρ,σ ,
(58)
S0Γρ,σ ≃Γρ,σ ×Υρ,σ Zρ,σ ,
i.e. les extensions S0Mρ,σ, S0Γρ,σ de Mρ,σ, Γρ,σ par L0 se d´eduisent de l’extension Zρ,σ de
Υρ,σ par L0 par image inverse par Mρ,σ
- Υρ,σ, Γρ,σ
- Υρ,σ – et on a aussi
(59)
S0Mρ,σ ≃Mρ,σ ×Γρ,σ S0Γρ,σ ,
i.e. l’extension S0Mρ,σ de Mρ,σ par L0 se d´eduit de l’extension S0Γρ,σ de Γρ,σ par L0, par
image inverse par Mρ,σ
- Γρ,σ.
On introduit un ´el´ement
(60)
τ ′
M ∈Mρ,σ ,
τ ′
M = (
= a
z}|{
τ ′
ρ ,
= b
z}|{
τ ′
σ ,
= u
z}|{
τ ′
G ) ,


---

46
o`u τ ′
ρ, τ ′
σ, τ ′
G sont les ‘avatars’ de τ ′, pris respectivement dans N ∗
ρ , N ∗
σ, Gρ,σ. Ceux-ci ont
bien tous la mˆeme image dans Gρ,σ et a fortiori dans Υρ,σ, donc d´eﬁnissent un ´el´ement de
Mρ,σ, dont l’op´eration sur S+ est celle de τ. D’o`u un plongement
(61)
S
-

iSM Mρ,σ :



identit´e sur S+
τ ′
S
- τ ′
M .
[page 584]
(62)
SN ∗
ρ×SN ∗
σ×S+
-
-
pr
S+ (57)
HHH
j

j
Mρ,σ
-
-
θG
Gρ,σ
S+



inj.
:
HHH
j

S
|{z}
= {1,τ ′}·S+



iS,M
IV

:
iS,G
L0×SN ∗
ρ×SN ∗
σ ×S+
A
A
AAUU
pr



pr
SN ∗
ρ×SN ∗
σ



pr
A
A
AAUU
pr
L0×SN ∗
ρ×SN ∗
σ
HHHH
j

HHH
j

HHH
H
j

A
A
AAUU



S0Mρ,σ
Γρ,σ



A
A
AAUU
S0Γρ,σ
:
:
θρ
z
z
θσ
z
z
δρ
:
:
δσ
N ∗
σ
N ∗
ρ
Υρ,σ
I
II
III



δG
A
A
AAUU
δZ

*
εΥ,ρ = ε′
Υ
{±1}
-
χΥ
ˆZ∗
HHHHHH
j {±1}
εΥ,σ = εΥ
-
-
pr
L0
HHH
j

-
-
θZ
Zρ,σ
V
On a resum´e certaines des relations entre les groupes introduits jusqu’`a pr´esent dans le
diagramme commutatif (62), que je commente bri`evement.
a) Toutes les ﬂ`eches sont soit injectives (
-

), soit surjectives (
-
- ), `a l’exception
peut-ˆetre des trois ﬂ`eches issues de Υρ,σ.
b) Les onze carr´es (six faces d’un cube, et cinq carr´es marqu´es I, II, III, IV, V) sont
cart´esiens.
c) Les cinq ﬂ`eches marqu´ees pr sont des projections canoniques de groupes produits
sur des produits partiels. La ﬂ`eche marqu´ee inj. : S+
- SN ∗
ρ × SN ∗
σ × S+ est
l’injection canonique.
d) Pour ne pas d´etruire la commutativit´e du diagramme, nous avons omis d’y faire
ﬁgure les ﬂ`eches (d’inclusion, moralement)
Zρ,σ
- Gρ,σ ,
N ∗
ρ
- Gρ,σ ,
N ∗
σ
- Gρ,σ ,
qui ﬁgurent dans (45).
57[S+ barr´e.
Probablement la partie du diagramme comprenant ce sommet S+ et les
fl`eches correspondantes est invalide.]


---

47
e) Pour ne pas surcharger le diagramme, je n’ai pas introduit dans ce diagramme de
notation pour certaines ﬂ`eches compos´ees utiles, telles
(63)















δΓ
:
Γρ,σ
-
Υρ,σ
δS0Γ
:
S0Γρ,σ
-
Υρ,σ
δM
:
Mρ,σ
-
Υρ,σ
δS0M
:
S0Mρ,σ
-
Υρ,σ ,
et
(64)















χΓ
=
χΥ ◦δΓ
:
Γρ,σ
-
ˆZ∗
χS0Γ
=
χΥ ◦δS0Γ
:
S0Γρ,σ
-
ˆZ∗
χM
=
χΥ ◦δM
:
Mρ,σ
-
ˆZ∗
χS0M
=
χΥ ◦δS0M
:
S0Mρ,σ
-
ˆZ∗,
et les compos´es ε?,ρ, ε?,σ : ?
- {±1}, o`u ? peut prendre toute valeur Z, G (d´eja
introduits), N ∗
ρ , N ∗
σ (on aura εNρ,ρ = ερ, εNσ,σ = εσ), Γ, S0Γ, M, S0M. Le noyau
de χ? est not´e ?∗, celui de ε? ρ est not´e ?′, celui de ε? σ est not´e ?′′, on note ?◦=?′∩?′′,
?+′ =?+∩?′, ?+′′ =?+∩?′′, ?+,◦=?+∩?◦, S? = Ker δ?, donc
(65)
?0 +
  

?′+
HHH
j

HHH
j

?′′+
  

?+
?
  ?
  ?
  ?
  ?0
  

?′
HHH
j

HHH
j

?′′
  

?
est ‘cart´esien’ [o`u ?◦+ =?+,◦, ?′+ = ?+′ et ?′′+ = ?+′′].
f) Rappelons aussi qu’on a commutativit´e dans
(66)
S

*
εS,ρ
{±1} HHHH
j ˆZ∗
,
-
χS
HHHH
j
εS,σ
{±1}

*
soit εS : S
- {±1}.
[page 585]
Le noyau de εS n’est autre que S+. En tant que sous-groupe de Mρ,σ (resp. de
Gρ,σ) S s’identiﬁe `a l’image inverse dans ce groupe du sous-groupe {1, τ ′
Γ} de Γρ,σ
(resp. du sous-groupe {1, τ ′
Υ} de Υρ,σ), o`u τ ′
Γ, τ ′
Υ d´esignent les images de τ ′ ∈S
dans Γρ,σ et Υρ,σ respectivement.


---

48
g) Le diagramme (62) a comme partie principale
(67)
A
AAU

 A
AAU



*
HHH
j 
*
HHH
j
-
-
A
AAU




1
-
PPPPP
q


,

1



tous les groupes marqu´es sur ce dernier diagramme, `a l’exception de ˆZ∗, {±1},
{±1} (mis entre crochets [
]) s’envoient dans Υρ,σ, qui est le terme terminal de
ce diagramme, reliant 9 groupes (en ne comptant pas S, ins´er´e comme source de
deux ﬂ`eches pointill´es) dans Υρ,σ, d´eduits de quatre d’entre eux Zρ,σ, N ∗
ρ , N ∗
σ, Gρ,σ
(qui s’envoient dans Υρ,σ par des ´epimorphismes) en prenant des produits ﬁbr´es
sur Υρ,σ de certains d’entre eux – le terme initial ´etant S0Mρ,σ, qui est le produit
ﬁbr´e des quatre facteurs pr´ec´edents. En prenant les noyaux des homomorphismes
des ces neuf groupes dans Υρ,σ, on trouve un diagramme de mˆeme type combina-
toire, reliant neuf groupes form´es de L0 = SZρ,σ, SN ∗
ρ , SN ∗
σ et S+ = SGρ,σ et
de certains produits de ces groupes (dont le produit sur l’ensemble d’indices vide,
savoir {1} = Ker(Υρ,σ
-
id Υρ,σ)), avec comme ﬂ`eches des projections canoniques.
Nous avons ins´er´e dans (62) seulement cinq parmi ces groupes produits, avec les
injections canoniques dans les produits ﬁbr´es dont ils proviennent, en nous dispen-
sant d’y faire ﬁgurer ´egalement SN ∗
ρ , SN ∗
σ, SGρ,σ = S+, les inclusions canoniques
SN ∗
ρ
-

N ∗
ρ , SN ∗
σ
-

N ∗
σ, S+ = SGρ,σ
-

Gρ,σ, et le diagramme complet des
projections des produits partiels de ces groupes et de L0, o`u manquent donc les
projections sur ces trois groupes, et les homomorphismes de ces groupes et de L0
dans le groupe unit´e.
[page 586]
6◦) Liens avec Σρ,σ, SGρ,σ.
On pose
(68)
Σρ,σ
=













(ξ, η, µ, ε′, ε)

ξρ S+-conjugu´e `a ρε′
ησ S+-conjugu´e `a σε
ξ = η εµ−1
1
|{z}
= lν
1, o`u ν = µ−1
2













⊆
S+ × S+ × ˆZ∗× {±1} × {±1} .
NB Si ρ non conjugu´e `a ρ−1 dans S+, ε′ connu quand on connaˆıt ξ, η – de mˆeme si σ non
conjugu´e `a σ−1 (donc σ2 ̸= 1), ε′ est d´etermin´e par ξ, η. De mˆeme si ˆZ
- L0 (n
- εn
0)
est injectif, alors µ est d´etermin´e par ξ, η, et la relation ξ = ηεµ−1
1
s’´ecrit aussi (sans faire
intervenir µ)
(69)
η−1ξ ∈L1 .
Soit d’autre part
(70)
SGρ,σ
=
{(α, β, µ) | [α, ρ]
| {z }
= ξ
= [β, σ]εµ−1
1
}
⊆
S × S × ˆZ∗.


---

49
On a une application
(71)























SGρ,σ
-
Σρ,σ
(α, β, µ)
-
(ξ, η, µ, ε′, ε) ,
avec





















ξ
=
[α, ρ]
η
=
[β, σ]
µ le mˆeme
ε′
=
εS(α)
ε
=
εS(β)
,
qui est ´evidemment surjective (58).
On d´eﬁnit d’autre part
(72)
Σeﬀ
ρ,σ
=
{(ξ, η, µ, ε′, ε) ∈Σρ,σ | ∃u ∈Aut(S+) avec u(ρ) = ξρ, u(σ) = ησ}
⊆
Σρ,σ
(59)
(cet u sera alors unique, et inversement, la connaissance de u d´etermine ξ, η). Il y a
correspondance 1–1 entre les ´el´ements de Σeﬀ
ρ,σ, et les syst`emes (u, µ, ε′, ε) ∈Aut(S+) ×
ˆZ∗× {±1} × {±1}, tels que l’on ait









u(ρ) est S+-conjugu´e `a ρε′
u(σ) est S+-conjugu´e `a σε
u(ε0) = εµ
0 (qui exprime ξ = ηlν
1)
– or cet ensemble n’est autre que le sous-groupe Zρ,σ de Aut(S+) × ˆZ∗× {±1} × {±1}
(cf. (6), p. 577). On trouve ainsi une bijection
(73)
Zρ,σ
-
∼
Σeﬀ
ρ,σ
u
-
(ξ, η, µ, ε′, ε) ,





















ξ
=
[u, ρ]
η
=
[u, σ]
µ
=
χ(u)
ε′
=
ε′
Z(u)
ε
=
εZ(u)
.
On d´esigne par SGeﬀ
ρ,σ l’image inverse de Σeﬀ
ρ,σ dans SGρ,σ par (71), donc on aura
(74)
SGeﬀ
ρ,σ
=















(α, β, µ) ∈S × S × ˆZ∗

[α, ρ] = [β, σ]εµ−1
1
∃u ∈Aut(S+) tel qu’on ait



u(ρ) = α(ρ)
( =
ξρ ,
avec
ξ = [α, ρ] )
u(σ) = β(σ)
( =
ησ ,
avec
η = [β, σ] )















⊆
SGρ,σ ,
58NB ξ = αρ(α)−1 ∈S+, car on a εS(ξ) = ˙αρ( ˙α) = 1, car ρ op`ere trivialement sur S/S+ ≃{±1},
pour la mˆeme raison η = βσ(β)∗∈S+.
59I.e. [u, ρ] = ξ, [u, σ] = η.


---

50
de sorte qu’on a un homomorphisme surjectif induit par (73)
(75)
SGeﬀ
ρ,σ
- Σeﬀ
ρ,σ .
[page 587]
On a une application canonique
(76)















S0Γρ,σ = Zρ,σ ×Υρ,σ N ∗
ρ ×Υρ,σ N ∗
σ
-
SGeﬀ
ρ,σ
x = (u, a, b)
-
(α, β, µ) , avec















α
=
u
∈Zρ
z
}|
{
a−1τ ′ν′(x)
β
=
u b−1τ ′ν(x)
|
{z
}
∈Zσ
µ
=
χSΓ(x)
(60)
o`u on a d´eﬁni ν′(x), ν(x) ∈Z/2Z par
(−1)ν′(x) = ε′(x) ,
(−1)ν(x) = ε(x) .
Par d´eﬁnition de S0Γρ,σ comme produit ﬁbr´e, on aura en eﬀet ua−1, ub−1 ∈S+, donc
α, β ∈S ; on aura d’ailleurs
(77)













α(ρ)
=
u(a−1(τ ′ν′(x)(ρ)
|
{z
}
= ρε′(x)
)
|
{z
}
= (ρε′(x))ε′(x) = ρ
) = u(ρ) ,
et de mˆeme
β(σ)
=
u(σ) ,
(61, 62)
d’ailleurs la condition [α, ρ]
| {z }
= [u,ρ]
= [β, σ]
| {z }
= [u,σ]
·εµ−1
1
ne fait qu’exprimer la condition que u(ε0) = εµ
0
qui intervient dans la d´eﬁnition mˆeme de Zρ,σ. Je dis que l’application envisag´ee (76) est
injective. Il suﬃt de voir que quand (α, β, µ) sont connus, on connaˆıt u – en eﬀet, on a
en termes de (α, β, µ)
(78)



ν′(x) = νS(α) ,
ν(x) = νS(β) ,
χSΓ(x) = χZ(u) = µ ,
d’o`u
a = τ ′ν(α)α−1u ,
b = τ ′ν(β)β−1u ,
donc si u est connu, on connaˆıt ´egalement a et b, donc x. D’autre part pour d´eterminer
u ∈Zρ,σ ⊆Aut(S+) × ˆZ∗× {±1} × {±1} en termes de (α, β, µ), il suﬃt en vertu de (78)
de d´eterminer l’´el´ement de Aut(S+) qu’il d´eﬁnit, ce qui est imm´ediat sur (77). On a donc
(79)
S0Γρ,σ
-

SGeﬀ
ρ,σ ,
60Pour ˆetre plus correct, il faudrait ´ecrire



α
=
u iρ(a)−1τ ′ν′(x)
β
=
u iσ(b)−1τ ′ν(x)
.
61I.e.
[α, ρ]
=
[u, ρ]
[β, σ]
=
[u, σ] .
62NB On a, pour tout a ∈N ∗
ρ , si ερ(a) = (−1)νρ(a), aτ ′νρ(a) ∈Zρ, donc [uaτ ′νρ(a), ρ] = [u, ρ]. Itou
pour σ . . .


---

51
il reste `a voir que cette application est surjective, on a fait ce qu’il fallait pour. Notons
d’abord que le compos´e
S0Γρ,σ
-

SGeﬀ
ρ,σ
-
´epi Σρ,σ (
-
∼
Zρ,σ )
n’est autre, par (77) et (71), que
(80)
x = (u, a, b)
- (ξ, η, µ, ε′, ε)

ξ
=
[u, ρ] ,
donc
u(ρ)
=
ξρ
η
=
[u, σ] ,
donc
u(σ)
=
ξσ
µ
=
χSΓ(x)
ε′
=
ε′(x)
ε
=
ε(x)
,
donc son compos´e avec Σeﬀ
ρ,σ
-
∼Zρ,σ n’est autre que la projection canonique
S0Γρ,σ
-
Zρ,σ
(u, a, b)
-
u ,
qui est surjective, de noyau SN ∗
ρ × SN ∗
σ = SZρ × SZσ. Consid´erons d’autre part
(81)















op´erations de SNρ × SNσ sur
SGρ,σ
=
{(α, β, µ) | [α, ρ] = [β, σ]εµ−1
1
}
⊆
S × S × ˆZ∗

(a0, b0) ∈SN ∗
ρ × SN ∗
σ
= SZρ × SZσ
op`ere par
(α, β, µ)
- (αa0, βb0, µ)















.
Il est clair qu’il op`ere librement, et que le quotient de Gρ,σ par cette action s’identiﬁe `a
Σρ,σ, donc on a le r´esultat idoine pour G∗
ρ,σ et Σ∗
ρ,σ. Or, pour
[page 588]
(82)
ε = (−1)ν ,
ε′ = (−1)ν′
ﬁx´es, l’op´eration pr´ec´edente de (a0, b0) correspond, par l’application (76), `a l’op´eration
(83)
(u, a, b)
- (u, τ ν′(a−1
0 )a, τ ν(b−1
0 )b) ,
i.e. `a la translation `a gauche par (τ ν′, τ ν) (a−1
0 , b−1
0 )
|
{z
}
= (a0,b0)−1
. D’o`u la surjectivit´e, et l’isomorphie
cherch´ee
(84)
S0Γρ,σ
-
∼
SGeﬀ
ρ,σ
(cf. 76) .
La translation `a gauche par l ∈L0 dans S0Γρ,σ correspond, par la bijection pr´ec´edente, `a
l’op´eration
(85)
(α, β, µ)
- (lα, lβ, µ) ,


---

52
dont il ´etait clair a priori qu’elle stabilise SGeﬀ
ρ,σ. Passant au quotient, on trouve donc
(86)
Γρ,σ
-
∼
L0\SGeﬀ
ρ,σ .
Enﬁn, consid´erons
(87)

































S0Mρ,σ
-
SGeﬀ
ρ,σ × S+
=
{(α, β, µ, f) ∈S×S× ˆZ∗×S+ | [α, ρ] = [β, σ]εµ−1
1
}
x = (u, a, b, U)
-
((α, β, µ), f)















α
=
ua−1τ ′νρ(a)
β
=
ub−1τ ′νσ(b)
µ
=
χSM(x) ( = χZ(u) = χρ(a) = χσ(b) = χG(U) )
f
=
uU −1 .
Cette application est bijective (trivial par (89)).
7◦) Fonctorialit´es.
Consid´erons
(88)
S
-
ϕ
S′ ,
homomorphisme surjectif de groupes proﬁnis.
Soient ρS′, σS′, τ ′
S′, . . . les images de ρ = ρS, σ = σS, τ ′ = τ ′
S, . . . dans S′.
Proposition. Conditions ´equivalentes sur ϕ :
a) L’application induite par ϕ
(89)
ΣS
ρ,σ
- ΣS′
ρ,σ
applique ΣS
ρ,σ
eﬀdans ΣS′
ρ,σ
eﬀ.
b) Pour tout u ∈Aut S+, qui normalise L0, et tel que u(Lρ) ∼
S+ Lρ, u(Lσ) ∼
S+ Lσ, il
existe u′ ∈Aut(S′+) qui rend commutatif
(90)
S+
-
ϕ
S′+
?
u
?
u′
S+
-
ϕ
S′+ ,
en d’autres termes, u invarie Ker ϕ.
b′) Itou, en supposant seulement, `a la place que u normalise L0, que u(L0) ∼
S+ L0 (plus
les autres conditions).
c) Il existe un homomorphisme de groupes
(91)
ϕZ : ZS
ρ,σ
- ZS′
ρ,σ
compatible avec χ, εZ, ε′
Z et tel que ∀u ∈ZS
ρ,σ, si u′ est son image, on ait comme
dans (90). (NB ϕZ sera unique, et est compatible avec iL0,Z (63)).


---

53
c′) Il existe un homorphisme de groupes
(92)
ϕG : GS
ρ,σ
- GS′
ρ,σ
compatible avec χG, εG, ε′
G et satisfaisant `a la condition de compatibilit´e (90). (NB
Ce ϕG
[page 589]
est alors unique, et compatible avec iS,G, iZ,G, il applique ZS
ρ dans ZS′
ρ , ZS
σ dans
ZS′
σ , qui se prolonge en ϕρ : N S
ρ
- N S′
ρ , induisant N ∗S
ρ
- N ∗S′
ρ
, et se prolonge
en ϕσ : N S
σ
- N S′
σ , induisant N ∗S
σ
- N ∗S′
σ
. . . )
On dira alors que ϕ est prolongeable.
Corollaire. On peut alors prolonger ϕ en
(93)
ϕSM : S0GS
ρ,σ
- S0GS′
ρ,σ ,
compatible avec θZ, θρ, θσ, θG, compte tenu de ϕZ, ϕρ, ϕσ, ϕG, et ceci de fa¸con ‘compatible
avec tout’, notamment avec les diagrammes (45), (62).
Exemple. Supposons ΣS′
ρ,σ = ΣS′
ρ,σ
eﬀ, alors les conditions de la proposition sont automa-
tiquement satisfaites (quelque soit l’homomorphisme surjectif S
- S′).
Remarque. Il se peut qu’on se donne un sous-groupe Z♮
ρ,σ ⊆ZS
ρ,σ, et qu’on consid`ere la
condition a) de la proposition seulement pour des u ∈Z♮
ρ,σ (64). Mais `a l’aide de Z♮
ρ,σ, on
construit
(94)
G♮
ρ,σ = Z♮
ρ,σ · S+ ,
Z♮
ρ = Zρ ∩G♮
ρ,σ ,
Z♮
σ = Zσ ∩G♮
ρ,σ
d’o`u N ♮
ρ et N ♮
ρ
∗, N ♮
σ et N ♮
σ
∗, Υ♮
ρ,σ , puis S0M♮
ρ,σ et M♮
ρ,σ .
Ceci pos´e, on a une variante ´evidente de la proposition, donnant des conditions de pro-
longement de ϕ en S0M♮
ρ,σ
- S0MS′
ρ,σ.
[page 590]
8◦) Le cas universel S = GL(2, Z)∧.
Consid´erons la suite exacte
(1)
1
- {±1}
- N ∼
1,1
|{z}
= M
- M∼
0,3
- 1 .
On a
(2)
{±1} = Centre(M) = Centre( ˆS+)
(65) ,
63Donc il induit ΥS
ρ,σ
- ΥS′
ρ,σ.
64Il faut supposer pour ˆetre `a l’aise que τ ′
Z ∈Z♮
ρ,σ.


---

54
d’o`u par (1) une application
(3)
M∼
0,3
- Aut(M)
-
restriction `a
S+ ∧= SL(2, Z)∧
Aut(S+ ∧) .
D’ailleurs, tout automorphisme de S+ ∧invarie son centre, donc passe au quotient, d’o`u
(4)
Aut(S+ ∧)
- Aut(S+ ∧/ ± 1 ≃S+ ∧
0,3 ) ,
et le compos´e de (3) avec (4) est l’homomorphisme canonique
(5)
M∼
0,3
- Aut(S+ ∧)
A
A
AAU




Aut(S+ ∧
0,3 = S+ ∧/{±1}) .
Cela montre que (3) est injectif, puisque M∼
0,3
- Aut(S+ ∧
0,3 ) l’est.
Remarque. L’application Aut(S+ ∧)
- Aut(S+ ∧
0,3 ) n’est pas injective par contre, les
´el´ements du noyau correspondant aux homomorphismes
S+ ∧
- Centre(S+ ∧) = {±1} ,
ou encore aux homomorphismes
(6)
S+ ∧
ab
- {±1} ,
ou encore
(S+ ∧
ab )2
- {±1} .
Or on veut que
S+ ∧
ab
=


ρ, σ

ρ6 = σ4 = [ρ, σ] = 1
ρ3 = σ2


≃Z/12Z ,
ρ
-
2 mod 12
σ
-
3 mod 12
[plut^ot ⟨ρ, σ| . . .⟩], donc
(7)









(S+ ∧
ab )2
-
∼
Z/2Z
ρ
-
0
σ
-
1 ,
cet isomorphisme correspond au caract`ere S+ ∧
- {±1}, qui s’obtient aussi comme com-
pos´e
(8)
S+ ∧
- S3 = S+ ∧/π∧
-
signature
d’une permutation {±1}
groupe
sym´etrique
`a trois
lettres
image
inverse
de π∧
0,3
dans S+∧
j
sg
65On a pos´e
S
=
T1,1
≃
GL(2, Z)
S∧
=
T ∧
1,1
≃
GL(2, Z)∧
S+
=
T +
1,1
=
SL(2, Z)
S+ ∧
=
SL(2, Z)∧.
[Grothendieck ´ecrit soit ˆS+, soit S+ ∧pour le m^eme groupe.
Nous ´ecrivons toujours
S+ ∧, et de m^eme pour S+ ∧
0,3 .
Similairement pour ˆπ = π∧etc.]


---

55
Ainsi le seul ´el´ement θ diﬀ´erent de 1 du noyau de (4) est donn´e par
(9)
θ : x
- x · sg(x) .
On notera, en posant
(10)
LS
0
= ε
ˆZ
0 ,
Lπ
0 = LS
0 ∩π = l
ˆZ
0 ,
que le sous-groupe θ(LS
0 ) ⊆S+ ∧n’est pas S-conjugu´e `a L0, il est engendr´e par
(11)
θ(ε0) = −ε0
(car ε0 = σρ, sg(ε0) = −1) ,
et on v´eriﬁe que ε0 n’est pas conjugu´e `a (−ε0)µ = −εµ
0 pour quelque µ ∈ˆZ∗(car on voit
[page 591]
tout de suite, en passant `a S∧
ab/π∧
0,3 ab et notant que l0 = ε2
0 serait conjugu´e `a (−εµ
0)2 = lµ
0,
qu’on doit avoir µ = 1, or ε0 et −ε0 ne sont pas conjugu´es mˆeme dans SL(2, ˆZ)′ . . . ).
Or on va s’int´eresser justement aux automorphismes de S+ ∧qui transforment LS
0 en un
sous-groupe conjugu´e. On notera que par contre
(12)
θ(l0) = l0 ,
donc θ(Lπ
0) = Lπ
0 .
Proposition. L’homomorphisme (3)
M∼
0,3
- Aut(S+ ∧)
est injectif, et son image est form´ee des automorphismes u de S+ ∧qui satisfont les deux
conditions suivantes.
a) u stabilise π = S+ ∧[2] = Ker(S+ ∧
- SL(2, Z/2Z)).
b) u transforme LS
0 en un sous-groupe de S+ ∧S+ ∧-conjugu´e de L0, i.e. il existe
µ ∈ˆZ∗et f0 ∈S+ ∧tels qu’on ait
(13)
u(ε0) = int(f −1
0 )(εµ
0) .
D´emonstration. L’injectivit´e a d´ej`a ´et´e vue. Montrons que les conditions a) b) sont
n´ecessaires pour que u provienne d’un u0 ∈M∼
0,3. Pour a) c’est trivial, puisque u0 stabilise
π∼
0,3, donc son image inverse dans S+ ∧. Pour la condition b), on est ramen´e au cas o`u
u0 ∈M∼
0,3[0] (quitte `a conjuguer par un ´el´ement de S+ ∧
0,3 ≃S+ ∧/ ± 1), dans ce cas on a
par construction de N ∼
1,1 `a partir de M∼
0,3 (cf. III, page 665 . . . )
(14)
u0(ε0) = εµ
0 ,
o`u µ0 ∈ˆZ∗est le multiplicateur, OK.
Inversement, soit u un automorphisme de S+ ∧qui satisfait a), b), consid´erons l’automor-
phisme ˜u de S+ ∧/ ± 1 ≃S+ ∧
0,3 qu’il induit. On voit donc que ˜u(π∧
0,3) = π∧
0,3, et que ˜u(ε0)
est S+ ∧
0,3 -conjugu´e `a un εµ
0 (µ ∈ˆZ∗). Donc par d´eﬁnition, on a ˜u ∈M∼
0,3 (cf. page 390
ﬀ.). Soit u′ l’automorphisme de S+ ∧induit par ˜u (via (3)) – alors u′ et u induisent le
mˆeme automorphisme de S+ ∧
0,3 = S+ ∧/{±1}, donc on aura u′ = u0Θ, o`u Θ = u−1u′ est
un automorphisme qui


---

56
1◦) induit l’identit´e sur S+ ∧/{±1}, et
2◦) transforme LS
0 en un sous-groupe conjugu´e
– on a vu que cela implique Θ = 1, c.q.f.d.
Consid´erons maintenant la suite exacte
(15)
1
- ± 1
-
π
|{z}
= S+[2]
- π0,3
- 1 ,
[page 592]
et consid´erons le scindage donn´e par
(16)



π0,3
-
π = S+[2] = Ker(SL(2, Z)
- SL(2, Z/2Z))
li
-
λi
def
= −li .
Il y a un tel homomorphisme, en vertu de
(17)



(−l∞)(−l1)(−l0) = 1 dans SL(2, Z), i.e.
l∞l1l0 = −1 ,
et il est ´evident que c’est un scindage. On aura de mˆeme un scindage pour π∧sur π∧
0,3.
On d´esigne par π0 l’image de (16), i.e.
(18)



π0 sous-groupe de π = S+[2] engendr´e par
λ0, λ1, λ∞(o`u λi = −li) ,
et on a donc un sous-groupe π∧
0 de π∧.
Proposition.
a) Le sous-groupe π0 de π est d’indice 2, et il est distingu´e dans S.
b) Le sous-groupe π∧
0 de π∧est d’indice 2 et il est distingu´e dans M – ou, ce qui revient
au mˆeme, stable sous l’action de M/ ± 1 ≃M∼
0,3.
D´emonstration. Comme
(19)









ρ(λi)
=
λi+1
σ(λ0)
=
λ1 ,
σ(λ1)
=
λ0 ,
σ(λ∞)
=
σ(λ1λ0)−1
=
λ−1
1 λ−1
0
τ(λ0)
=
λ−1
0
,
τ(λ1)
=
λ−1
1
,
τ(λ∞)
=
τ(λ1λ0)−1
=
λ0λ1 ,
on voit que π0 est normalis´e par ρ, σ, τ, donc par S. Qu’il soit d’indice 2 est ´evident.
Donc π∧
0 est d’indice 2 dans π∧et normalis´e par S∧. Pour voir qu’il est normalis´e par M
tout entier, comme
M = M(0) · S+ ∧,


---

57
on est ramen´e `a v´eriﬁer qu’il est normalis´e par M(0) ≃M∼
0,3(0).
Or on aura, pour
u ∈M∼
0,3(0),
(20)









u(ρ)
=
int(α)ρ
u(σ)
=
ε2 int(β)σ
u(ε0)
=
εµ
0









ε2
=
ε2(µ)
α
∈
π∧· {1, τ}
β
∈
π∧,
d’o`u
(21)



u(l0)
=
lµ
0
u(−l0)
=
(−l0)µ ,
i.e. u(λ0) = λµ
0 (car (−1)µ = −1) ,
donc u(λ0) ∈π∧
0 ; il reste `a prouver que u(λ1) ∈π∧
0 , or
u(λ1) = u(ρ(λ0)) = ( uρ
|{z}
= (int(α)ρ)u
)(λ0) = int(α)(ρ)(u(λ0)
| {z }
= λµ
0
) ,
et comme π∧
0 est normalis´e par S∧et en particulier par αρα−1, on trouve bien u(λ1) ∈π∧
0 .
Corollaire. On a
(22)



π
≃
π0 × µ
π∧
≃
π∧
0 × µ ,
o`u
µ = {±1} = Centre(S+ ∧) .
C’est trivial, puisqu’on a un scindage de l’extension centrale (15).
[page 593]
Soient
(23)



µτ
=
{1, τ}
⊆
S ,
Dτ
=
µτ × µ
⊆
S ,
µσ
=
{1, σ}
⊆
S ,
Dσ
=
µσ × µ
⊆
S ,
de sorte que l’on a
(24)
Dτ ∩S
=
Dτ ∩π
=
µ
Dτ ∩π0
=
{1}
Dσ ∩S
=
Dσ ∩π
=
µ
Dσ ∩π0
=
{1}
(66) .
On pose
(25)



πτ
=
µτ · π
=
Dτ · π0 ,
π0 τ
=
µτ · π0 ,
πσ
=
µσ · π
=
Dσ · π0 ,
π0 σ
=
µσ · π0 ,
66Itou en rempla¸cant S, π par S∧, π∧.


---

58
de sorte que l’on a
(26)



πτ
=
π0 τ × µ ,
πσ
=
π0 σ × µ ,
et itou en mettant des ∧.
Normalisation de α, β. Les relations (20) ne d´eterminent α, β que ‘modulo signe’. On
l`eve cette ambiguit´e en prenant
(27)
α ∈π0 τ ,
β ∈π0 .
Le groupe S/π0. Il est d´ecrit par g´en´erateurs ρ, σ, τ et relations
(28)









ρ6 = σ4 = τ 2 = 1 ,
ρ3 = σ2 ,
τ(ρ) = σ(ρ−1) ,
τ(σ) = σ−1 ,
τ(ρ) = ρ ,
car on a
(29)
τ(ρ) = (−l−1
1 )ρ ,
donc la derni`ere relation (28) s’´ecrit −l−1
1
= 1, i.e. λ1 = 1, et implique λ∞= λ0 = 1 (en
appliquant ρ). En termes de ρ, σ, τ ′, on trouve de mˆeme
(30)









ρ6 = σ4 = τ ′2 = 1 ,
ρ3 = σ2 ,
τ ′(ρ) = ρ−1 ,
τ ′(σ) = σ−1 ,
σ(ρ) = ρ−1 .
Le sous-groupe S+/π0 a la pr´esentation en ρ, σ
(31)



ρ6 = σ4 = 1 ,
ρ3 = σ2 ,
σ(ρ) = ρ−1


.
Quelle est l’op´eration de M∼
0,3 ≃M/ ± 1 sur S+/π0? On a une structure d’extension
(32)
1
-
µ
|{z}
= ±1
- S+/π0
- S+/π
| {z }
≃S3
- 1 ,
et les automorphismes en question conservent cette structure d’extension. Les ´el´ements
de M! ∼
0,3 ≃M!/{±1} op`erent en induisant l’identit´e dans le quotient S3, et bien sˆur aussi
dans µ – or un tel automorphisme de l’extension correspond `a un homomorphisme
(33)
S3
-
µ
|{z}
±1
,
i.e.
S3 ab
- µ ,
or
S3 ab
-
sg
{±1} = µ ,


---

59
donc le groupe des automorphismes de S+/π0 induisant l’identit´e dans S3 est isomorphe
`a Z/2Z, son g´en´erateur est donn´e par
(34)
θ(x) = sg(x) · x ,
donc



θ(ρ)
=
ρ
θ(σ)
=
−σ .
[page 594]
Composant avec les formules (20), on trouve
(35)
u|S+ ∧/π∧
0 = θε2(u) :



˙ρ
-
˙ρ
˙σ
-
ε2(u) ˙σ
,
i.e.
(35 bis)
[ ˙u, ˙σ]
| {z }
= ˙u( ˙σ) ˙σ−1
= ε2(u)˙
dans
S/π0
(67) .
Reprenons la d´eﬁnition
(36)
Z = Zρ,σ
def
=









u ∈Aut(S+ ∧)

u(Lρ) S+ ∧-conjugu´e `a Lρ
u(Lσ) S+ ∧-conjugu´e `a Lσ
u(L0) = L0









,
de sorte qu’on aura, pour u ∈Z,
(37)









u(ρ) S-conjugu´e `a ρε′
u(σ) S-conjugu´e `a σε (= εσ)
u(ε0) = εµ
0 ,
avec µ ∈ˆZ∗et ε, ε′ ∈{±1} bien d´etermin´es (car



ˆZ
-
S
n
-
εn
0
est injectif, ρ et ρ−1
ne sont pas S+ ∧-conjugu´es, ni σ et σ−1). Je dis qu’un tel u provient de M∼
0,3 – il reste `a
v´eriﬁer, en vertu de la proposition, que u stabilise π∧, qui est engendr´e par l0, l1, l∞. Or
on aura
u(l0) = lµ
0 ∈π∧
et
u(h) =
uρ
|{z}









= int(f)(ρε′)(u)
f ∈S+ ∧
(l0) = int(f)(ρε′)(u(l0)) = int(f)(ρε′)(lµ
0) ,
67Cela s’´ecrit aussi [ ˙u, ˙x] = sg(x)ν2(u) dans S+ ∧/π0 (u ∈M!, x ∈S+ ∧) (attention, ¸ca foire si on ne
suppose pas u ∈M!, seulement u ∈M . . . ).


---

60
or S∧et a fortiori int(f)(ρε′) normalisent π∧, donc
u(l1) ∈π∧,
et comme
u(−1) = −1 ,
d’o`u
u(l∞) = −u(l1l0)−1 = −u(l0)−1u(l1)−1 ,
on a aussi u(l∞) ∈π∧, OK.
Si on identiﬁe u `a un ´el´ement de M∼
0,3, on voit qu’en fait
u ∈M∼
0,3 ≃M![0] ⊆M
(68) ,
et on aura donc (20), de fa¸con plus pr´ecise,
(38)









u(ρ)
=
int(α)ρ
u(σ)
=
ε2 int(β)σ
u(ε0)
=
εµ
0
avec



α ∈π∧
0 τ ,
β ∈π∧
0
µ ∈ˆZ∗,
qui `a leur tour impliquent (37). En fait, les formules (38) pour u(ρ), u(σ), u(ε0) d´eterminent
de fa¸con unique µ ∈ˆZ∗, ε2 ∈{±1}, α ∈π∧
0 τ, β ∈π∧
0 , et on aura n´ecessairement alors
(39)
ε2 = ε2(µ) ,
ετ = ε3(µ) ,
[ε3 = ?]
o`u ετ est l’homomorphisme qui intervient dans la suite exacte
(40)
1
- π∧
0
- π∧
0,τ
-
ετ
{±1}
- 1 .
Ainsi on a prouv´e :
Proposition. Dans le cas universel (S = S+ ∧), on a Z!
ρ,σ ∼M![0]
def
= M! ∼
0,3[0], les
composants u, µ, ε′, ε d’un ´el´ement de Z!
ρ,σ correspondant respectivement (en termes de
u0 ∈M[0]) `a u0 (identiﬁ´e `a un ´el´ement de Aut(S+ ∧)), µ = χ(u0) (le multiplicateur de
u0), ε = ε3(µ), ε′ = ε2(µ).
Corollaire. On a Gρ,σ ≃M = N ∼
1,1, Υρ,σ ≃M/S+ ∧= N ∼
1,1/S+ ∧≃M∼
0,3/S+ ∧
0,3 ≃Γ∼
Q.
[page 595]
Remarque. Il est tentant d’´ecrire les deux premi`eres relations (38) sous la forme
(41)



(α−1u)(ρ)
=
ρ ,
i.e.
α−1u
∈
Zρ ,
(β−1u)(σ)
=
ε2σ ,
soit
β−1u
∈
N ′
σ ,
et d’introduire alors
(42)



a
=
α−1u
∈
Zρ ,
donc
u
=
αa ,
α
=
ua−1 ,
b
=
β−1u
∈
Nσ ,
donc
u
=
βb ,
β
=
ub−1 ,
68Attention, on n’avait pas introduit pr´ec´edemment M∼
0,3[0], mais seulement M! ∼
0,3[0] ⊆M! ∼
0,3. Or il
n’est pas vrai que l’on aurait u ∈M! ∼
0,3, p.ex. on peut avoir u = ε0. L’image de u dans S3 est dans {1, σ0},
donc en corrigeant au besoin par ε0, on aura un ´el´ement de M! ∼
0,3[0]. Cf. rectiﬁcation plus d´etaill´ee p.
609 ﬀ. On va noter Z!
ρ,σ = M![0] = Zρ,σ ∩M!.


---

61
et les d´eveloppements du §48 (notamment XI) peuvent faire s’attendre que les quantit´es a,
b, pour u ∈M[0] variable, d´ependent multiplicativement de u. Nous allons voir cependant
qu’il n’en est rien. Soit en eﬀet
δ : Gρ,σ
-
∼
M
- Υρ,σ ≃Γ∼
Q
l’homomorphisme canonique, de sorte que l’on aura
(43)
δ(u) = δ(b) = τ ν3
Υ δ(a) ,
en posant
τΥ = δ(τ) ,
ε3 = (−1)ν3
( ν3 ∈Z/2Z ) .
Si u′ correspond `a b′, a′, ν′
3, on aura de mˆeme
(43 bis)
δ(u′) = δ(b′) = τ
ν′
3
Υ δ(a′) ,
et si u′′ = u′u correspond `a a′′, b′′, ν′′
3,
(43 ter)
δ(u′u) = δ(b′′) = τ
ν′′
3
Υ δ(a′′) .
En fait, on aura
(44)
b′′ = b′b ,
ν′′
2 = ν′
2 + ν2
et
ν′′
3 = ν′
3 + ν3
(i.e.
ε′′
2 = ε′
2ε2
et
ε′′
3 = ε′
3ε3
) .
On a en u
u(σ)
=
ε2 int(β)σ
u′(σ)
=
ε′
2 int(β′)σ ,
d’o`u
(u′u)(σ) = u′(u(σ)) = ε2 int(u′(β))u′(σ) = ε2ε′
2 int(u′(β)β′)σ
avec u′(β)β′ ∈π∧
0 , ce qui par l’unicit´e prouve
(45)
β′′ = u′(β)β′ ,
ε′′
2 = ε′
2ε2 ,
d’o`u on conclut bien
b′′
|{z}
= β′′−1u′′ = β′′−1(u′u)
=
b′
|{z}
= β′−1u′
·
b
|{z}
= β′u
,
i.e. β′′−1u′u = β′−1u′β−1u, i.e. β′′−1 = β′−1u′(β−1), i.e. β′′ = u′(β)β′, qui n’est autre que
(45). La relation ε′′
3 = ε′
3ε3 est aussi ´evidente, p.ex. sur la relation (qui caract´erise ε3 et
de mˆeme ε′
3, ε′′
3)
(46)
u(ρ) est S+ ∧-conjugu´e `a ρε3 .
Il reste donc `a examiner la relation hypoth´etique
a′′ = a′a ,
qui implique
(∗)
δ(a′′) = δ(a′)δ(a) ,


---

62
mais comparant (43), (43 bis), (43 ter), on trouve la relation
δ(u′)δ(u)
|
{z
}
= δ(u′u) = τ
ν′′
3
Υ δ(a′′)
= τ
ν′
3
Υ δ(a′)τ ν3
Υ δ(a) ,
[page 596]
[i.e.]
τ
ν′
3+ν3
Υ
δ(a′′) = τ
ν′
3
Υ δ(a′)τ ν3
Υ δ(a) ,
ou encore
δ(a′′) = τ ν3
Υ δ(a′)τ ν3
Υ δ(a) ,
i.e.
(47)
δ(a′′) = τ ν3
Υ (δ(a′))δ(a) .
Donc la relation (∗) ´equivaut `a
(48)
δ(a′) = τ ν3
Υ (δ(a′)) , i.e. [δ(a′), τ ν3
Υ ] = 1 , i.e. [δ(u′), τ ν3
Υ ] = 1
(69) .
Cela montre que si ν3 = 1, i.e. ε3 = −1, alors la relation (∗) ´equivaut `a la commutativit´e
de δ(u′) avec τΥ. C’est une condition draconienne sur un ´el´ement de Γ∼
Q qui, pour un
´el´ement de ΓQ lui-mˆeme tout au moins, implique que u′ ∈{1, τΥ} – et par des arguments
heuristiques, on a vu qu’il devait mˆeme en ˆetre ainsi pour tout ´el´ement de Γ∼
Q. Il apparaˆıt
que le succ`es de la pr´esentation du §48 XI tient au fait que dans la situation envisag´ee
dans ce cas, le groupe Υρ,σ ≃ˆZ∗´etait commutatif, donc τΥ central. En dehors de ce cas,
la quantit´e a = α−1u ∈Zρ
-

Gρ,σ d´epend multiplicativement de l’´el´ement u ∈M![0],
seulement `a condition de se borner `a des u ∈M![0]′.
Nous allons essayer de sauver la mise, en trouvant un homomorphisme canonique
M![0]
| {z }
= Z!ρ,σ
- Z!
ρ,σ ×Υρ,σ N ∗
ρ ×Υρ,σ N ∗
σ
|
{z
}
= S0Γ!ρ,σ
⊆
indice 2
S0Γρ,σ
(70) .
Notons que le deuxi`eme membre est form´e des triples
(49)
{(
u
|{z}
∈M[0]
,
a
|{z}
∈N ′ρ
,
b
|{z}
∈N ′σ
) | u = fb = f ′a, avec f, f ′ ∈S+ ∧convenables}
(71) ,
et pour un tel triple, on aura
(49 bis)







u(σ) = int(fb)(σ) = int(f) int(b)(σ)
|
{z
}
= ε2(b)(σ)
= ε2(u) int(f)(σ)
u(ρ) = int(f ′)(ρε3(u)) = int(f ′)ε3(τ ′)(ρ) = int(f ′ε3(τ ′))(ρ) ,
69Puisque δ(u) = τ ν3
Υ δ(a).
70NB On a S0Γ!
ρ,σ/Lπ
0
-
∼
S0Γρ,σ/LS
0
def
= Υρ,σ ≃Γ∼
Q.
71Ce qui implique
ε2(u)
=
εσ(b)
ε3(u)
=
ερ(a)


---

63
o`u on pose
ε3(τ ′)
def
=



1
si
ε3
=
+1
τ ′
si
ε3
=
−1
,
i.e. ε3(τ ′) = σν3 si ε3 = (−1)ν3 .
Si u correspond `a α, β (cf. (38)), les formules (49 bis) s’´ecrivent aussi respectivement



int(f)(σ)
=
int(β)(σ) ,
i.e.
f
=
βσi
( i ∈Z/4Z )
int(f ′ε3(τ ′))(ρ)
=
int(α)(ρ) ,
i.e.
f ′ε3(τ ′)
=
αρj
( j ∈Z/6Z ) .
Donc on trouve :
Proposition. Pour un u ∈Z!
ρ,σ = M![0] ≃M∼
0,3 ﬁx´e, les (u, a, b) ∈S0Γρ,σ au dessus de
u sont exactement les ´el´ements de
(50)


(u, a, b)

a
=
f ′−1u
avec
f ′
=
αρjε3(τ ′)
( j ∈Z/6Z )
b
=
f −1u
avec
f
=
βσi
( i ∈Z/4Z )



(72) .
Consid´erons alors l’´el´ement (u, a, b) au dessus de u ayant l’expression la plus simple en
termes de α, β, en prenant i = 0, j = 0, correspondant donc aux choix :
[page 597]
(51)



a
=
ε3(τ ′)α−1u ,
i.e.
α
=
ua−1ε3(τ ′)
b
=
β−1u ,
i.e.
β
=
ub−1 ;
je me demande si cette section ensembliste de S0Γ!
ρ,σ au dessus de Z!
ρ,σ = M![0] est
multiplicative, ou, ce qui revient au mˆeme, si a et b d´eﬁnis par (51) d´ependent multiplica-
tivement de u.
Proposition Soit (u, a, b) ∈S0Γ!
ρ,σ (cf. (50)). Pour qu’on ait i = 0, j = 0, i.e. pour
qu’on ait (51) – i.e. pour que (u, a, b) appartienne `a la section ensembliste pr´ec´edente, il
faut et il suﬃt qu’on ait les relations
(52)
u ≡b ≡ε3(σ)a
mod π∧
0
(73) .
D´emonstration. Comme ρ = ub−1 et αε3(σ) = uσ−1ε3(τ ′) = ua−1ε3(σ−1) (74) sont
tous deux dans π0, la condition est n´ecessaire. Pour la suﬃsance, on note que (52) s’´ecrit,
avec les notations de (50), donc f = ub−1, f ′ = ua−1, i.e. f ′ε3(σ−1) = ua−1ε3(σ−1),
(53)
f , f ′ε3(σ−1) ∈π0 ,
72o`u α, β, ε2, ε3 sont d´eﬁnis par u via (38).
73O`u on a pos´e
ε3(σ) =



1
si
ε3
=
+1
σ
si
ε3
=
−1 .
74NB τ ′τ = σ−1, τ ′σ−1 = τ.


---

64
et r´eduisant modulo π∧
0 dans S∧/π0 cela s’´ecrit ˙β ˙σi = 1 et ˙α ˙ρjε3(τ ′σ−1)˙= 1, cette derni`ere
relation s’´ecrit aussi ˙α( ˙ρ)ε3(τ)˙= 1, i.e. ε3( ˙τ) ˙α ˙ρj = 1, or ε3( ˙τ) ˙α = 1, la condition [1mm]
˙σi = ˙ρj = 1 ,
i.e.
i = 0 , j = 0 ,
c.q.f.d.
Soient maintenant u, correspondant `a a, b, ε3, et u′, correspondant `a a′, b′, ε′
3, soit
u′′ = u′u, correspondant `a a′′, b′′ = b′b et ε′′
3 = ε′
3ε3, de sorte qu’on aura
u
≡
ε3(σ)a
(π∧
0 )
u′
≡
ε′
3(σ)a′
(π∧
0 )
u′′
|{z}
=
u′u
|{z}
≡(ε′
3(σ)a′)(ε3(σ)a)
= ε · ε′
3(σ) · ε3(σ) · a′′, o`u ε ∈{±1}, ε = −1 si et seulement si ε3 = −1 et ε′
3 = −1
≡
ε′′
3(σ)a′′
(π∧
0 ) ,
ce qui donne
a′ε3(σ)a ≡εε3(σ)a′′
(π∧
0 ) ,
i.e.
(53)
a′′ ≡εε3(σ)(a′) · a
(75), [76] .
Donc la relation escompt´ee
a′′ = a′a ,
´equivalente `a
a′′ ≡a′a
(π∧
0 ) ,
est vraie si et seulement si on a
[page 598]
(54)
ε3(σ)(a′) ≡εa′
(π∧
0 ) ,
o`u









ε ∈{±1} , ε
def
= −1 si et seulement si ε3 = ε′
3 = −1
ε3(σ)
def
=



1
si
ε3
=
+1
σ
si
ε3
=
−1 .
Cette condition (54) s’explicite suivant les cas :
(55)









a)
si ε3 = 1, alors ε = 1 et (54) [est] toujours v´eriﬁ´ee.
b)
si ε3 = −1, alors (54) s’´ecrit σ(a′) = ε′
3 · a′
(π∧
0 ), i.e.
[ ˙σ, ˙a′] = ˙ε′
3 ,
o`u les ˙ d´esignent les classes dans M/π∧
0 .
Comme on a a′ ≡ε′
3(σ)−1u′ =



u′
si
ε′
3
=
1
σ−1u′
si
ε′
3
=
−1
, on trouve que la condition
(55 b) ´equivaut aussi `a
(56)



˙σ( ˙u′)
=
ε′
3u′
dans M/π∧
0 , i.e.
[ ˙σ, ˙u′]
=
ε′
3
75NB ε3(σ) et ε3(σ−1) op`erent de la mˆeme fa¸con car σ−1 = −σ.
76[Deux fois (53).]


---

65
(´equivalence valable aussi bien pour ε′
3 = 1 que ε′
3 = −1). Or on a vu (35) que l’on a dans
S+ ∧/π∧
0
˙u′( ˙σ) = ε2(u′) ˙σ ,
i.e. [ ˙u′, ˙σ] = ε2(u′), ou encore
(57)
[ ˙σ, ˙u′] = ε2(u′)˙.
Comparant (56) et (57), on voit que (56) prend la forme ´equivalente
(58)
ε2(u′) = ε3(u′) .
On a donc prouv´e :
Proposition. Soient u, u′ et u′′ = u′u dans M![0] = Z!
ρ,σ, correspondant `a ε3 = ε′
3,
ε′′
3 = ε′
3ε3 dans {±1}, et `a a = ε3(τ ′)α−1u, a′ = ε′
3(τ ′)α′−1u′, a′′ = ε′′
3(τ ′)
| {z }
= ε′
3(τ ′)ε3(τ ′)
α′′−1 u′′
|{z}
u′u
, avec
a, a′, a′′ ∈N ′
ρ, a ≡ε3(σ)−1u, a′ ≡. . . , a′′ ≡. . . (π0) (77). Les conditions suivantes sont
´equivalentes :
a) On a
a′′ = a′a .
a′) On a
a′′ ≡a′a
(π∧
0 ) .
b) On a ε3 = 1, i.e. a(ρ) = ρ, ou σ(a′) = ε′
3a′
(π∧
0 ).
b′) On a ε3 = 1, i.e. a(ρ) = ρ, ou a′(σ) = ε′
3σ
(π∧
0 ).
c) On a ε3 = 1, i.e. a(ρ) = ρ, ou σ(u′) = ε′
3u′
(π∧
0 ).
c′) On a ε3 = 1, i.e. a(ρ) = ρ, ou u′(σ) = ε′
3σ
(π∧
0 ).
d) On a ε3 = 1 ou ε′
2 = ε′
3, i.e. ε′
2ε′
3 = 1 .
Corollaire. Au dessus des deux sous-groupes
(59)



Z!′
ρ,σ
=
M!′[0]
def
=
{u ∈Z!
ρ,σ | ε3(u) = 1}
Z!′′′
ρ,σ
=
M!′′′[0]
def
=
{u ∈Z!
ρ,σ | ε2(u) = ε3(u)}
l’application section ensembliste
(60)
A :
Z!
ρ,σ
|{z}
≃M![0]
-
S0Γ!
ρ,σ
u
-
(u, a = ε3(τ ′)α−1u, b = β−1u)
(78)
77NB









ε3
=
ε3(u)
=
ερ(a)
ε′
3
=
ε3(u′)
=
ερ(a′)
ε′′
3
=
ε3(u′′)
=
ερ(a′′) .


---

66
est une section multiplicative. Mais elle n’est pas multiplicative au dessus de M![0] tout
entier.
[page 599]
Remarque. Les ´el´ements de l’image inverse S0Γ′!
ρ,σ de Z!′
ρ,σ dans S0Γ!
ρ,σ qui appartiennent
`a la section envisag´ee sont caract´eris´es (en vertu de la proposition p. 598) par la relation
(61)
u ≡b ≡a
mod π∧
0
(79) ,
qui rend ´evident que c’est un sous-groupe. Je n’ai pas trouv´e de jolie expression analogue
pour l’appartenance d’un ´el´ement de S0Γ!′′′
ρ,σ (caract´eris´e par la relation ε2(u)ε3(u) = 1) `a
la section correspondante.
Proposition. Soit Sπ
0 Γ!
ρ,σ ⊆S0Γ!
ρ,σ le sous-ensemble de S0Γ!
ρ,σ [donn´e par]
(62)
Sπ
0 Γ!
ρ,σ
=





(u, a, b) ∈Zρ,σ
|{z}
= M[0]
×N ∗
ρ × N ∗
σ

u
≡
b
(π∧
0 )
u
≡
ε3(σ)a
mod π∧= π∧
0 × {±1}





⊆
S0Γ!
ρ,σ .
Alors :
a) Sπ
0 Γ!
ρ,σ est un sous-groupe de S0Γ!
ρ,σ.
b) L’homomorphisme canonique Sπ
0 Γ!
ρ,σ
- Z!
ρ,σ = M![0], (u, a, b)
- u, est surjectif,
et son noyau est le sous-groupe, isomorphe `a µ = {±1}, des ´el´ements (1, ε, 1) avec
ε ∈µ = N ′
ρ ∩π∧= Lρ ∩π∧.
D´emonstration. Le fait qu’on a un sous-groupe r´esulte du calcul d´ej`a fait p. 597, 598, la
condition que le produit de deux ´el´ements (u′, a′, b′), (u, a, b) de Sπ
0 Γ!
ρ,σ y soit, s’exprimant
encore par la formule
(56)
[ ˙σ, ˙u′] = ˙ε′
3
dans M/π∧(au lieu de M/π∧
0 )
[80] ,
ou encore
(56 bis)
[ ˙u′, ˙σ]
| {z }
= ˙u′( ˙σ) ˙σ−1 = ˙ε′
2
= ˙ε′
3 ,
soit ˙ε′
3 = ˙ε′
2 .
Or dans S/π0, les images de ε′
2 et ε′
3 appartiennent toutes deux au sous-groupe central
π/π0, donc ils sont triviaux dans S/π, donc la relation (56 bis) est trivialement satisfaite.
La surjectivit´e de l’application Sπ
0 Γ!
ρ,σ
- Z!
ρ,σ provient du fait que Sπ
0 Γ!
ρ,σ contient la
section ensembliste A(Z!
ρ,σ) de la proposition p. 597. Le noyau est form´e des (1, a, b) avec
a ∈N ∗
ρ ∩π, b ∈N ∗
σ ∩π0. Or N ∗
ρ ∩S = Lρ, N ∗
σ ∩S = Lσ, et
(57)
Lρ ∩π∧= Lσ ∩π∧= µ ,
Lρ ∩π∧
0 = Lσ ∩π∧
0 = {1} ,
78Cf. proposition p. 597.
79En plus de ε3(u) ≡1, qui caract´erise les ´el´ements de S0Γ′!
ρ,σ.
80[Saut dans la num´erotation.]


---

67
[page 600]
d’o`u la caract´erisation du noyau.
Corollaire. Consid´erons S0Γ!
ρ,σ comme une extension de Z!
ρ,σ = M![0] par Lρ × Lσ ≃
Z/6Z × Z/4Z, donc (en ´ecrivant Lρ ≃µ × L−ρ ≃Z/3Z × Z/2Z) une extension de
Z/2Z
| {z }
= µ
× Z/3Z
| {z }
= L−ρ
× Z/4Z
| {z }
Lσ
.
Cette extension correspond donc canoniquement `a trois exten-
sions, par µ, L−ρ, Lσ respectivement. L’extension par L−ρ × Lσ est munie d’une section
canonique. Il reste une extension (c’est justement Sπ
0 Γ!
ρ,σ) de Z!
ρ,σ par µ.
Cette extension correspond justement `a l’ambiguit´e de signe pour choisir un α = π∧au
dessus de ˜α ∈π∧/ ± 1 d´eﬁni par u ∈Z!
ρ,σ = M![0], qui se reﬂ`ete par l’ambiguit´e `a choisir
le signe pour a ∈N ′
ρ, li´e `a α par (51),
(58)
a = ε3(τ ′)α−1u ,
α = ua−1ε3(τ ′) .
Nous avons pu lever cette ambiguit´e par l’exigence α ∈π∧
0 τ = {1, τ} × π∧
0 , et nous venons
de constater que ce choix, pour canonique qu’il soit, n’est pas multiplicatif. En mˆeme
temps, on trouve l’explicitation compl`ete de α′′ (normalis´e canoniquement par la condition
α′′ ∈π∧
0 τ) associ´e `a u′′ = u′u, en termes de α′ (associ´e `a u′) et α (associ´e `a u) ´egalement
normalis´es en termes de a′, a. En eﬀet, la proposition p. 598 nous dit dans quels cas
exactement on a
(59)
a′′ = a′a ,
savoir si et seulement si on a
(59 bis)
ε3(u) = 1
ou
ε2(u′)ε3(u′) = 1 .
Mais on sait maintenant qu’en tous cas on doit avoir
(60)
a′′ = εa′a ,
ε ∈{±1} ,
et on trouve maintenant que ε = +1 si et seulement si on est dans le cas (59 bis), [ε =]−1
dans le cas contraire, i.e. si ε3(u) = −1 et ε2(u′)ε3(u′) = +1. En r´esum´e :
Corollaire.
Soient u, u′ ∈M![0], d’o`u u′′ = u′u, soient α, α′, α′′ ∈π∧
0 τ associ´es
(d´eﬁnis par u(ρ) = int(α)ρ etc.), et posons
[page 601]
(61)
a = ε3(τ ′)α−1u ,
a′ = ε′
3(τ ′)α′−1u′ ,
a′′ = ε′′
3(τ ′)α′′−1u′′ ,
o`u
ε3(τ ′) =



1
si
ε3
=
1
τ ′
si
ε3
=
−1
,
et de mˆeme pour ε′
3(τ ′), ε′′
3(τ ′) ,
et o`u
ε3 = ε3(u) = ε3(χ(u)) ,
et de mˆeme pour ε′
3, ε′′
3
– donc ε′′
3 = ε3ε′
3. On a alors
(62)
a′′ = εa′a ,
avec ε ∈{±1} ,


---

68
et
(63)



ε
=
+1
si et seulement si
ε3 = 1 ou ε′
2ε′
3 = 1 , donc
ε
=
−1
si et seulement si
ε3 = −1 et ε′
2ε′
3 = −1 .
On aura donc
(∗)



α′′
=
u′′a′′−1ε′′
3(τ ′)
=
εu′ua−1a′−1ε3(τ ′)ε′
3(τ ′) .
Je pr´esume qu’on aura
(64)
α′′ = εu′(α)α′ ,
(81)
o`u ε [est] donn´e par (63).
En eﬀet,



α
=
ua−1ε3(τ ′)
α′
=
u′a′−1ε′
3(τ ′) ,
d’o`u
u′(α)
=
u′ua−1ε3(τ ′)u′−1
u′(α)α′
=
u′ua−1 ε3(τ ′) ̸u′−1 ̸u′a′−1
|
{z
} ε′
3(τ ′) ,
la formule (64), en vertu de (∗), prend donc la forme
a′−1ε3(τ ′) = ε3(τ ′)a′−1 ,
i.e.
[ε3(τ ′), a′−1] = 1 ,
elle n’est pas toujours v´eriﬁ´e si ε3 = −1, i.e. ε3(τ ′) = τ ′, o`u elle repr´esente encore une
restriction draconienne sur a′. La formule toujours correcte est
α′′ = (εu′(α)α′) · ε′
3(τ ′)([a′, ε3(τ ′)])
|
{z
}
= [ε′
3(τ ′)(a′),ε3(τ ′)]
.
I.e. comme ε′
3(τ ′)a′ = α′−1u′ (61), la formule un peu alambiqu´ee (82) :
(65)
α′′ = (εu′(α)α′) · [ α′−1u′
| {z }
= ε′
3(τ ′)a′
, ε3(τ ′)]
(o`u ε ∈{±1} d´eﬁni dans (63)).
Il reste `a examiner la question si l’extension S0Γρ,σ de Z!
ρ,σ ≃M![0] par µ = {±1} est
triviale ou non, tenant compte du fait que ses restrictions `a Z!′
ρ,σ et `a Z!′′′
ρ,σ sont triviales.
Soient Sπ
0 Γ!′
ρ,σ, Sπ
0 Γ!′′′
ρ,σ les images inverses de Z!′
ρ,σ, Z!′′′
ρ,σ dans Sπ
0 Γ!
ρ,σ, donc
(66)



Sπ
0 Γ!′
ρ,σ
=
Sπ
0 Γ!
ρ,σ ∩Γ!′
ρ,σ
Sπ
0 Γ!′′′
ρ,σ
=
Sπ
0 Γ!
ρ,σ ∩Γ!′′′
ρ,σ ,
81Pas vrai en g´en´eral.
82Sic ! Voil`a le monstre qui m’a fait passer par des sueurs froides pendant une semaine ou deux !


---

69
et on a des suites exactes d’extensions centrales
(67)



1
-
µ
-
Sπ
0 Γ!′
ρ,σ
-
Z!′
ρ,σ
-
1
1
-
µ
-
Sπ
0 Γ!′′′
ρ,σ
-
Z!′′′
ρ,σ
-
1 ,
qui sont scind´ees par des sous-groupes not´es respectivement Sπ0
0 Γ!′
ρ,σ, Sπ0
0 Γ!′′′
ρ,σ, de sorte
qu’on a
(68)



Sπ
0 Γ!′
ρ,σ
≃
Sπ0
0 Γ!′
ρ,σ × µ
Sπ
0 Γ!′′′
ρ,σ
≃
Sπ0
0 Γ!′′′
ρ,σ × µ .
[page 602]
Je me pose la question si ces sous-groupes
(69)



Sπ0
0 Γ!′
ρ,σ
⊆
Sπ
0 Γ!′
ρ,σ
⊆
Sπ
0 Γ!
ρ,σ
Sπ0
0 Γ!′′′
ρ,σ
⊆
Sπ
0 Γ!′′′
ρ,σ
⊆
Sπ
0 Γ!
ρ,σ
(83)
sont invariants dans Sπ
0 Γ!
ρ,σ, ce qui signiﬁerait aussi (passant alors au quotient par ces
sous-groupes) que l’extension Sπ
0 Γ!
ρ,σ de Z!
ρ,σ par µ, scind´ee sur Z!′
ρ,σ et sur Z!′′′
ρ,σ, provient
en fait (avec lesdits scindages) d’extensions de Z!
ρ,σ/Z!′
ρ,σ (≃±1) et de Z!
ρ,σ/Z!′′′
ρ,σ (≃±1)
par µ, qu’il faudrait ensuite caract´eriser (comme trivial ou non trivial). Comme les sous-
groupes en question sont distingu´es dans Sπ
0 Γ!′ [= Sπ
0 Γ!′
ρ,σ etc.] resp. Sπ
0 Γ!′′′, si x est un
´el´ement de Sπ
0 Γ! qui n’est pas dans Sπ
0 Γ!′ resp. Sπ
0 Γ!′′′, dire que Sπ0
0 Γ!′ (resp. Sπ0
0 Γ!′′′) est
distingu´e dans Sπ
0 Γ! tout entier signiﬁe simplement qu’il est normalis´e par x.
1◦) Cas de Sπ0
0 Γ!′ dans Sπ
0 Γ!. On prendra
(70)



x = (u0, a0, b0) avec u0 = τ, d’o`u ε3(u0) = ε2(u0) = χ(u0) = −1,
α0 = τ, β0 = 1, a0 = ε3,0(τ ′)α−1
0 u0 = τ ′, b0 = β−1
0 u0 = τ,
donc
x = (u0 = τ, a0 = τ ′, b0 = τ) ,
donc on a
x ∈Sπ0
0 Γ!′′′ ⊆Sπ
0 Γ
et
x ̸∈Sπ
0 Γ!′ ,
et il faut voir si x normalise Sπ0
0 Γ!′. Soit
(71)
u = ( u
|{z}
∈Z
,
a
|{z}
∈N ′ρ
,
b
|{z}
∈N ′σ
) ∈Sπ0
0 Γ!′ ,
i.e.



u ≡a ≡b
(π0)
ε3(u) = 1
,
et calculons
x u x−1 = x u x = (τ(u), τ ′(a), τ(b)) ,
est-il dans Sπ0
0 Γ′ (et non seulement dans Sπ
0 Γ′), i.e. a-t-on
(72)
τ(u) ≡τ ′(u) ≡τ(b)
(π0)
?
83Sous-groupes d’indice 4 dans Sπ
0 Γρ,σ.


---

70
La relation τ(u) ≡τ(b) ≡τ(a) est cons´equence imm´ediate de (71), donc (72) ´equivaut `a
τ ′(a) ≡τ(a)
(π0) ,
i.e.
σ−1(τ(a)) = τ(a) ,
i.e.
(73)
[ ˙σ, τ(a)˙] = 1
dans S/π0 .
Ou encore, en vertu de (35 bis),
ε2(τ(a)) = 1 ,
i.e.
ε2(a) = 1 ,
ou enﬁn (comme a ≡u
(π0))
(74)
ε2(u) = 1 .
Cette condition n’est pas cons´equence de la condition ε3(u) = 1, ce qui montre que Sπ0
0 Γ!′
n’est pas invariant dans Sπ
0 Γ!.
[2◦)] Sπ0
0 Γ!′′′ est-il invariant dans Sπ
0 Γ! ? Soit
(75)
x = (u0, a0, b0) ∈Sπ0
0 Γ! ∖Sπ
0 Γ!′′′ ,
donc
a)



ε3(u0)
=
1
ε2(u0)
=
−1
b)
u0 ≡b0 ≡a0
(π0) ,
[page 603]
et ´etudions son action sur
(76)
u = (u, a, b) ∈Sπ0
0 Γ!′′′







a)
ε2(u)
| {z }
= ε2
ε3(u)
| {z }
= ε3
= 1
b)
u ≡b ≡ε3(σ)a
(π∧
0 ) .
On a
(77)
x u x−1 = (u0(u), a0(a), b0(b))
et la relation x u x−1 ∈Sπ0
0 Γ!′′′ s’´ecrit
(78)
u0(u) ≡b0(b) ≡ε′
3(σ) · a0(a)
(84) .
Or les relations (75 b) et (76 b) impliquent aussitˆot
u0(u) ≡b0(b) ≡a0(ε3(σ) · a)
|
{z
}
= ε3[a0(σ)]·a0(a)
,
donc la relation (78) ´equivaut aussi `a
(79)
ε3[σ] ≡ε3[a0(σ)] ,
84NB ε3(u0(u)) = ε3(u).


---

71
ce qui est automatiquement v´eriﬁ´ee si ε3 = 1, et pour ε3 = −1 revient `a
(80)
σ ≡a0(σ)
(π∧
0 ) ,
i.e.
ε2(a0) = 1 ,
i.e.
ε2(u0) = 1 ,
relation qui est fausse par l’hypoth`ese (75 a). Donc on trouve encore Sπ0
0 Γ!′′′ non invariant
dans Sπ
0 Γ!. Par contre, posons
(81)





















S0Γ0
=
Ker(S0Γ0
-
(ε2,ε3) µ × µ)
=
S0Γ! ∩S0Γ!
=
S0Γ!′ ∩S0Γ!′′
=
S0Γ!′′ ∩S0Γ!′′
[85]
Sπ
0 Γ0
=
S0Γ! 0 ∩Sπ
0 Γ!
Sπ0
0 Γ0
=
S0Γ! 0 ∩Sπ0
0 Γ! ,
de sorte qu’on a une suite exacte
(82)
1
- µ
- Sπ0
0 Γ! 0
- S0Γ! 0
- 1 ,
canoniquement scind´ee par Sπ0
0 Γ0 – on trouve donc
(82)
Sπ
0 Γ! 0 = Sπ0
0 Γ! 0 × µ
[86] .
Ceci pos´e, les calculs pr´ec´edents montrent que Sπ0
0 Γ! 0, qui est d’indice 8 dans Sπ
0 Γ!, est
un sous-groupe invariant. En r´esum´e :
Proposition. Consid´erons les sous-groupes Sπ0
0 Γ!′, Sπ0
0 Γ!′′′, Sπ0
0 Γ! 0 de Sπ
0 Γ! (d’indices 4,
4, 8), qui sont les images des restrictions respectives Z!′, Z!′′′, Z! 0 de la section ensembliste
A d´eﬁnie par (51), (52) de Sπ
0 Γ! sur Z = M[0] - qui est multiplicative sur ces sous-groupes,
et d´eﬁnit donc des scindages des images inverses Sπ
0 Γ!′, Sπ
0 Γ!′′′, Sπ
0 Γ! 0 de Z!′, Z!′′′, Z! 0
dans Sπ
0 Γ! :
(83)
Sπ
0 Γ!′ ≃Sπ0
0 Γ!′ × µ ,
Sπ
0 Γ!′′′ ≃Sπ0
0 Γ!′′′ × µ ,
Sπ
0 Γ! 0 ≃Sπ0
0 Γ! 0 × µ .
On a alors ceci :
a) Sπ0
0 Γ!′, Sπ0
0 Γ!′′′ ne sont pas distingu´es dans Sπ
0 Γ! (87).
b) Sπ0
0 Γ! 0 est distingu´e dans Sπ
0 Γ!, de sorte que l’extension Sπ
0 Γ! de Z! ≃M![0] par
µ est canoniquement isomorphe `a l’image inverse d’une extension centrale (savoir
Sπ
0 Γ!/Sπ0
0 Γ! 0) de Z!/Z! 0 ≃µ × µ par µ.
[page 604]
Examinons cette extension centrale
(84)
1
- µ
-
E
|{z}
≃Sπ
0 Γ!ρ,σ/Sπ0
0 Γ! 0
ρ,σ
-
(ε3,ε2) µ × µ
- 1 ,
85[?, les S0Γs `a droite manquent partiellement sur la copie.]
86[Deux fois (82).]
87Ce qui implique qu’il n’existe pas de section (multiplicative) de l’extension Sπ
0 Γ de Z! par Γ, qui
co¨ıncide avec A sur Z!′ ou sur Z!′′′.


---

72
s’ins´erant dans le diagramme d’extensions
(85)
1
- µ
- E
- µ×µ
- 1
6
6
6
(ε3,ε2)
1
- µ
- Sπ
0 Γ!
ρ,σ
- Z!
ρ,σ ≃M![0]
?
  ?
  ?
  1
- Lρ×Lσ
- S0Γ!
ρ,σ
- Z!
ρ,σ
- 1 .
L’int´erˆet de (84) est qu’elle permet de r´ecup´erer l’extension S0Γ!
ρ,σ de Z!
ρ,σ par Lρ × Lσ,
par la loi covariante-contravariante dans le foncteur ‘extensions’, via
(86)
Z!
ρ,σ
-
(ε3,ε2) µ × µ ,
µ
-

Lρ × Lσ
−1
-
(ρ3, σ2)
(‘homomorphisme diagonal’) ,
ainsi que la sous-extension Sπ
0 Γ!
ρ,σ de celle-ci (de Z!
ρ,σ par µ).
´Etudions d’abord l’ordre des ´el´ements de E – ils sont ´evidemment diviseurs de 4, sont-ils
tous d’ordre 2 (ou 1) ? Soit donc
(87)
u = ( u
|{z}
∈Z
,
a
|{z}
∈N ∗
ρ
,
b
|{z}
∈N ∗
σ
) ∈Sπ
0 Γ! ,
ı.e.



u
≡
b
(π∧
0 )
u
≡
ε3[σ]a
(π∧)
(88) .
Je veux examiner si u2 ∈Sπ0
0 Γ! 0. ´Evidemment
u = (u2, a2, b2) ∈Sπ
0 Γ! 0 ,
il reste `a voir si u2 ∈Sπ0
0 Γ!, i.e. si on a non seulement u2 ≡b2 (π0) et u2 ≡a2 (π∧) – ce
qui est clair et exprime simplement u2 ∈Sπ
0 Γ – mais mˆeme
(88)
u2 ≡a2
mod π∧
0
(?) .
La relation
u ≡ε3[σ] · a
mod π
s’´ecrit aussi
u ≡±ε3[σ] · a
mod π0
et implique
u2 ≡ε3[σ] a ε3[σ] a
mod π0 ,
ce qu’on peut ´ecrire
(89)
u2 ≡mod π∧
0 ε3ε3[σ](a) · a =



a2
si
ε3
=
1
−σ(a) · a
si
ε3
=
−1
.
88NB Pour ´eviter des confusions, on ´ecrit ε3[σ], ε3[τ ′] etc. au lieu de ε3(σ), ε3(τ ′) pour σν3, τ ′ν3 etc.


---

73
Donc (88) est vraie si ε3 = 1, tandis que pour ε3 = −1, elle ´equivaut `a
σ(a) ≡−a
(π∧
0 ) ,
i.e.
[σ, a]˙ = −1
dans S/π0 ,
i.e.
ε2(a)
| {z }
= ε2(u)
= −1 ,
i.e. ε2(u)ε3(u) = 1 .
Donc on trouve :
Proposition. Soit x ∈E (cf. (89)). Pour que l’on ait x2 = 1, il faut et il suﬃt qu’on ait
ε3(x) = 1 ou ε2(x)ε3(x) = 1, i.e. que l’on ait
(90)
x ∈E′ ∪E′′′ ,
[page 605]
o`u
(91)
E′ = {x ∈E | ε3(x) = 1} ,
E′′′ = {x ∈E | ε2(x)ε3(x) = 1} .
Corollaire 1. E a exactement deux ´el´ements d’ordre 4, qui sont les deux ´el´ements de E
au dessus de l’´el´ement (−1, 1) de µ × µ. Ces deux ´el´ements sont inverses l’un de l’autre,
ce sont les deux g´en´erateurs du seul sous-groupe cyclique d’ordre 4 de E, qui n’est autre
que E′′ = {x ∈E | ε2(x) = 1}.
Corollaire 2. L’extension E n’est pas scind´ee.
Car ´etant centrale, elle serait isomorphe `a (µ × µ) × µ, donc ses ´el´ements seraient d’ordre
qui divise 2.
Nous pouvons regarder maintenant E comme extension de E/E′′ ≃{±1} = µ par E′′
(≃Z/4Z). Il faudrait d’abord expliciter l’op´eration de E/E′′ = µ sur E′ – l’´el´ement −1
d’ordre 2 de µ induit un automorphisme involutif de E′′ ; d’ailleurs Aut(E′) ≃(Z/4Z)∗≃
{±1}, donc l’automorphisme en question est la multiplication par un signe ±1, qu’il faut
d´eterminer. On va nommer [un] repr´esentant de −1 ∈E/E′′ [et] prendre l’´el´ement de
E provenant de
(92)
x = (u0 = τ, a0 = τ ′, b0 = τ) ∈Sπ0
0 Γ!′′′
(cf. (70)) ,
qu’on va faire op´erer sur l’image d’un
(93)
u = (u, a, b) ∈Sπ
0 Γ! ,
avec















ε3(u)
=
−1
ε2(u)
=
1
u
≡
b
mod π∧
0
u
≡
σa
mod π∧
(qui est un g´en´erateur de E′′). On aura donc
x(u) = (τ(u), τ ′(a), τ(b)) ≡(1, ε, ε)(u, a, b)
|
{z
}
= (u,εa,εb)


---

74
modulo Sπ0
0 Γ0, avec un signe ε ∈{±1} `a d´eterminer. La condition de congruence s’´ecrit
( uτ(u)−1, εaτ ′(a)−1, εbτ ′(b)−1 ) ∈Sπ0
0 Γ0 ,
qu’on soit dans Sπ
0 Γ! 0 est ´evident et valable quel que soit le choix du signe ε ; c’est la
condition de congruence qui distingue Sπ0
0 Γ! de Sπ
0 Γ! qui est essentielle, savoir
(94)
uτ(u)−1 ≡εaτ ′(a)−1
(π∧
0 ) .
La diﬃcult´e dans cette approche vient du fait que les seuls ´el´ements de M qu’on sache
expliciter sont ceux qui proviennent de S ≃GL(2, Z) lui-mˆeme, or pour ceux-ci, on a
ε2(u)ε3(u) = 1, alors que le u ci-dessus doit satisfaire ε2(u) = 1, ε3(u) = −1, donc
ε2(u)ε3(u) = −1. On peut d’autre part travailler dans le quotient GL(2, ˆZ) de M, et y
prendre
(95)
u =
 µ 0
0 1

avec µ ∈ˆZ∗,



µ ≡−1 (3)
µ ≡
1 (4)
i.e.
µ ≡
5 (12) ,
tandis que τ correspond `a la matrice
τ =
 −1 0
0 1

;
[page 606]
on aura de toutes fa¸cons
uτ(u)−1 = 1 .
Soit d’autre part dans GL(2, ˆZ)
(96)



a = τ ′a0 ,
a0 = cρ + d ,
c2 + cd + d2 ∈ˆZ∗
τ ′ =
 0 1
1 0

,
ρ =
 0 1
−1 1

,
donc
(97)
a =
 0 1
1 0
   d
c
−c c+d

=
 −c c+d
d
c

et
(98)
µ = −(c2 + cd + d2)
(89) .
On travaillera avec le sous-groupe ferm´e π∧
0 dans SL(2, ˆZ) engendr´e par
−l0 = −
 1 −2
0
1

,
−l1 = −
 1 0
2 1

,
−l∞= −
 3 −2
2 −1

et dans le groupe quotient de GL(2, ˆZ) par π∧
0 , qui est extension de ˆZ∗par
SL(2, ˆZ)/π∧
0 ≃SL(2, Z)/π0 ≃{(ρ, σ) | ρ6 = σ4 = 1, ρ3 = σ2, σ(ρ) = ρ−1}
[c.`a.d. ⟨ρ, σ | . . . ⟩], et mˆeme produit semi-direct grˆace `a
T0 = {
 ξ 0
0 1

| ξ ∈ˆZ∗}
det
≃ˆZ∗
89Un peu bref, cf. plus bas . . .


---

75
op´erant par l’interm´ediaire de ε2(ξ) [?] (cf. p. 593, 594 – formules (34), (35), (35 bis)).
On doit supposer
(99)
σa ≡u
(π∧) ,
o`u σ =
 0 −1
1
0

,
donc
(100)
σa =
 −d
−c
−c c+d

.
La relation (99) s’´ecrit
(102)



a ≡u
(SL(2, ˆZ)) ,
i.e.
det σa = det u ,
i.e. (98)
σa ≡u
(2)
[90] ,
et cette derni`ere congruence s’´ecrit
(103)
c ≡0
(2) ,
d ≡1
(2)
(91) .
NB On ne peut avoir la congruence mod 4 : σa ≡u
(4) , car on aurait µ ≡−d ≡−1
(4),
ce qui est contraire `a l’hypoth`ese (95) : µ ≡1
(4).
Revenant `a la relation (94), on trouve ceci :
Lemme. Soient c, d ∈ˆZ satisfaisant
(104)
µ
def
= −(c2 + cd + d2) ∈ˆZ∗
(92) ,
(105)
µ ≡1
(4)
(i.e. c2 + cd + d2 ≡−1
(4)) ,
(106)
c ≡0
(2) ,
d ≡1
(2) .
Soit
(107)
a = τ ′(cρ + d) =
 −c c+d
d
c

∈GL(2, ˆZ)
(entier de d´eterminant µ). Alors on a une congruence
(108)
aτ ′(a)−1 ≡ε
mod π∧
0 ⊆GL(2, ˆZ) ,
et le signe ε ∈{±1} ne d´epend pas des choix faits pour c, d.
[page 607]
C’est le moment de le calculer ! Reprenant
a0 = cρ + d ∈Zρ ,
on aura
a = τ ′a0 ,
τ ′(a) = a0τ ′ ,
aτ ′(a)−1 = τ ′a0τ ′−1a−1
0
= τ ′(a0)a−1
0
,
90[(101) n’existe pas.]
91−d ≡µ (2) en est une cons´equence, car µ ≡1 ≡−1
(2).
92NB On aura n´ecessairement µ ≡−1
(3).


---

76
o`u



τ ′(a0) = cρ−1 + d =
ta0
a−1
0
=
ta0/ det a0 = −1
µ(cρ−1 + d) ,
(93)
donc
aτ ′(a)−1 = τ ′(a0)a−1
0
= −1
µ(cρ−1 + d)2 =
1
c2 + cd + d2(cρ−1 + d)2 .
Or on a
(cρ−1 + d)2 = c2 ρ−2
|{z}
= −ρ
+ 2 c d ρ−1
|{z}
= 1−ρ
+ d2 = −(c2 + 2cd)ρ + (2cd + d2) .
Or
c
≡
0
(2)
=⇒
c2, 2cd
≡
0
(4)
d
≡
1
(2)
=⇒
d2
≡
1
(4) ,
donc
(∗)
(cρ−1 + d)2 ≡1
(4) ,
et comme par hypoth`ese
c2 + cd + d2 ≡−1
(4) ,
on aura
(109)
aτ ′(a)−1 =
1
c2 + cd + d2(cρ−1 + d)2 ≡−1
(4) .
Donc on a prouv´e, en fait :
Proposition. Soient c, d ∈ˆZ tels que ξ
def
= c2 + cd + d2 ∈ˆZ∗, soit
a = τ ′(cρ + d) =
 −c c+d
d
c

∈GL(2, ˆZ) ,
supposons
σa ≡
 ξ 0
0 1

(2)
(94) ,
i.e.
c ≡0
(2) ,
d ≡1
(2) .
Alors on a (posant τ ′ =
 −1 0
0 1

)
aτ ′(a)−1 ≡ε2(ξ)
(4)
(a fortiori on a la congruence modulo π∧
0 ).
Corollaire.
L’extension E de µ × µ par µ (84), ou de µ par E′′ ≃Z/4Z, est non
commutative.
Mais voici une fa¸con de le voir sans calcul. Si l’extension ´etait commutative, sa classe
d’isomorphie serait donn´ee par un Ext1
Z (ou un Ext1
Z/4Z). Or le foncteur Ext1(−, µ) est
93On pose dans M2(ˆZ)
tu = (Tr u) −u ,
et on aura tρ = ρ−1 (plus g´en´eralement tu = u−1 si det u = 1)
94NB σ =
 0 −1
1
0



---

77
additif. Comme la restriction de l’extension aux sous-groupes E′/µ et E′′′/µ de µ × µ est
triviale, et que µ × µ est la somme directe de ces sous-groupes (qui sont respectivement
1 × µ et le sous-groupe diagonal), il s’ensuivrait que l’extension serait triviale, or on a vu
que ce n’est pas le cas.
La structure du groupe E s’explicite ais´ement, p.ex. en tant qu’extension de E/E′′ ≃µ
par E′′ ≃Z/4Z. Choisissons un ´el´ement quelconque [x] de E ∖E′′, il est d’ordre 2 (les
seuls ´el´ements d’ordre 4 ´etant dans E′′), de sorte que l’on a
[page 608]
(110)
E ≃{1, x} · E′′
|
{z
}
(semi-direct)
.
Notons que si x op´erait trivialement sur E′′, i.e. si E ´etait isomorphe au produit, alors
pour un ´el´ement u de E′′ d’ordre 4, x · u serait d’ordre 4, ce qui est absurde (troisi`eme
d´emonstration du fait que E/E′′ ≃µ op`ere non trivialement sur E′′). Or du seul fait que
l’op´eration de {1, x} sur E′′ est non triviale, elle est connue, donc la structure de E est
d´etermin´ee – en fait on a
(111)
E ≃D4 .
Il y a un choix privil´egi´e de x, en prenant pour x l’´el´ement
(112)



τε
def
= τS0Γ mod Sπ0
0 Γ0 , o`u bien sˆur
τS0Γ = (τ, τ ′, τ) ,
de sorte que l’on a une repr´esentation canonique
(113)
E ≃
{1, τE} · E′′
|
{z
}
produit semi-direct
(95) .
L’homomorphisme E
- µ × µ se r´ecup`ere par ses restrictions aux deux facteurs
(114)















µ ≃{1, τε}
- µ × µ ,
τε
- (−1, −1)
(homomorphisme diagonal)
E′′
-
|
{z
}
l’unique homomorphisme
non trivial E′′
- µ,
d´eduit de l’isomorphisme
E′′
2
def
= E′′/2E′′
-
∼
µ
µ × {1}
-

µ × µ .
Le fait que E ne soit par commutative s’exprime aussi par le fait que l’homomorphisme
canonique
(115)
Eab
-
∼
µ × µ
est un isomorphisme, i.e. que le sous-groupe noyau µ de Eab
- µ × µ est aussi le sous-
groupe des commutateurs.
95E′′ ≃Z/4Z, τE(u) = u−1 pour u ∈E′′.


---

78
On a vu que l’extension E de µ×µ par µ n’est pas scind´ee, mais qu’en est-il de son image
inverse, l’extension Sπ
0 Γ! de Z! ≃M[0] par µ ? A priori, nous savons seulement qu’il n’y
a pas de scindage de cette extension qui prolonge le scindage canonique A dont on dispose
au dessus de Z0 = Ker(Z!
-
(ε3,ε2) µ × µ). Je pr´esume que mˆeme Sπ
0 Γ′′, extension de Z!′′ par
µ, est non triviale, et mˆeme l’extension qu’elle induit du sous-groupe
Γ′
Q = ΓQ ∩Γ′∼
Q
|{z}
≃M[0]′
⊆M[0] ⊆M![0] = Z! .
Il serait int´eressant d’identiﬁer, plus pr´ecis´ement, l’extension par ΓQ qu’elle induit, qui
correspond `a un ´el´ement canonique
(115)
c ∈H1(Spec Q, µ2) ⊆Br(Q) ,
[page 609]
sauf erreur on aura
(115)
c =
ξ′ξ′′
|{z}
cup-produit
[96] ,
o`u ξ, ξ′′
∈H2(Q, µ2) sont les ´el´ements qui d´ecrivent respectivement les extensions
Q(
3√
1) = Q(√−3), et Q(
√
3) – contenues l’une et l’autre, ainsi que Q(√−1) = Q(i),
dans l’extension biquadratique Q(
i
|{z}
= 2√−1
,
j
|{z}
= 3√
1
) = Q(
12√
1) , le corps des racines 12i`emes
de l’unit´e (dont le groupe de Galois est (Z/12Z)∗≃(Z/3Z)∗× (Z/4Z)∗≃µ × µ). Il doit
ˆetre trivial – quand on connaˆıt un peu les fondements – que c ainsi explicit´e est ̸= 0, et
n’est pas non plus scind´e en passant `a Q(i), le troisi`eme larron.
Consid´erons maintenant le plongement central
(116)
µ
-

iρ,µ
S0Γ!
ρ,σ = Z!
ρ,σ ×Υ N ∗
ρ ×Υ N ∗
σ
ε
-
(1, ε, 1)
(97)
`a valeurs dans
Ker(S0Γ!
ρ,σ
- Z!
ρ,σ) ≃Lρ × Lσ ,
on a donc un homomorphisme canonique de rel`evement
(117)
M![0] ≃Z!
ρ,σ ≃Sπ
0 Γ!
ρ,σ/µ
- S0Γ!
ρ,σ/iρ,µ(µ) ,
96[Trois fois (115).]
97NB
Z
≃
M[0]
Υ
≃
Γ∼
Q .


---

79
qui s’explicite en termes de deux homormorphismes canoniques fondamentaux (98)
(118)
Z!
ρ,σ
|{z}
≃M[0] ≃Γ∼
Q·Lπ
0
-
a
N ∗
ρ /µ ,
Z!
ρ,σ
-
b
N ∗
σ ,
o`u, je rappelle
(119)



















N ∗
ρ
=
{u ∈M | u(ρ) = ρε3(u)}
⊆
M = N ∼
1,1 ≃Γ∼
Q · S+
|{z}
= SL(2,Z)∧
N ∗
σ
=
{u ∈M | u(σ) = σε2(u) (= ε2(u)σ)}
⊆
M .
Les applications a, b sont donn´ees par les formules (cf. 51)
(120)



a(u) = a = ε3[τ ′]α−1u ,
b(u) = b = β−1u ,
i.e.
α = ua−1ε3[τ ′] ,
β = ub−1 ,
o`u α ∈π∧
0 τ, β ∈π∧
0 sont caract´eris´es par
(121)
u(ρ) = int(α)(ρ) ,
u(σ) = ε2(σ) int(β)(σ) .
Les quantit´es a = a(u) ∈N ∗
ρ /µ, b = b(u) ∈N ∗
σ sont caract´eris´es en termes de u ∈Z! (a
au signe pr`es seulement) par les congruences
(122)
u ≡b
(π∧
0 ) ,
u ≡ε3[σ]a
(π∧) ,
qui impliquent a fortiori (r´eduisant modulo S+ ∧) qu’on a commutativit´e dans
[page 610]
(123)
Z!
ρ,σ

*
δρ
N ∗
ρ /{±1}
HHHH
j Υρ,σ ≃Γ∼
Q
.
-
δZ
HHHH
j
δσ
N ∗
σ

*
Il serait temps de rectiﬁer la confusion (p. 594) entre Z = Zρ,σ ⊆M∼
0,3, et Z! = Z!
ρ,σ =
Z ∩M! ∼
0,3. On a en eﬀet
(124)
Zρ,σ ≃
M(0) · LS
0
|
{z
}
semi-direct, ⊆M
-
∼
M∼
0,3 · L
S0,3
0
|
{z
}
⊆M∼
0,3
(125)
Z!
ρ,σ ≃Z!
ρ,σ ∩M! =
M(0) · Lπ
0
|
{z
}
semi-direct, ⊆M
-
∼
M∼
0,3(0) · L
π0,3
0
|
{z
}
⊆M∼
0,3
98Ceci m´erite d’ˆetre explicit´e dans un th´eor`eme r´ecapitulatif . . .


---

80
[plut^ot Zρ,σ ∩M! ?]. Le lien entre les deux est donn´e par le diagramme
(126)
1
- Lπ
0
- Z!
ρ,σ
- Υρ,σ
- 1
?
  ?
  2
?
1
- LS
0
- Zρ,σ
- Υρ,σ
|{z}
≃M(0) ≃Γ∼
Q
- 1 ,
o`u Lπ
0
- LS
0 est l’inclusion d’indice 2 de
(127)
Lπ
0 =
l
ˆZ
0
|{z}
= (ε2
0)ˆZ
-

LS
0
= ε
ˆZ
0 .
Bien entendu, c’est bien sur Z!
ρ,σ, non sur Zρ,σ, qu’on a d´eﬁni (117), (118), d’o`u (123).
Je m’int´eresse `a la restriction des homomorphismes (123) au sous-groupe Lπ
0 de Z!
ρ,σ; la
caract´erisation (122) montre que l’homomorphisme induit
Lπ
0
- N ∗
ρ /{±1}
est trivial (car a en termes de u ne d´epend que de u modulo π∧), tandis que l’homomorphisme
induit
Lπ
0
- N ∗
ρ
se factorise par Lπ
0/Lπ0
0 ≃Z/2Z (car b en termes de u ne d´epend que de u modulo π∧
0 ).
Sa valeur b sur ˙l0 est caract´eris´ee par les conditions
b ∈N ∗
σ ,
b ≡l0
(π0) ,
qui sont satisfaites ´evidemment par b = −1. Donc il y a lieu d’introduire aussi, qu’on le
veuille ou non, le plongement central canonique
(128)
µ
-

N ∗
σ
−1
-
−1
et on a commutativit´e dans
(129)
Lπ
0
-

Z!
ρ,σ
?
?
Lπ
0/Lπ0
0
≃µ
-

N ∗
σ .
Donc on trouve, `a partir des deux homomorphismes (123)


---

81
[page 611]
de Z!
ρ,σ, par passage au quotient deux homomorphismes canoniques
(130)
Υρ,σ
- N ∗
ρ /{±1}
Γ∼
Q
Υρ,σ
- N ∗
σ/{±1} ,
qui sont en fait des sections de
N ∗
ρ /{±1}
- Υρ,σ
Γ∼
Q ∼
M(0)
N ∗
σ/{±1}
- Υρ,σ ,
de sorte qu’on trouve des d´ecompositions
(131)











N ∗
ρ /{±1}
≃
Υρ,σ · SZρ/{±1}
|
{z
}
= Lρ/{±1} ≃Z/3Z
N ∗
σ/{±1}
≃
Υρ,σ · SZσ/{±1}
|
{z
}
= Lσ/{±1} ≃Z/2Z
(produits semi-directs).
L’op´eration de Υρ,σ sur Lρ/{±1} ≃Z/3Z est donn´ee par le
caract`ere quadratique ε3, celle sur Lσ/{±1} ≃Z/2Z est donn´ee par le caracat`ere quadra-
tique ε2.
La sym´etrie de pr´esentation des deux homomorphismes (130) est un peu bidon – p.ex.
l’homomorphisme Γ∼
Q = Υρ,σ
- N ∗
σ/{±1} se remonte de fa¸con ´evidente en
(132)
Γ∼
Q = Υρ,σ
- N ∗
σ
6
≀
6
M(0)
-

M[0] = Z! .
Une autre fa¸con de le voir est de noter que
(132)
Υρ,σ ≃M!
0[0]/Lπ0
0
[99] ,


---

82
o`u
M!
0[0]
def
= M0(0) · Lπ0
0
-
| {z }
sous-groupe
d’indice 2
M![0] = M(0) · Lπ0
0 ;
or sur Lπ0
0 , l’homomorphisme induit par
M![0] = Z!
ρ,σ
- N ∗
σ
est trivial. Ainsi on a mˆeme un scindage de
(133)
1
- Lσ
- N ∗
σ
- Υρ,σ
|{z}
≃Γ∼
Q
- 1
en un produit semi-direct
N ∗
σ ≃Υρ,σ · Lσ ,
qu’il vaut mieux ´ecrire en caract´erisant le sous-groupe section en tant que sous-groupe de
Gρ,σ ≃M, soit donc
(134)
N ! ∗
0 σ
def
=
Im(M0[0]
- N ∗
ρ )
=
Im(M[0]
- N ∗
ρ )
=
{β−1u | u ∈M(0), β ∈π∧
0 tels que u(σ) = ε2(u) int(β)(σ)}
=
{v ∈N ∗
σ | ∃β ∈π∧
0 tel que βv ∈M[0] = NormM(L0) ∩M[100]} .
(101)
Posant
(135)
M!
0
def
= M(0) · π0
⊆
|{z}
indice 2
M!
def
= M(0) · π ,
[page 612]
de sorte qu’on a
(136)
M! ≃M!
0 × µ
(102) ,
on a donc
(137)



N ∗!
σ 0
=
N ∗
σ ∩M!
0
N ∗!
σ
def
=
N ∗
σ ∩M!
=
N ∗!
σ 0 × µ ,
99[Deux fois (132).]
100[Il est possible qu’il manque quelque chose ici.]
101NB On d´eﬁnit M! comme l’image inverse de M! ∼
0,3, i.e. le noyau de la repr´esentation canonique
M
- S+ ∧/π∧
|
{z
}
≃S3
-
∼
Aut(S+ ∧/π∧) .
102NB On a M!
0
-
∼
M! ∼
0,3.


---

83
et on trouve que
(138)
N ∗!
σ 0
-
∼
Υρ,σ = Γ∼
Q .
Posons pour abr´eger
(139)
M(1/2) = N ∗!
σ 0 ,
cf. (137) ,
on aura donc que M(1/2) est un groupe-section pour N ∗
σ, extension de Υρ,σ par Lσ, et a
fortiori pour M, extension de Υρ,σ par S+ ∧, et en mˆeme temps pour M!
0, M!.
(140)















M!
0
≃
M(1/2) · π∧
0
(103)
M!
≃
M(1/2) · π∧
M
≃
M(1/2) · S+ ∧
N ∗
σ
≃
M(1/2) · Lσ
h
Si on veut paraphraser en introduisant
(141)
N ∗!
ρ 0
def
= N ∗
ρ ∩M!
0 = {v ∈N ∗
ρ | ∃α ∈π∧
0 tel que αv
|{z}
= u
∈M(0)} ,
c’est donc l’ensemble des v qu’on peut associer `a des u ∈M(0) ⊆M![0] ≃Z!
ρ,σ, `a l’aide
de α ∈π∧
0 tel que α−1u ∈N ∗
ρ , i.e.
u(ρ) = int(α)(ρε3) ,
o`u ε3 = ε3(u) = ε3(v) .
Mais comme u(ρ) doit avoir mˆeme image dans S3 ≃S+ ∧/π∧que ρ, il faut qu’on ait
ε3 = 1, et alors α est l’´el´ement α(u) associ´e `a u, et v = α−1u est l’image canonique de u
dans N ∗
ρ . Ainsi on trouve :
Proposition :
L’homomorphisme N ∗!
ρ 0
- Υρ,σ = Γ∼
Q est injectif, et a pour image
Υ′
ρ,σ = {γ ∈Υρ,σ | ε3(γ) = 1}.
Corollaire. N ∗!
ρ 0 ⊆Z!
ρ, i.e. N ∗!
ρ 0 = Z!
0 ρ
def
= Zρ ∩M!
0.
Il est naturel de poser
(142)
N ∗!
ρ 0 = Z!
0 ρ = M(−) .
Comme N ∗!
ρ ⊇Z!
ρ ⊇µ, on voit que l’on a
(142)









N ∗!
ρ
=
N ∗!
ρ 0 × µ
(donc N ∗!
ρ = Z!
ρ)
∥
Z!
ρ
=
Z!
ρ 0 × µ
[104] .
103Attention, M! est invariant dans M, et M!
0 est invariant dans M!, mais non dans M, cf. plus bas.


---

84
Le sous-groupe Z!
0,ρ = M(−) est une section de M′ sur Υ′
ρ,σ ≃Γ′∼
Q , et ´etant contenu
dans M′!
0, M′!, M′, Z!
ρ, Zρ, on aura des d´ecompositions en produits semi-directs
(143)





















M′!
0
≃
M(−) · π0
M′!
≃
M(−) · π
M′
≃
M(−) · S
Z!
ρ
≃
M(−) × µ
Zρ
≃
M(−) × Lρ
. . .
i
[page 613]
Revenons au diagramme (130), je dis que l’homomorphisme
Υρ,σ
|{z}
= Γ∼
Q
;
- N ∗
ρ /{±1}
ne se rel`eve pas en un homomorphisme de Υρ,σ dans N ∗
ρ – en d’autres termes, que
l’extension Υ∼
ρ,σ de Υρ,σ par {±1} = µ qu’elle d´eﬁnit n’est pas triviale. Pour identiﬁer
cette extension, consid´erons le diagramme
(144)
M![0] = Z!
ρ,σ
-
can.
Υρ,σ = Z!
ρ,σ/Lπ
0
-
hom. (130) N ∗
ρ /{±1}
6
S0Γ!
ρ,σ
can., (u,a,b) - u








can.
(passage
au quotient)
S0Γρ,σ (sans !)
6
6
incl.
 


incl.
Sπ
0 Γ!
ρ,σ
- N ∗
ρ ,
qui montre que l’on a un diagramme de carr´es cart´esiens
(145)
M(0)
-

M![0] = Z!
ρ,σ
-
´epi
Υρ,σ
-

N ∗
ρ /{±1}
6
I
6
2
II
6
2
III
6
2
M(0)∼
-

Sπ
0 Γ!
ρ,σ
- Υ∼
ρ,σ
-

N ∗
ρ ,
o`u M(0)∼est d´eﬁni comme l’extension de M(0) par µ induite par l’extension Sπ
0 Γ!
ρ,σ de
M![0], qui s’identiﬁe donc aussi `a l’image inverse de l’extension Υ∼
ρ,σ de Υρ,σ par µ, par
l’isomorphisme compos´e M(0)
-
∼Υρ,σ. Donc l’extension Υ∼
ρ,σ de Υρ,σ par µ s’identiﬁe
104[Deux fois (142).]


---

85
essentiellement `a l’extension M(0)∼de M(0) par µ, dont on s’est convaincu plus au moins
qu’elle n’´etait pas triviale.
Voici une autre fa¸con d’obtenir l’homomorphisme canonique Υρ,σ
- N ∗
ρ /±1, et l’extension
Υ∼
ρ,σ de Υρ,σ. Consid´erons
(146)
N ∗!
ρ
= N ∗
ρ ∩M! .
On a alors
(147)
N ∗!
ρ ∩S+ = Ker(N ∗!
ρ
- Υρ,σ
|{z}
≃Γ∼
Q
) = Lρ ∩π = µ ,
d’autre part l’homomorphisme
(148)
N ∗!
ρ
- Υρ,σ
est ´epimorphique .
Car il suﬃt de voir que pour tout u ∈M(0) il existe un ´el´ement de N ∗!
ρ qui lui est congru
modulo S. Or on a u(ρ) = int(α)(ρ) avec α ∈π∧
τ = {1, τ} · π∧. Si ε3(u) = 1, i.e. α ∈π∧,
α−1u ∈Zρ ⊆N ∗
ρ fait l’aﬀaire. Si ε3 = −1, on aura
α = α0τ ,
α0 ∈π∧,
et on a
u(ρ) = α(ρ) = α0( τ(ρ)
|{z}
= σ(ρ−1)
) = α0(σ(ρ−1)) ,
donc
(σ−1α−1
0 u)(ρ) = ρ−1 ,
donc σ−1α−1
0 u ∈N ∗
ρ , OK.
[page 614]
Donc on a une suite exacte
(149)
1
- µ
- Z∗!
ρ
|{z}
≃Υ∼
ρ,σ
- Υρ,σ
|{z}
≃Γ∼
Q
- 1 ,
qui fait de Z∗!
ρ une µ-extension de Υρ,σ, d’o`u un homomorphisme canonique
Υρ,σ ≃Z∗!
ρ /µ
- N ∗
ρ /µ ,
qui, bien entendu, n’est autre que le premier homomorphisme (130).
9◦) R´ecapitulation sur le cas universel.
Finalement, j’ai l’impression que j’ai fait encore des larges d´etours et contorsions, pour
ﬁnalement me perdre dans les sables, et perdre un peu le ﬁl. Je vais donc r´ecapituler ce
qui me semble essentiel.
am
(1) Zρ,σ ≃M(0)·LS
0
= M[0] (op´erant sur S+ ∧par op´eration induite par l’adjoint).


---

86
On distingue dedans un sous-groupe d’indice 2
(2)
Z!
ρ,σ ≃M(0) · Lπ
0 .
On a
(3)
Gρ,σ ≃M ,
et, plus pr´ecis´ement, le diagramme
(4)
1
- L0
- Zρ,σ
- Υρ,σ
- 1
?
  ?
  1
- S+ ∧
- Gρ,σ
- Υρ,σ
- 1
s’identiﬁe au diagramme
(4 bis)
1
- LS
0
-
M(0)·LS
0
z }| {
M[0]
- Γ∼
Q
- 1
?
  ?
  1
- S+ ∧
- M
- Γ∼
Q
- 1 .
D’ailleurs, les homomorphismes
(5)
Υρ,σ

*
ε′
Υ=ερ
Υ
µ
- ˆZ∗
HHHH
j
ε′′
Υ=εσ
Υ
µ
s’identiﬁent `a
(5 bis)
Γ∼
Q

1
ε3
-
χ
PPPPPPP
q
ε2
ˆZ∗  
µ
@@
R
µ .
bmOn a
(6)
N ∗
σ = {u ∈M | u(σ) = σε2(u) ( = ε2(u) · σ = ε2[τ](σ) = ε2[τ ′](σ) )}
et
(7)















N ∗
σ ∩S∧
=
Dσ = {1, τ} · Lσ = {1, τ ′} · Lσ
N ∗
σ ∩S+ ∧
=
Lσ
( ≃Z/4Z )
N ∗
σ ∩π
=
µ
N ∗
σ ∩π0
=
{1} .


---

87
[page 615]
Posons
(8)



M!
0 = M(0) · π0 ⊆M! = M(0) · π = Ker(M
- S3) ,
de sorte que M! ≃M!
0 × µ
et
(9)



M(1/2)
def
= N ∗!
σ 0
def
= N ∗
σ ∩M!
0
N ∗!
σ
= N ∗
σ ∩M! ,
alors l’homomorphisme M
- Υρ,σ induit un isomorphisme
(10)
M(1/2) = N ∗!
σ 0
-
∼
Υρ,σ ,
donc on a des scindages en produits semi-directs
(11)





















M
≃
M(1/2) · S+ ∧
M!
≃
M(1/2) · π
M!
0
≃
M(1/2) · π0
N ∗!
σ
≃
M(1/2) · µ
N ∗
σ
≃
M(1/2) · Lσ ,
et
(12)
Υρ,σ
-
∼
M(1/2) = N ∗!
σ
-

N ∗
σ .
cmOn a
(13)
N ∗
ρ = {u ∈M | u(ρ) = ρε3(u)
( = ε3[τ ′](ρ) )}
et
(14)















N ∗
ρ ∩S∧
=
Dρ = {1, τ ′} · Lρ
N ∗
ρ ∩S
=
Lρ
( ≃Z/6Z )
N ∗
ρ ∩π
=
µ
N ∗
ρ ∩π0
=
{1} .
Soient
(15)
N ∗!
ρ 0
def
= N ∗
ρ ∩M!
0 ,
N ∗!
ρ
def
= N ∗
ρ ∩M! ;
on trouve
(16)
N ∗!
ρ 0 ⊆Zρ = CentrM(ρ) = CentrM(Lρ) ,


---

88
et on note aussi
(17)
N ∗!
ρ 0 = Z!
ρ 0 = M′(−) .
On voit que l’homomorphisme M
- Υρ,σ = Γ∼
Q induit un isomorphisme
(18)
M′(−) = Z!
ρ,0
-
∼
Υ′
ρ,σ
|{z}
def
= {γ∈Υρ,σ | ε3(γ)=1}
= Γ∼
Q ,
d’o`u on d´eduit un scindage en produits semi-directs (voire produits directs)
(19)





















M′
≃
M′(−) · S+ ∧
M′!
≃
M′(−) · π
M′!
0
≃
M′(−) · π0
Z!
ρ = N ∗!
ρ
≃
M′(−) × µ
Zρ
≃
M′(−) × Lρ .
[page 616]
Soit maintenant
(20)
µτ ′ = {1, τ ′} ⊆S∧,
alors µτ ′ normalise Lρ, car
τ ′(ρ) = ρ−1 ,
d’o`u
τ ′(Lρ) = Lρ ,
donc il normalise Zρ = CentM(Lρ), donc aussi Z!
ρ = Zρ ∩M! (puisque M! est invariant
dans M) = Z!
ρ,0 × µ = M′(−) × µ. D’ailleurs µτ ′ ∩Z!
ρ = µτ ′ ∩M! = {1}. Soit
(21)
N ?
ρ = µτ ′ · Z!
ρ = µτ ′ · ( Z!
ρ 0 × µ
| {z }
≃M(−)×µ ≃Γ′∼
Q×µ
)
|
{z
}
(produit semi-direct)
.
On fera attention que contrairement `a ce que pourrait sugg´erer cette ´ecriture, µτ ′ ne
normalise pas Z!
ρ,0 – sinon on aurait une d´ecomposition en produit N ?
ρ = N ?
ρ 0, o`u N ?
ρ,0 =
µτ ′ · Z?
ρ,σ, or il n’en est rien. On a une suite exacte
(22)
1
- µ
- N ?
ρ
- Υρ,σ
|{z}
= Γ∼
Q
- 1 ,
de sorte que N ?
ρ est une quasi-section de multiplicit´e 2 de l’extension N ∗
ρ
- Υρ,σ, ou de
M
- Υρ,σ = Γ∼
Q. Ainsi on trouve
(23)







M
=
N ?
ρ ∧µ2 S+ ∧
Nρ
=
N ?
ρ ∧µ2 Lρ ≃N ?
ρ × L−ρ
|{z}
≃Z/3Z
.


---

89
L’extension (22) de Υρ,σ par µ est l’extension not´ee Υ∼
ρ,σ dans la section pr´ec´edente, elle
est sˆurement non scind´ee. Elle donne naissance `a un homomorphisme canonique
(24)
Υρ,σ
-
∼
N ?
ρ /µ
- N ∗
ρ /µ .
Remarque. Pour bien faire, il faudrait expliciter l’op´eration de τ ′ sur
Z!
ρ ≃Z!
ρ 0 × µ
-
∼
Γ′∼
Q × µ ,
en termes de l’op´eration de l’image τΓ de τ ′ sur Γ′∼
Q par automorphisme int´erieur (NB τΓ
n’est autre que l’´el´ement de ΓQ ⊆Γ∼
Q ‘conjugaison complexe’) et d’un homomorphisme
de Γ′∼
Q dans µ, i.e. d’un ‘caract`ere quadratique’ de Γ′∼
Q – il y a fort `a parier que celui-ci
est justement ε2 – de sorte que Γ0 ∼
Q ≃Γ′∼
Q ∩Γ′′∼
Q apparaˆıt comme invariant par τ ′ . . . En
somme, il y aurait lieu de reprendre l’´etude de l’extension faite dans la section pr´ec´edente,
en y partant du point de vue des α, β associ´es,
[page 617]
dans l’optique actuelle, sans doute plus simple. Il y aurait lieu en mˆeme temps d’expliciter
une autre section partielle, qui serait au dessus de
Γ′′′∼
Q = {x ∈Γ∼
Q | ε2(x)ε3(x) = 1} ,
et qui m´eriterait peut-ˆetre la notation M(
√
3) ou du moins M(q), pour un g´en´erateur q
convenable de Q(
√
3) ??? (105).
Je me rends compte que je suis en train de d´econner – ayant un peu perdu contact avec
le contenu g´eom´etrique de mes calculs. Il faut garder `a l’esprit que
(25)
M!
0
-
∼
M! ∼
0,3
correspond, au ∼pr`es, au π1 de U0,3 Q, les section de M!
0
- Γ∼
Q ≃Υρ,σ correspondent
donc (au ∼pr`es) `a celles de π1(U0,3 Q) sur ΓQ, donc (‘moralement’) aux points rationnels
sur Q de U0,3 Q – quand ce sont des sections partielles, aux points de U0,3 Q `a valeurs dans
des extensions ﬁnies de Q. Ainsi, la section envisag´e dans b) correspond bien au point
1/2 de U0,3 Q, la section partielle M(−) envisag´ee ici dans c) correspond au point −de
U0,3 Q, qui est dans U0,3(Q(
3√
1)), donc la notation M(−) est raisonnable. Quant `a N ∼
ρ ,
il n’est pas ⊆M!
0 –mˆeme en divisant par µ ; on trouve apr`es division par µ une section
de M∼
0,3 sur Γ∼
Q, mais ce n’est pas une section de M! ∼
0,3. Or au ∼pr`es, M∼
0,3 est le π1 de
M′
1,1 Q, sch´ema modulaire sur Q des courbes elliptiques modulo sym´etrie. Donc la donn´ee
de cette section correspond `a la donn´ee d’une telle ‘courbe elliptique modulo sym´etrie’
sur Q. Passant au sous-groupe Γ′∼
Q – ce qui correspond `a l’extension de corps de base de
Q `a Q(j) = Q(
3√
1) – on retrouve l’image dans M! ∼
0,3 de la section partielle pr´ec´edente
M(−) – cela montre donc qu’il s’agit toujours de la ‘mˆeme’ courbe elliptique. J’ai bien
l’impression cependant que sur Γ∼
Q tout entier, cette section de M∼
0,3 ne peut se remonter
en une section de M sur Γ∼
Q – i.e. justement que l’extension N ?
ρ de Γ∼
Q par µ est non
triviale. Cela signiﬁerait-t-il qu’il n’existe pas de courbe elliptique d´eﬁnie sur Q d’invariant
0 ? (Chose qui semble absurde – on doit pouvoir sur un corps trouver n’importe quel
105? M´erite un examen attentif.


---

90
invariant . . . (106)). De fa¸con pr´ecise, on a le diagramme de sch´emas modulaires sur Q
(26)
M1,1
?
@
@
@@
R
M′
1,1
- E′
sch´ema modulaire
des courbes
elliptiques
gerbe
de groupe µ
sch´ema modulaire des
courbes elliptiques
modulo sym´etrie
sch´ema modulaire
grossier
,
le fait qu’un point de M′
1,1(Q) ne se remonte
[page 618]
pas en un point de M1,1, ne signiﬁe pas que son image dans E′ ne se remonte pas `a M1,1.
De fa¸con pr´ecise, le diagramme s’identiﬁe `a
(27)
M1,1 ≃(U0,3, ˜S3)
?
@
@
@@
R
M′
1,1 ≃(U0,3, S3)
- U0,3/S3 ≃U0,3/ ˜S3 ≃E′ ,
o`u ˜S3 est l’extension de S3 = SL(2, Z/2Z) par µ, d´eﬁnie par
(28)
˜S3
=
S+/π0
≃
SL(2, Z)/(sous-groupe invariante engendr´e par −l0)
≃
SL(2, Z/4Z)
,
sous-groupe invariante (d’ordre 4) engendr´e par −l0,
i.e. sous-groupe engendr´e par −l0, −l1

,
en faisant op´erer ˜S3 sur U0,3 par l’interm´ediaire de S3. Un point de M′
1,1 rationnel sur
Q s’identiﬁe donc `a un S3-torseur T sur Q, muni d’un morphisme
(29)
T
- U0,3
compatible avec les actions de S3, un point de M1,1 s’identiﬁe `a un ˜S3-torseur ˜T sur Q,
muni d’un morphisme
(30)
˜T
- U0,3
compatible avec l’op´eration de ˜S3 (107). D´esignant par
T = ˜T/µ
le S3-torseur correspondant, la donn´ee de (30) ´equivaut `a la donn´ee de (29). Donc les
rel`evements `a M1,1 d’un point de M′
1,1 rationnel sur Q s’identiﬁent aux ˜S3-torseurs ˜T
qui rel`event le S3-torseur T, i.e. (`a isomorphisme pr`es) ils correspondent aux homomor-
phismes ΓQ
- ˜S3 qui rel`event l’homomorphisme ΓQ
- S3 qui d´eﬁnit T (108) :
106?
107T est le torseur sur SL(2, Z/2Z) des (pr´e)rigidiﬁcations de Jacobi d’´echelon 2, ˜T celui des ‘pr´e-
rigidiﬁcations de Jacobi d’´echelon 2 pr´ecis´ees’ (le premier est d´eﬁni pour une courbe elliptique modulo
sym´etrie, le deuxi`eme seulement pour une vraie courbe elliptique.)
108On suppose maintenant choisi un point de T( ¯Q).


---

91
ΓQ
-

˜S3
?
S3 ;
l’obstruction est, comme il se doit, une extension de ΓQ par µ2, i.e. un ´el´ement de
H2(Q, µ2) ≃
2Br(Q). Dans le cas qui nous occupe, l’image de T dans U0,3 est form´ee
de {−, −j}, qui est connexe sur Q, sans doute ΓQ
- S3 est surjectif (109). De fa¸con
g´en´erale, dans la traduction galoisienne en termes de scindages de M0,3 sur ΓQ, l’homo-
morphisme ΓQ
- S3 est le compos´e
ΓQ
-
k
M0,3
- S3 ,
qui est trivial si et seulement si k est une section de
M!
0,3 = Ker(M0,3
- S3)
sur ΓQ.
Ici on a une section de M!
0,3 au dessus du sous-groupe Γ′
Q d’indice 2, donc
k|Γ′
Q = 1, donc k(ΓQ) ⊆S3 est d’ordre 2, on voit que
[page 619]
c’est le sous-groupe {1, ˙σ∞} de S3, car l’image de τ ′ = στ ∈M0,3 dans S3 est (comme
celle de τ est 1) ´egale `a celle de σ = σ∞, i.e. ˙σ∞. Cela signiﬁe que l’on a
T ≃T0 ∧{1, ˙σ∞} S3 ,
i.e. T est d´eduit d’un µ-torseur (i.e. d’une extension quadratique de Q – savoir justement
Q(
3√
1) = Q(j)) par extension du groupe d’op´erateurs µ
- S3 (−1
- ˙σ∞).
Donc,
prenant l’image inverse de µ = {1, ˙σ∞} dans ˜S3, on trouve une extension de µ par µ – ¸ca
ne peut gu`ere ˆetre que Z/4Z ! (110) – que j’ai envie de noter E′′,
1
- µ
-
≃Z/4Z
z}|{
E′′
- µ
- 1 ,
et le probl`eme d’obstruction est de trouver un remontage
E′′
- µ
6
    
ΓQ
(qui n’existe sˆurement pas!
(111)) – donc l’obstruction s’interpr`ete comme l’extension
de ΓQ par µ, image inverse de l’extension E′′. (Il faudrait regarder pourquoi, en termes
109Canul´e, cf. rectiﬁcation plus bas.
110Oui, c’est ´evident, puisque σ = σ∞dans S3 = SL(2, Z)/π0 est bien d’ordre 4, donc E′′ ≃Z/4Z
canoniquement . . .
111C’est ´evident en eﬀet, grˆace `a (ΓQ)ab ≃ˆZ∗⊇Z∗
3, on a (Z∗
3)4 ≃Z/2Z, donc d´ej`a sur Z∗
3 ¸ca ne se
remonte pas.


---

92
classiques, cette obstruction est scind´ee, quand on passe au sous-groupe Γ′′′
Q correspondant
au corps Q(
√
3)).
Ainsi, le point Q-rationnel envisag´e de M′
1,1 ne se remonte pas en un point Q-rationnel
de M1,1. Par contre, son image 0 dans E′ ≃U0,3/S3 doit bien se remonter – i.e. il doit
bien exister un ˜S3-torseur ˜P, et un ˜S3-homomorphisme
˜P
- U0,3 ,
i.e.
P
|{z}
= ˜P/µ
- U0,3 .
Consid´erons en eﬀet le sous-sch´ema
Q = U0,3 ×E′ {0}
image inverse de 0, soit
P0 = Qr´ed .
C’est un sous-schema qui, sur un corps K ⊇Q(j), est somme de deux points, et qui sur
Q est connexe – c’est un sch´ema canoniquement isomorphe `a Spec Q(−). Il est stable
par S3, qui y op`ere via
S3
-
sg
µ ,
et l’op´eration galoisienne de µ sur le µQ-torseur P0.
[page 620]
Ainsi on a le diagramme
(31)
˜S3
-
can.
S3
-
sg
µ
ΓQ
    
(112) .
On voit alors que la cat´egorie des rel`evements des points Q-rationnels de E′ en un point
Q-rationnel de M1,1 resp. M′
1,1, est ´equivalente `a celle des S3-torseurs ˜P sur Q, qui
rel`event le µ-torseur P0. On avait choisi un P = T de fa¸con particuli`erement triviale, en
utilisant le scindage
µ
-
∼
{1, ˙σ∞}
-

S3
de S3
- µ – mais le torseur T ne se remonte pas en un ˜T. Les classes d’isomorphie de
points de M′
1,1 resp. de M1,1 au dessus du point 0 de E′, correspondent de mˆeme aux
classes de conjugaison (modulo noyau S+
3 [resp.] ˜S+
3 de S3
- µ [resp.] ˜S3
- µ)
de rel`evements de ΓQ
- µ en ΓQ
- S3 resp. ΓQ
- ˜S3.
Consid´erons un rel`evement en
ΓQ
- S3 ,
son image est un sous-groupe de S3, qui est soit {1, ˙σ∞} ou un de ses conjugu´es {1, ˙σ0},
{1, ˙σ1}, ou c’est S3 tout entier. Dans le premier cas, on a vu que ¸ca ne se remonte pas en
˜S3. Donc pour pouvoir remonter, il faut prendre un ´epimorphisme ΓQ
- S3 – on sort
donc du contexte ab´elien sur Q, pour entrer dans le domaine des extensions ab´eliennes de
112NB Le noyau de ˜S3
- µ est une extension centrale de Z/3Z par µ = Z/2Z, elle est donc triviale
et isomorphe `a Z/6Z (noyau engendr´e par ρ).


---

93
Q(j). Examiner en termes de groupes de Galois s’il existe un tel rel`evement ΓQ
- ˜S3,
et comment les obtenir, apparaˆıt comme un exercice plaisant et d´electable de th´eorie des
corps de classes, que je ne vais pas poursuivre pour le moment, pour ne pas ´eterniser cette
digression. Revenant par la suite sur ce point, il me faudrait en mˆeme temps expliciter
la relation entre les points de vue remontage d’homomorphismes de ΓQ, et scindage de
l’extension M0,3 de ΓQ par S+ ∧
0,3 , ou M de ΓQ par S+ ∧≃SL(2, Z)∧.
[page 621]
Revenons au sous-groupe
N ?
ρ
|{z}
4
⊇M′(−) = Z!
ρ 0
3
⊆N ∗
ρ ⊆M
contenant le sous-groupe section partielle M(−)
-
∼Γ′
Q
∼. Soit
(32)
M0(−)
def
=
Ker(M′(−)
-
ε2 µ)
=
Zρ ∩M′′!
0
=
N ∗
ρ ∩M0 !
0
2
⊆
M′(−) ,
qui est donc une section partielle au dessus de
(33)
Γ0 ∼
Q
=
Ker(Γ∼
Q
-
(ε2,ε3) µ × µ)
=
Ker(Γ∼
Q
- ˆZ∗
- (Z/12Z)∗) .
Modulo une v´eriﬁcation que je vais faire plus bas, τ ′ normalise M0(−). Consid´erons
alors
(34)
M′′′(−)
def
= µτ ′ · M0(−)
|
{z
}
(semi-direct)
,
o`u µτ ′ = {1, τ ′} ,
c’est un sous-groupe d’indice 4 de N ?
ρ , et on a maintenant
(35)
M′′′(−)
-
∼
Γ′′′
Q
∼,
c’est une section partielle au dessus de Γ′′′
Q
∼, d’o`u des isomorphismes
[page 622]
(36)



M′′′
≃
M′′′(−) · S+ ∧
N ∗
ρ
≃
M′′′(−) · Lρ .


---

94
Diagramme r´ecapitulatif des sous-groupes de N ∗
ρ obtenus jusqu’`a pr´esent :
(37)
M′′′(−)
-

2
M′′′(−) × µ
-

2
N ?
ρ
-

3
N ∗
ρ
    	
 2
    	
 2
    	
 2
    	
 2
M0(−)
-

2
M′(−)
| {z }
= Z!
ρ 0
-

2
M′(−) × µ
-

3
Zρ
@
@
@
@
@
@
@
@
@
@
I

@
@
@
@
@
@
@
@
I

6
 
6
 
6
 
6
 
6
 
6
 
µτ ′
-

2
Dτ ′
-

3
Dρ
    	
 2
    	
 2
    	
 2
1
-

2
µ
-

3
Lρ
o`u nous sommes ici int´eress´es surtout `a la ‘face sup´erieure’, couvrant des sous-groupes
d’indice ﬁni de N ∗
ρ , interm´ediaires entre celui-ci et M0(−) (d’indice 24 dans N ∗
ρ ). Je
vais examiner la question d’invariance de ces sous-groupes les unes dans les autres, et la
structure des groupes quotients.


---

95
Je vais refaire un diagramme qui montre mieux les relations entre les groupes en question :
(38)
µ
6
 
M0(−) × µ
6
 
2
Z!
ρ = M′(−) × µ
6
 
3
Zρ
-

2
-

2
-

2
-

2
Dτ ′
6
 
M′′′(−) × µ
6
 
2
N ?
ρ
6
 
3
N ∗
ρ
       	
 2
      	
 2
       	
 2
       	
 2
       	
 2
       	
 2
1
6
 
M0(−)
6
 
2
Z!
ρ 0 = M′(−) × µ
-

2
-

2
-

2
µτ ′
6
 
M′′′(−)
6
 
2
M′(−) · µτ ′
(113)
	
 3
	
 3
	
 3
	
 3
Lρ
6
 
Zρ
-

2
-

2
Dρ
 
6
N ∗
ρ
?

?

0) Sous-groupes d’indice ﬁni dans Zρ – dans le diagramme il y en a quatre :
(39)
Z!
ρ = M′(−) × µ 
 
2
M′(−) = Z!
ρ 0 = N ∗!
ρ 0
6
 
2
6
 
2
M0(−) × µ 
 
2
M0(−) = Z0 !
ρ 0
Sont-ils invariants dans Zρ ? C’est clair pour les sous-groupes
(40)



M′(−) × µ = Zρ ∩M! = Z!
ρ ,
et pour
M0(−) × µ = Zρ ∩M! ∩Ker(ε2 : M
- µ)
113Attention, M′(−) · µτ ′ n’est pas un sous-groupe, car µτ ′ ne normalise pas M′(−).


---

96
– cela montre que ces groupes sont
[page 623]
mˆeme invariants dans N ∗
ρ , puisque Zρ, M!, Ker ε2 sont stabilis´es par N ∗
ρ . D’ailleurs,
comme Z!
ρ 0 = M′(−) est invariant dans Z!
ρ = M′(−) × µ, pour montrer qu’il l’est dans
Zρ, il suﬃt de prouver qu’il est normalis´e par ρ (puisque Zρ = Lρ · Z!
ρ – c’est plus ou
moins trivial) ; or examinons de fa¸con g´en´erale pour x ∈M si x normalise
M!
0
def
= M(0) · π0 ;
comme il normalise π0, il suﬃt de voir si pour u ∈M(0), on a
xux−1 ∈M!
0 ,
qui ´equivaut aussi `a
xux−1 ≡u
(π0) ,
i.e.
[x, u] ∈π0 .
Or on sait que pour x ∈S, u ∈M!, on a
(∗)
[x, u]
|{z}
= xu(x)−1
≡(sg(x))ε2(u)
mod π0
[c.`a.d. sg(x)ν2, o`u ε2(u) = (−1)ν2], o`u
sg : S
-
can. S3
-
sg
µ .
Cela montre le
Lemme. Si x ∈S+, u ∈M!
0, alors conditions ´equivalentes :
a) xux−1 ∈M!
0 .
b) xux−1 ≡u (π0) , i.e. [x, u] ∈π0 .
c) sg(x)ε2(u) = 1 , i.e. sg(x) = 1 ou ε2(u) = 1.
Corollaire 1. Soit x ∈S+ ∧. Pour que x normalise M!
0, il faut et il suﬃt qu’on ait
sg(x) = +1.
Corollaire 2. Le sous-groupe M′′
0
! = M′′(0) · π0 est normalis´e par S+ ∧.
Ceci montre en particulier que ρ normalise M!
0, donc aussi M′(−) = Z!
ρ 0 = Zρ∩M!
0, qui
est donc invariant dans Zρ. Il en est donc de mˆeme de son intersection avec M0(−) × µ,
soit M0(−). (Ou encore : ce groupe est ´egal `a Zρ ∩M′′
0
!, et M′′
0
! est normalis´e par ρ . . . ).
Ainsi les quatre groupes (39) sont distingu´es dans Zρ.
Pour voir s’ils sont distingu´es dans N ∗
ρ = µτ ′ · Zρ, il suﬃt de voir s’ils sont normalis´es par
τ ′. C’est clair pour Z!
ρ = Zρ∩M! – d’o`u le fait que N ?
ρ = µτ ′·Z!
ρ est un sous-groupe de N ∗
ρ .
Pour voir lesquels des trois autres sous-groupes envisag´es de ce dernier sont normalis´es,
il faudrait donc expliciter l’action de τ ′ sur Z!
ρ = M′(−) × µ.


---

97
[page 623 bis]
Notons que τ ∈M(0) ⊆M!
0 normalise M!
0, donc il op`ere sur M! = M!
0
|{z}
≃Γ∼
Q×π0
×µ par
l’op´eration produit de la conjugaison par τ dans M!
0, et l’identit´e dans µ. On a d’autre
part τ ′ = τσ, on a vu que
(40)
σ(x) ≡ε2(x)x
(π0)
[pour] x ∈M
[114] ,
donc
(41)
τ ′(x) ≡ε2(x)τ(x)
(π0)
[pour] x ∈M ,
donc il s’ensuit :
(42)



Si x ∈M!
0 , alors τ ′(x) ≡x (π0)
⇐⇒
τ ′(x) ∈M?
0
⇐⇒
ε2(x) = 1 ,
en particulier, M′′
0
! est normalis´e par τ .
Donc appliquant ceci aux ´el´ements de Z!
ρ 0 = M′(−) dans Z!
ρ = M′(−) × µ, on trouve :
(43)



Soit x ∈Z!
ρ 0 , alors
τ ′(x) ∈Z!
ρ 0 ⇐⇒ε2(x) = 1 .
Corollaire. Z!
ρ 0 = M′(−) n’est pas normalis´e par τ ′, donc n’est pas invariant dans N ∗
ρ ,
mais M0(−) = Zρ ∩M′′
0
! est normalis´e par τ ′, donc aussi son produit par µ.
Donc le seul des quatre sous-groupes (39) de Zρ qui ne soit distingu´e dans N ∗
ρ est
M′(−) = Z!
ρ 0. Les autres donnent naissance, par produit semi-direct avec µτ ′, `a des
sous-groupes de N ∗
ρ , invariants dans N ∗
ρ .
Le plus petit de tous ces sous-groupes est
M0(−), qui est d’indice 24 dans N ∗
ρ . Le groupe quotient
N ∗
ρ /M0(−)
est donc un groupe d’ordre 24, qui re¸coit d’ailleurs le groupe Dρ = µτ ′ · Lρ ⊆N ∗
ρ ,
normalisateur de Lρ dans GL(2, Z), groupe isomorphe `a D6, et d’ordre 12. Le noyau de
(44)
Dρ
-

N ∗
ρ /M0(−)
est ´evidemment contenu dans Lρ = Dρ ∩Zρ, et il est r´eduit `a 1 puisqu’on a mˆeme
Lρ ∩Z!
ρ 0 ⊆Lρ ∩M!
0 = Lρ ∩π0 = {1} .
Ainsi Dρ (d’ordre 12) apparaˆıt comme un sous-groupe d’indice 2 de N ∗
ρ /M0(−), tout
comme il est sous-groupe d’indice 2 de S/π0. Il serait tentant
[page 624]
alors d’´etablir un isomorphisme
N ∗
ρ /M0(−)
?≃S∧/π0
114[Deux fois (40).]


---

98
compatible avec ces plongements de Dρ. Essayons-le ainsi :
Proposition. Consid´erons l’homomorphisme compos´e
(45)
M
-
θM
GL(2, ˆZ)
-
GL(2, Z/4Z)
|
{z
}
∼
GL(2,Z)
| {z }
= S
/S[4]
-
´epimorphisme
de degr´e 4
S/π0 ≃S∧/π∧
0 ,
qui induit sur S∧⊆M l’homomorphisme canonique S∧
- S∧/π∧
0 . Alors l’homomorphisme
induit
N ∗
ρ
- S/π0
a comme noyau M0(−), et induit par passage au quotient un isomorphisme
(46)
N ∗
ρ /M0(−)
-
∼
S/π0 .
D´emonstration. Les ´el´ements de M0(−) sont les ´el´ements de la forme









v = α−1u

u ∈M(0) ,
α ∈π0
u(ρ) = α(ρ)
(donc ε3(u) = 1)
ε2(u) = 1









,
ils sont en correspondance 1-1 avec les ´el´ements de M0(0) = {u ∈M(0) | ε2(u) = ε3(u) =
1}. L’image de v dans GL(2ˆZ)/ Im π∧
0 , a fortiori dans S/π0, est ´egale `a celle de u. Donc
l’assertion que M0(−) est dans le noyau de M
- S/π0, ´equivaut `a celle que M0(0) est
dans ce noyau, donc que l’on a un diagramme commutatif
(47)
M(0)
- M
?
(ε2,ε3)
?
(45)
µ × µ
-
?
S/π0
(115) .
Notons que le compos´e
M
-
S/π0
- (Z/4Z)∗≃{±1}
@@
R
GL(2, Z/4Z)
  
n’est autre que ε2. Notons aussi que par la compatibilit´e
S
-

M
@
@
@@
R
can.
?
(45)
S/π0
115NB Le caract`ere ε3 n’intervient pas dans l’explicitation de M
- S/π0, cf. plus bas . . .


---

99
l’op´eration de M sur S/π0 d´eduite de l’homomorphisme (45) n’est autre que l’op´eration
d´eduite des automorphismes sur S en passant au quotient par π0, op´eration qui, pour
u ∈M! et en particulier sur M(0) ⊆M!, est donn´ee par ε2(u) (cf. p. 594). Ainsi
[page 625]
on voit que M′′! s’envoie dans le centre de S/π0, qui est contenu dans S+/π0, et en fait
´egal `a l’image µ de π/π0 dans S+/π0 (puisque le centre de S+/π ≃S3 est trivial). Donc
on a une factorisation
M′′!
- µ
-
| {z }
centre
S/π0 ,
et il faudrait v´eriﬁer que cet homomorphisme M′′!
- µ n’est autre que ε3, qui est donc
trivial sur M0 ! et a fortiori sur M0(0). En fait, on se convainc que le noyau n’est pas
Ker(ε3|M′′!) (qui contient en eﬀet µ !), mais M′′
0
! – on va y revenir plus bas.
Admettant ce point, on trouve donc
Ker(N ∗
ρ
- S/π0) = N ∗
ρ ∩M′′
0
! ,
et comme N ∗
ρ ∩M!
0 = Z!
ρ 0 = M′(−), on trouve que le noyau cherch´e est ´egal `a
M′(−) ∩M′′ = M0(−), c.q.f.d.
Donc on a bien un homomorphisme injectif (46), et comme les groupes
[page 626]
en pr´esence ont mˆeme ordre 24, cet homomorphisme est bien un isomorphisme, c.q.f.d.
1) Application `a la structure de Mρ,σ et `a la d´eﬁnition d’un homomorphisme
M
- Mρ,σ/µρ.
Rappelons que
(48)
Mρ,σ
def
= N ∗
ρ ×Υρ,σ N ∗
σ ×Υρ,σ Gρ,σ ,
o`u
(49)

















Gρ,σ ≃M ≃
M(0)
| {z }
≃M∼
0,3(0)
· S+ ∧
Υρ,σ
def
= Gρ,σ/ S+ ∧
|{z}
= Sρ,σ
≃Γ∼
Q ( ∼
M(0) ) ,
N ∗
ρ = NormM(Lρ) , N ∗
σ = NormM(Lσ) .
D’autre part, nous avons introduit les sous-groupes remarquables
(50)



Z!
σ 0
=
M(1/2)
⊆
N ∗
σ
(p. 615, (9))
N ?
ρ
=
Z!
ρ · µτ ′
⊆
N ∗
σ
(p. 616, (21)) .
Le premier de ces groupes ne contient pas µ, le deuxi`eme le contient,
(51)



Z!
σ 0 ∩µ = {1}
N ?
ρ ⊇µ ,


---

100
et
(52)







Z!
σ 0
-
∼
Υρ,σ = Γ∼
Q ,
1
- µ
- N ?
ρ
-
= Γ∼
Q
z}|{
Υρ,σ
- 1
exacte .
Soit alors
(53)
M♮
ρ,σ
def
=
N ?
ρ ×Υρ,σ Z!
σ 0 ×Υρ,σ Gρ,σ
|{z}
= M
⊆
Mρ,σ .
On a un plongement central canonique
(54)
µ
×
µ
×
µ
-

Mρ,σ
(ε
,
ε′
,
ε′′)
-
(ε, ε′, ε′′)
provenant des plongements centraux
µ
-

N ∗
ρ
µ
-

N ∗
σ
µ
-

Gρ,σ
@
@
R

  

S+
ρ,σ = S+ ,
et on a
M♮
ρ,σ ∩(µ × µ × µ) = (1 × µ × µ) ,
donc
(55)
µ × µ
-

M♮
ρ,σ .
On d´esigne par µρ le sous-groupe central µ de Nρ ou de N ?
ρ , ou µ × 1 dans M♮
ρ,σ. Il est
clair par (52) que l’on a une suite exacte
(55)
1
- µρ
-

M♮
ρ,σ
- Gρ,σ
|{z}
≃M
- 1
[116] ,
d’o`u des homomorphismes canoniques
[page 627]
(56)
M
-
∼
M♮
ρ,σ/µρ
-

Mρ,σ/µρ
(117) .
´Evidemment le sous-groupe M♮
ρ,σ de Mρ,σ contient Sρ,σ = SGρ,σ ≃S+ ∧, en fait on a un
116[Deux fois (55).]
117On verra donc
Γ♮
ρ,σ
def
= M♮
ρ,σ/S+
ρ,σ
-

Γρ,σ = Mρ,σ/S+
ρ,σ .


---

101
diagramme de suites exactes
(57)
1
- µρ × Sρ,σ
- M♮
ρ,σ
- Υρ,σ
- 1
?
  ?
1
- SZρ
|{z}
= Lρ
× SZσ
|{z}
= Lσ
× S+
ρ,σ
- Mρ,σ
- Υρ,σ
- 1 .
Dans l’isomorphisme (56), le sous-groupe S+ ∧de M correspond au sous-groupe
µρ × S+
ρ,σ/µσ ≃Sρ,σ, il s’envoie isomorphiquement sur le sous-groupe Sρ,σ de Mρ,σ/µρ.
On trouve ainsi
(58)
1
-
≃S+
ρ,σ
z}|{
S+ ∧
- M
-
≃Υρ,σ
z}|{
Γ∼
Q
- 1
?
≀
?
≀
?
≀
1
- S+
ρ,σ - M♮
ρ,σ/µρ - Γ♮
ρ,σ/µρ
- 1
?
  ?
  1
- S+
ρ,σ - Mρ,σ/µρ - Γρ,σ/µρ
- 1
Ainsi, on trouve en passant que l’homomorphisme canonique ´epimorphique [∗]
(59)
1
- SZρ × SZσ
|
{z
}
= Lρ×Lσ
- Γρ,σ
-
[∗] Υρ,σ
- 1
admet une ‘bisection’ Γ♮
ρ,σ (dont l’intersection avec SZρ × SZσ est µρ × 1),
(60)











Γρ,σ ≃Γ♮
ρ,σ · SΓρ,σ
| {z }
≃SZρ×SZσ = Lρ×Lσ
,
Γ♮
ρ,σ ∩SΓρ,σ = µρ
Γρ,σ/µρ ≃( Γ♮
ρ,σ/µρ
| {z }
≃Υρ,σ ≃Γ∼
Q
) · (Lρ/µρ × Lσ) .
Pour dire ce que deviennent les sous-groupes remarquables
M(0) ,
M[0]
| {z }
=MS[0] = M(0)·LS
0
,
M![0]
| {z }
= Mπ[0] = M(0)·Lπ
0
,
M!
0[0]
| {z }
= Mπ0[0] = M(0)·Lπ0
0
,
M(1/2)
|
{z
}
= Z!
0 σ
,
M′(−) ,
M′′′(−) ,
N ?
ρ
de M par l’homomorphisme
M
-
∼
M♮
ρ,σ/µρ
-

Mρ,σ ,
il faudrait d’abord introduire les groupes ad´equats dans les Mρ,σ g´en´eraux. Nous allons
donc revenir sur ces groupes maintenant.


---

102
[page 628]
VI) Les groupes Mρ,σ g´en´eraux : r´ecapitulation, raﬃnement.
1◦) Donn´es. Ce sont celles de V 1◦) (p. 577). En plus de S (proﬁni) et de GL(2, Z)∧
- S,
homomorphisme continu surjectif, i.e. des g´en´erateurs ρ, σ, τ (ou ρ, σ, τ ′) de S, on se
donne aussi un sous-groupe ouvert
(1)
S♮⊆S+ ,
invariant dans S .
Dans le cas universel S = GL(2, Z)∧, la donn´ee de S♮peut correspondre au point de vue
o`u on regarde le sous-groupe M♮de M form´e des u qui normalisent S♮et qui op`erent
trivialement dans S+/S♮– c’est un sous-groupe ouvert, qui d´eﬁnit dans Γ∼
Q = M/S+
un sous-groupe image Γ♮
Q
∼ouvert, dont on peut se proposer d’´etudier les repr´esentations
dans des groupes proﬁnis convenables. Un cas int´eressant sera celui o`u
S♮
=
π0 ,
donc
M♮
=
M′′! ,
ou
S♮
=
π ,
donc
M♮
=
M′ .
Si
S♮
=
S ,
donc
M♮
=
M
[plut^ot S♮= S+ dans le troisi`eme cas ?], on retrouvera les constructions pr´ec´e-
dentes. Un cas int´eressant aussi est celui o`u S est le groupe des points ad´eliques entiers
d’un sch´ema en groupes sur Z (dans ce cas, il est vrai que ρ, σ, τ n’engendrent peut-
ˆetre S que modulo groupe ﬁni, i.e. ils engendrent peut-ˆetre seulement un sous-groupe
ouvert. Dans ce cas, il faudrait plutˆot paraphraser les constructions qui suivent dans le
cas sch´ematique. J’y reviendrai par la suite. Un choix int´eressant d’un S♮est alors la
composante neutre de S.)
J’h´esite `a introduire des notations Z♮
ρ,σ, M♮
ρ,σ etc. – pour ne pas surcharger des notations
d´ej`a lourdes. Donc je pr´ef`ere utiliser les notations plus simples Zρ,σ etc. – ´etant entendu
que dans ces constructions, le groupe S♮intervient – quitte `a r´eintroduire la notation ♮
au cas de besoin.
On pose
(2)
S♮
τ =
= µτ
z }| {
{1, τ} ·S♮⊆S .
[page 629]
2o) Zρ,σ, Υρ,σ.
Soit
(4)
Zρ,σ
def
=















(u, µ, ε2, ε3)

a)
∃α ∈S♮
τ avec εS(α) = ε3, u(ρ) = α(ρ)
b)
∃β ∈S♮
τ avec εS(β) = ε2, u(σ) = β(σ)
c)
u(ε0) = εµ
0
d)
u normalise S♮















⊆
Aut(S+) × ˆZ∗× µ × µ ,
[118] .
118[(3) n’existe pas.]


---

103
Proposition. Zρ,σ est un sous-groupe du groupe produit.
D´emonstration. Les conditions a), d) d´eﬁnissent ´evidemment chacune une sous-groupe.
Compte tenu que
τ(σ) = −ε ,
la condition b) signiﬁe aussi que
(5)
b′)
u(σ) est S♮-conjugu´e `a σε2 (= ε2σ) ,
et sous cette forme il est clair que la condition b′) d´eﬁnit un sous-groupe. Je ne pense
pas que la condition a) d´eﬁnisse `a elle seule un sous-groupe. Mais si G(b) d´esigne le sous-
groupe du produit d´eﬁni par la condition b) [etc.], on va montrer que G(a,b) est un
sous-groupe de G(b) – ce qui prouvera la proposition. Soient u, u′ ∈G(b) [plut^ot G(a,b)],
correspondant `a (u, µ, ε2, ε3) et (u′, µ′, ε′
2, ε′
3), et `a α, α′ ∈S♮
τ, de sorte que l’on a
(6)
u(ρ) = α(ρ) ,
u′(ρ) = α′(ρ) ,
avec εS(α) = ε3, αS(α′) = ε′
3 ,
prouvons que u′u ∈G(a,b) – i.e. qu’il satisfait aussi `a (b). Si ε3 = 1, i.e. α ∈S♮⊆S [il
est possible qu’il manque quelque chose ici], u′(α) est d´eﬁni et on aura
(u′u)(ρ) = u′(u(ρ)) = u′(α(ρ)) = u′(α)(u′(ρ)) = u′(α)(α′(ρ)) = (u′(α)α′)(ρ) = α′′(ρ) ,
avec
(7)
α′′ = u′(α)α′ ∈S♮
τ
εS(α′′) = εS(α′) = ε′
3 = ε3ε′
3



Cas ε3 = 1
(puisque u′(α) ∈S♮, i.e. εS(u′(α)) = 1, et ε3 = 1). Dans ce cas on gagne. Si ε3 = −1, on
´ecrit
α = α0τ ,
α0 ∈S♮,
et on aura
u(ρ) = (α0τ)(ρ) = α0(τ(ρ)) = α0(σ(ρ−1)) = (α0σ)(ρ−1 , )
o`u maintenant α0σ ∈S+, donc u′(α0σ) est d´eﬁni, et on aura
(u′u)(ρ) = u′(u(ρ)) = u′(α0σ)(u′(ρ−1)
| {z }
= α′(ρ−1)
) = (u′(α0σ)α′)(ρ−1) ,
et comme
ρ−1 = στ(ρ)
on trouve
(8)
(u′u)(ρ) = α′′(ρ) ,
avec







α′′ = ε
∈S♮
z }| {
u′(α0)
S+
z }| {
u′(σ)
∈S♮
τ
z}|{
α′ στ ,
o`u
ε ∈µ = {±1} = Centre S+
est choisi de fa¸con que α′′ (si possible) soit dans S♮
τ.


---

104
Notons que tous les facteurs de ce produit sont dans S♮
τ ou S+, en tous cas α′′ ∈S.
[page 630]
R´eduisant modulo S♮, la relation α′′ ∈S♮
τ s’´ecrit
˙α′′ ∈{1, ˙τ} , i.e. ˙εu′(σ)˙ ˙α′ ˙σ ˙τ ∈{1, ˙τ} , soit ˙εu′(σ)˙ ˙α′ ˙σ ∈{1, ˙τ} ,
on distingue encore deux cas :
1◦) ε′
3 = 1, i.e. ˙α′ = 1 ; la relation s’´ecrit
(∗)
˙εu′(σ)˙ ˙σ = 1 .
2◦) ε′
3 = −1, i.e. ˙α′ = ˙τ ; comme τσ = −στ, la relation s’´ecrit
(∗∗)
−˙εu′(σ)˙ ˙σ = 1 .
Donc dans tous les cas, la relation s’´ecrit
(9)



u′(σ)˙ =
(εε′
3)˙ ˙σ−1 ,
soit encore
u′(σ)˙ =
(−εε′
3)˙ ˙σ .
Or supposant maintenant qu’on a b) pour u′, ce qui implique
u′(σ)˙ = ε′
2 ˙σ ,
on voit donc qu’il suﬃt de choisir ε de fa¸con que −εε′
3 = ε′
2, i.e.
ε = −ε′
2ε′
3 ,
donc on aura
α′′ = −ε′
2ε′
3u′( α0σ
|{z}
=ατσ = ατ ′
)α′ στ
|{z}
−τ ′
,
i.e.
(10)
α′′ = ε′
2ε′
3u′(ατ ′)(α′τ ′)
o
Cas ε3 = −1 ,
formule qui a un sens car ατ ′ ∈S+, donc u′(ατ ′) est d´eﬁni, et l’argument pr´ec´edent
prouve que l’´el´ement en question satisfait
(11)
α′′ ∈S♮
τ ,
εS(α′′) = εS(α)
| {z }
= −1
εS(α′) ,
en distinguant les cas (∗) et (∗∗) de (9).
Mˆeme conclusion dans les premier cas o`u
εS(α) = 1 (7). Cela ach`eve la d´emonstration.
Remarque. Si S est ‘assez gros’, l’homomorphisme de projection est injectif,
(12)
Zρ,σ
-

Aut(S)+
(cf. p. 578) .


---

105
Examples dans le cas universel.
a) S♮= S+ = SL(2, Z)∧. La condition (4 d) est vide, les conditions a), b) ´equivalent
respectivement au fait que u(ρ) conjugu´e `a ρε3, u(σ) conjugu´e `a σε2, i.e. on retombe
sur la d´eﬁnition (6), p. 578, qui donne
(13)
Zρ,σ = M(0) · LS
0
= MS[0] = M[0]
(119) .
b) S♮= π = π0 × µ. On trouve maintenant
(14)
Zρ,σ = M(0) · Lπ
0 = Mπ[0] = M![0]
(not´e Z!
ρ,σ dans V 8◦) (120, 121).
c) S♮= π0. Les conditions a) et b) n’ont pas chang´e par rapport au cas pr´ec´edent,
puisque π = π0 × µ et µ est central ; par contre, la
[page 631]
condition d) devient nettement plus stricte, on trouve p.ex. que Zρ,σ ∩S+ = Lπ0
0
(d’indice 2 dans le groupe correspondant Lπ
0 du cas pr´ec´edent), et comme l’op´eration
de M(0) ⊆M! sur S+/π0 ‘se fait par le caract`ere ε2 ’, on voit que l’on a maintenant
(15)
Zρ,σ = M′′(0) · Lπ0
0
= M′′[0]0 ,
o`u, pour m´emoire,









M′′(0)
=
Ker(M(0)
-
ε2 µ)
M′′[0]0
=
Ker(M[0]
-
ε2 µ)
M[0]0
=
M(0) · Lπ0
0 .
(122).
Ces deux derniers examples sugg`erent l’opportunit´e, dans le cas g´en´eral o`u on disposerait
d’un sous-groupe S♮
0 de S♮, invariant dans S, tel qu’on ait
(16)
S♮= S♮
0 × µ
119NB A priori on a plutˆot Zρ,σ ⊆M∼
0,3, mais on a
M[0]
-
∼
M∼
0,3[0]
∥
∥
M(0) · LS
0
-
∼
M0,3(0) · LS0,3
0
.
120Dans ce cas, il est imm´ediat que Zρ,σ op`ere trivialement sur S+/S♮, car il en est ainsi de M![0] =
Mπ[0].
121Expliciter `a nouveau pourquoi (i.e. pourquoi (ε0, 1, 1, 1) ̸∈Zρ,σ).
122Il en est ainsi si dans la d´eﬁnition de Zρ,σ on exige dans d) que u induit l’op´eration triviale sur
S+/S♮, condition que j’ai ﬁnalement abandonn´ee comme inutile. Donc avec la nouvelle version, les cas
S♮= π et S♮= π0 donnent le mˆeme Zρ,σ. Mais je voudrais obtenir Mπ0[0] = M[0]!
0 = M(0) · π0, le
groupe de b) est un peu trop grand, celui de c) (ancienne mani`ere) un peu trop petit !


---

106
(o`u µ est le sous-groupe central universel µ = {1, ρ3} = {1, σ2}), de d´eﬁnir Zρ,σ en termes
de S♮, et de choisir les α, β de la d´eﬁnition (4) dans
(17)
S♮
0 τ
def
= µτ · S♮
0
(123) .
Remarque. On est tent´e de remplacer la d´eﬁnition (4) (pour a) et b)) par la d´eﬁnition
d’apparence plus simple de la p. 578, qui rend ´evident qu’on a un sous-groupe. Mais elle
ne donne pas, mˆeme si S♮⊆π (cas universel) une action triviale de Z sur S+/π, comme
on le veut sˆurement [quelques mots manquent] qu’en se restreignant `a des (u, µ, ε2, ε3)
avec ε3 = 1, car ˙ρ−1 n’est pas ´egal `a ˙ρ ! Il est vrai (dans le cas universel p.ex.) que u(ρ)
est conjugu´e dans S+ `a ρε3, mais en g´en´eral il ne le sera pas par un ´el´ement (disons) de
π.
On posera
(18)
L♮
0 = {l ∈LS
0 | (int(l), 1, 1, 1) ∈Zρ,σ}
(124)
(o`u LS
0 ⊆S+ est l’ensemble des εn
0, n ∈ˆZ), et on a un homomorphisme canonique
(19)
L♮
0
- Zρ,σ ,
injectif si et seulement si on a
(20)
L♮
0 ∩Centr(S+) = {1} ,
l’image invariante (125). On pose
(21)
Υρ,σ = Zρ,σ/L♮
0 ,
d’o`u
(22)
1
- L♮
0
- Zρ,σ
-
δZ
Υρ,σ
- 1 ,
(23)
Zρ,σ
- Υρ,σ
  
ε3 Υ
µ
-
χΥ
ˆZ∗
@
@
R
ε2 Υ
µ ,
d´eduit de
(u, µ, ε2, ε3)









-
ε3
-
µ
-
ε2
.
123Cette remarque sur un S♮
0 devient maintenant inutile.
124NB On a L♮
0 ⊇L0 ∩S♮, et l’inclusion peut ˆetre stricte, cf. exemple c) ci-dessus . . . , o`u L♮
0 = Lπ
0,
L0 ∩S♮= Lπ0
0 .
125Ce qu’on suppose.


---

107
[page 632]
On pose
(24)









Υ′
ρ,σ = Ker ε3 Υ , Υ′′
ρ,σ = Ker ε2 Υ , Υ′′′
ρ,σ = Ker ε3 Υε2 Υ ,
Υ0
ρ,σ = Υ′ ∩Υ′′ = Υ′′ ∩Υ′′′ = Υ′′′ ∩Υ′ ,
Z′
ρ,σ , Z′′
ρ,σ , Z′′′
ρ,σ , Z0
ρ,σ
sont les images inverses de Υ′
ρ,σ dans Zρ,σ .
Ce sont donc des sous-groupes d’indice 1, 2 ou 4 de Υρ,σ resp. Zρ,σ – l’indice 4 ne pouvant
se pr´esenter que pour Υ0
ρ,σ, Z0
ρ,σ.
Remarques. [Ces remarques vont jusqu’`a la page 650.]
1◦) On a donc
(25)
Z0
ρ,σ ≃









(u, µ) ∈Aut(S+) × ˆZ∗

a)
u(ρ) est S♮-conjugu´e `a ρ
b)
u(σ) est S♮-conjugu´e `a σ
c)
u(ε0) = εµ
0









(isomorphisme de groupes).
La condition d) de (4) – stabilit´e de S♮sous u – est
cons´equence ici de a) b) c), car on aura
u(ρ)
≡
ρ
(S♮)
u(σ)
≡
σ
(S♮) ,
ce qui implique
(25 bis)
u(x) ≡x
(S♮)
∀x ∈S+ ,
i.e. la stabilit´e de S♮et une action triviale de u sur S/S♮[plut^ot sur S+/S♮] (126).
2◦) On a encore l’´el´ement remarquable
(26)
τZ ∈Zρ,σ ,
τZ = (τ, −1, −1, −1)
(127) .
3◦) S0Gρ,σ, Gρ,σ, S0G♮
ρ,σ, G♮
ρ,σ.
Proc´edant comme page 579, on trouve
Zρ,σ
- Aut(S+) ,
126Plus g´en´eralement,
Z′′′
ρ,σ ≃









(u, µ, ε) ∈Aut(S+) × ˆZ∗× µ

a)
u(ρ) est S♮-conjugu´e `a ε[τ](ρ)
b)
u(σ) est S♮-conjugu´e `a ε[τ](σ)
c)
u(ε0) = εµ
0 .









.
127C’est une raison de plus pour ne pas exiger dans (4 d) que u op`ere trivialement sur S+/S♮, ce qui
nous ferait perdre τ !


---

108
d’o`u des produits semi-directs
(27)
S0Gρ,σ
def
= Zρ,σ · S+ ⊇S0G♮
ρ,σ
def
= Zρ,σ · S♮
et un homomorphisme
(28)
L♮
0
-

iL♮
0,G
S0G♮
ρ,σ ⊆S0Gρ,σ
l
-
iL0,Z(l) · l−1
d’image invariante, ce qui permet de poser
(29)
Gρ,σ
def
= S0Gρ,σ
| {z }
Zρ,σ·S+
/ Im L♮
0 ⊇G♮
ρ,σ = S0G♮
ρ,σ/ Im L♮
0 ,
d’o`u [des] suites exactes
(30)
1
- L♮
0
- S0G♮
ρ,σ
- G♮
ρ,σ
- 1
?
  ?
  1
- L♮
0
- S0Gρ,σ
- Gρ,σ
- 1
et [un] diagramme commutatif
(31)
Zρ,σ
-
 iZ
G♮
ρ,σ
-

Gρ,σ
6
 
iL0,Z
6
 
iS♮
6
 
iS
L♮
0
-
iL0,S S♮
-

S+ ,
s’ins´erant dans [un] diagramme commutatif de suites exactes
(32)
1
- L♮
0
- Zρ,σ
-
δZ
Υρ,σ
- 1
?
  ?
  1
- S♮
- G♮
ρ,σ
-
δG
Υρ,σ
- 1
?
  ?
  1
- S+
- Gρ,σ
- Υρ,σ
- 1 .
On consid`ere les compos´es
(33)
Gρ,σ
-
δG
Υρ,σ
  
ε2 Υ
µ
-
χΥ
ˆZ∗
@
@
R
ε3 Υ
µ ,


---

109
not´es
χG = χΥ ◦δG ,
ε2 G = ε2 Υ ◦δG ,
ε3 G = δGε3 Υ
[plut^ot ε3 G = ε3 Υ ◦δG]. On a maintenant
(34)









G′
ρ,σ, G′′
ρ,σ, G′′′
ρ,σ, G0
ρ,σ comme dans (24)
G+
ρ,σ = Ker χG, G′
ρ,σ
+, G′′
ρ,σ
+, G′′′
ρ,σ
+, G0
ρ,σ
+,
(Υ+
ρ,σ = Ker χΥ oubli´e . . . )
(128) .
Si
(35)
τG ∈G♮
ρ,σ ⊆Gρ,σ ,
τΥ ∈Υρ,σ
[page 633]
d´esignent les images de τZ (26) dans Gρ,σ, Υρ,σ, on peut faire l’identiﬁcation
(36)



S ≃image inverse de {1, τΥ} ⊆Υρ,σ dans Gρ,σ, par Gρ,σ
- Υρ,σ ,
S♮= image inverse de {1, τΥ} ⊆Υρ,σ dans G♮
ρ,σ ,
et
(37)
εS = χS|S = ε2 G|S = ε3 G|S :



trivial sur S+
−1 sur τ .
Consid´erons l’aplication canonique
(38)
G♮
ρ,σ
-

Gρ,σ
-
Aut(S+)
×
ˆZ∗
×
µ
×
µ
u
-

int(u)|S+
,
χG(u)
,
ε2 G(u)
,
ε3 G(u)

.
Proposition. C’est un homomorphisme de groupes. L’image de G♮
ρ,σ est form´ee des
syst`emes
(u, µ, ε2, ε3) ∈Aut(S+) × ˆZ∗× µ × µ
satisfaisant les conditions
(39)















a)
u(ρ) est S♮-conjugu´e `a ε3[τ]ρ ,
b)
u(σ) est S♮-conjugu´e `a ε2[τ]σ ,
c)
u(ε0) est S♮-conjugu´e `a εµ
0 ,
d)
u stabilise S♮(automatique via a), b) si ε2 = ε3) .
Son noyau est
(40)


f −1u ∈G♮
ρ,σ

u = (u, 1, 1, 1) ∈Z0 +
ρ,σ ,
f ∈S♮,
u = int(f)


.
128Itou avec G′♮
ρ,σ . . .


---

110
Corollaire. Soient
(41)
Z0 = CentrS+(L0) ,
Z♮
0 = Z0 ∩S♮= {f ∈S♮| (int(f), 1, 1, 1) ∈Zρ,σ} ,
de sorte que L♮
0 s’identiﬁe `a un sous-groupe central de Z♮
0. Consid´erons l’application
(42)
Z♮
0
-
S0G♮
ρ,σ = Zρ,σ · G♮
f
-
f −1
|{z}
∈S♮
· u(f)
|{z}
∈Zρ,σ
= u(f) · f −1 ,
o`u
u(f) = (int(f), 1, 1, 1) ∈Zρ,σ ⊆G♮
ρ,σ .
Cette application est un homomorphisme de groupes, elle induit sur L♮
0 ⊆Z♮
0 l’homo-
morphisme canonique (28),
et L♮
0
⊆
Z♮
0
est l’image inverse de iL0,SG(L♮
0)
=
Ker(S0G♮
ρ,σ
- G♮
ρ,σ). On trouve ainsi un homomorphisme injectif
(43)
Z♮
0/L♮
0
-

G♮
ρ,σ ,
dont l’image est le noyau de (38), i.e. on a une suite exacte canonique
(44)
1
- L♮
0
- Z♮
0
- G♮
ρ,σ
-
˜G♮
ρ,σ
|{z}
⊆Aut(S+)×ˆZ∗×µ×µ
- 1 ,
o`u ˜G♮
ρ,σ est form´e des (u, µ, ε2, ε3) satisfaisant les conditions (39).
Remarque. Cette proposition fait appr´ecier dans quelle mesure la construction faite
ici de G♮
ρ,σ est plus ﬁne que celle o`u on le d´eﬁnissait simplement comme un groupe
d’automorphismes de S+ (avec mˆeme au besoin des µ, ε, ε′ par dessus le march´e . . . ).
[page 634]
On va consid´erer aussi l’homomorphisme (en fait eﬀectivement moins ﬁn que (38), mˆeme
dans des cas pas du tout d´eg´en´er´es tels que S+ = SL(2, ˆZ))
(45)
G♮
ρ,σ
-
Aut(S+)
×
µ
×
µ
u
-
(int(u)|S+
,
ε3(u)
,
ε2(u))
induit par (38), son image est form´ee des syst`emes (u, ε3, ε2) tels que
(46)















a)
u(ρ) est S♮-conjugu´e `a ε3[τ](ρ) ,
b)
u(σ) est S♮-conjugu´e `a ε2[τ](σ) ,
c)
u(LS
0 ) est S♮-conjugu´e `a L0 ,
d)
u stabilise S♮(automatique si ε3 = ε2, via a), b)) .
Son noyau est
(47)


f −1u ∈G♮
ρ,σ

u = (u, µ, 1, 1) ∈Z0 +
ρ,σ ,
f ∈S♮
tel que u = int(f)


.


---

111
Pour appr´ecier la structure du noyau, soient
(48)



SN0
=
NormS+(L0) ,
SN ♮
0
=
SN0 ∩S♮= {f ∈S♮| ∃µ ∈ˆZ∗tel que (int(f), µ, 1, 1) ∈Zρ,σ} ,
et soit
(49)
S ˜
N0
=
{(u, µ) | u(ε0) = εµ
0}
⊆
SN0 × ˆZ∗
,
S ˜
N ♮
0
=
S ˜
N0 ∩(N ♮
0 × ˆZ∗)
– donc on a
(50)
S ˜
N ♮
0
-
∼
SN ♮
0
(u, µ)
-
u
si
ˆZ
-
LS
0
n
-
εn
0
est injectif
(129) .
On a un homomorphisme canonique injectif
(51)
S ˜
N ♮
0
-
S0 ˜G♮
ρ,σ = Zρ,σ · S+
(f, µ)
-
f −1 · (int(f), 1, 1, 1) = u · f −1 ,
qui induit sur L♮
0 l’homomorphisme canonique (28) (et qui prolonge (42)) – il est encore
vrai que l’image inverse de iL0,SG(L♮
0) est L♮
0 ⊆g
SN
♮
0, et on trouve ainsi une suite exacte
canonique
(52)
1
- L♮
0
- g
SN
♮
0
- G♮
ρ,σ
- ˜˜Gρ,σ
|{z}
⊆Aut(S+)×µ×µ
- 1 ,
o`u ˜˜Gρ,σ est form´e des (u, ε2, ε3) satisfaisant (16) – i.e. on a
(52 bis)
g
SN
♮
0/L♮
0 ≃Ker(G♮
ρ,σ
- Aut(S+) × µ × µ) .
[page 635]
4◦) Nρ, Nσ, Zρ, Zσ, N ♮
ρ, N ♮
σ, Z♮
ρ, Z♮
σ.
On pose
(53)



Nρ
=
{a ∈Gρ,σ | a(ρ) = ρε3 ,
o`u
ε3 = ε3(a)}
Nσ
=
{b ∈Gρ,σ | b(ρ) = ρε2 ,
o`u
ε2 = ε2(b)} .
NB Il n’y a pas lieu ﬁnalement de traˆıner des ∗en donnant une d´eﬁnition de Nρ, Nσ qui
donneraient des groupes plus gros. (Donc p. 580 je me suis autocanul´e `a ce sujet . . . )
On pose
(54)



Zρ = CentrGρ,σ(ρ) = CentrGρ,σ(Lρ) = Ker(Nρ
-
ε3 µ)
Zσ = CentrGρ,σ(σ) = CentrGρ,σ(Lσ) = Ker(Nσ
-
ε2 µ)
129Itou pour S ˜
N0.


---

112
(55)



SZρ = Zρ ∩S+ = Ker(Zρ
-
δZ Υρ,σ) = CentrS+(ρ) = CentrS+(Lρ)
SZσ = Zσ ∩S+ = Ker(Zσ
-
δZ Υρ,σ) = CentrS+(σ) = CentrS+(Lσ)
(130) ,
d’o`u
(56)
1
- Zρ
- Nρ
-
ε3 ρ µ
- 1
1
- Zσ
- Nσ
-
ε2 σ µ
- 1
(131) .
Le fait qu’on peut mettre des 1 au bout provient du fait que τ ′ ∈Nρ ∩Nσ satisfait
(57)
ε2(τ ′) = ε3(τ ′) = χ(τ ′) = −1 .
On a un merveilleux diagramme (p. 580)
(58)
Dτ ′ = µτ ′ × µ
  
@@
R
Dρ
- Nρ ∩S
| {z }
= µτ′·SZρ
-
@@
R
Nρ
@@
R
Dσ
- Nρ ∩S
| {z }
= µτ′·SZρ
-
  
Nρ
  
S
- Gρ,σ
ou mieux
(59)
µτ ′
-

Dτ ′
S

3

2
Dσ
@
@
@@
R

SNσ
@
@
@@
R

-

Nσ
@
@
@
@
@
@
@
@
@@
R

3
Dρ

3

SNρ

3

-

Nρ
6
 
6
 
6
 
6
 
6
 
6
 
6
 
6
 
6
 
1
-

µ
S+


3

2
Lσ
@
@
@
@
R

SZσ
@
@
@@
R

-

Zσ
-

G′′
ρ,σ
@
@
@
@
@
@
@
@
@@
R

3
Lρ

3

SZρ

3

-

Zρ
-

G′
ρ,σ .
s
*
Gρ,σ





66
 
O

130On d´eﬁnit de fa¸con idoine SNρ, SNσ, mais on a SNρ = SZρ, SNσ = SZσ.
131Suites exactes scind´ees par µτ ′ – la deuxi`eme aussi scind´ee par µτ.


---

113
On d´eﬁnit :
(60)
N ♮
ρ ,
N ♮
σ ,
Z♮
ρ ,
Z♮
σ ,
SZ♮
ρ ,
SZ♮
σ ,
intersection de Nρ, Nσ etc. avec S♮
ρ,σ. On a des suites exactes
(61)



1
- SZ♮
ρ
- N ♮
ρ
-
δ♮
ρ
Υρ,σ
- 1
1
- SZ♮
σ
- N ♮
σ
-
δ♮
σ
Υρ,σ
- 1 ,
et des homomorphismes de suites exactes
[page 636]
(62)





































1
- SZ♮
ρ
- N ♮
ρ
-
δ♮
ρ
Υρ,σ
- 1
?
  ?
  1
- SZρ
- Nρ
-
δρ
Υρ,σ
- 1
1
- SZ♮
σ
- N ♮
σ
-
δ♮
σ
Υρ,σ
- 1
?
  ?
  1
- SZσ
- Nσ
-
δσ
Υρ,σ
- 1 ,
(63)





































1
- Z♮
ρ
- N ♮
ρ
-
ε♮
3 ρ
µ
- 1
?
´epi
?
´epi
1
- Υ′
ρ,σ
- Υρ,σ
-
ε3 Υ
µ
- 1
1
- Z♮
σ
- N ♮
σ
-
ε♮
2 σ
µ
- 1
?
´epi
?
´epi
1
- Υ′′
ρ,σ
- Υρ,σ
-
ε3 Υ
µ
- 1
(et diagrammes analogues sans ♮).


---

114
On a donc un diagramme
(64)
1
- S♮
- G♮
ρ,σ
- Υρ,σ
- 1




ε3 Υ
µ
    
χΥ
ˆZ∗

*
ε2 Υ
µ
?
  6
 
6
 
1
- S+
- S
- µτ
- 1
L♮
0 ≃SZρ,σ
B
B
B
B
B
B
B
B
BBN
  - Zρ,σ
BB
B
BB
B
B
B
BBN
  SZ♮
ρ
- N ♮
ρ
?
  ?
  SZ♮
σ
- N ♮
σ






(cf. p. 581, (45)), et diagramme analogue sans ♮.
Je voudrais maintenant d´eﬁnir l’analogue des sous-groupes M(1/2), M′(−), M′′′(−),
N ?
ρ de p. 615 ﬀ., ce qui implique qu’on ait un groupe ⊆G♮
ρ,σ jouant le rˆole de M!
0 – l’id´eal
serait que ce soit G♮
ρ,σ lui-mˆeme. Mais dans le cas universel S = GL(2, Z)∧, S♮= π0,
d’o`u Zρ,σ = M![0] = M(0) · Lπ
0, L♮
0 = Lπ
0, on trouve Gρ,σ ≃M,
G♮
ρ,σ
=
sous-groupe de Gρ,σ = M engendr´e par S♮= π0 et par Zρ,σ = M(0) · Lπ
0
=
M(0) · π = M! ,
et non M(0) · π0 = M!
0 .
L’ennui provient ﬁnalement du fait que c’est Zρ,σ qui est trop gros ; on aimerait d´eﬁnir
dans Zρ,σ un sous-groupe qui joue le rˆole de M(0)·π0. Il n’y a pas de diﬃcult´e si on peut
d´eﬁnir dans Zρ,σ un sous-groupe qui corresponde `a M(0),
(65)
Zρ,σ(0) ⊆Zρ,σ ,
qui donne un scindage
(66)
Zρ,σ ≃Zρ,σ(0) · L♮
0
(semi-direct) ,
et on aura alors
(67)
Gρ,σ ≃Zρ,σ(0) · S+
|
{z
}
(semi-direct)
,
[page 637]
et on poserait
(68)









G♮
ρ,σ
def
=
Zρ,σ(0) · S♮
⊆
G♮
ρ,σ ⊆Gρ,σ = Zρ,σ(0) · S+
Z♮
ρ,σ
=
G♮
ρ,σ ∩Zρ,σ = Zρ,σ(0) · (L0 ∩S♮) .


---

115
Rappelons une fa¸con standard d’obtenir un scindage canonique de Zρ,σ sur Υρ,σ, quand
on dispose d’un (ρ, σ)-homomorphisme
(69)
S
- SL(2, ˆZ)′ = SL(2, ˆZ)/{±1} ,
commutant `a l’action de τ, ce qui induit un homomorphisme
(70)
Zρ,σ
- B′
0 = {
 µ λ
0 1

| µ ∈ˆZ∗, λ ∈ˆZ}
grˆace `a l’´etude du §48, induisant
(71)



L♮
0
-
L′
0 = {
 1 λ
0 1

| λ ∈ˆZ}
εn
0
-
 1 n
0 1

.
Plus pr´ecis´ement, on a un diagramme de suites exactes
(72)
1
- L♮
0
- Zρ,σ
- Υρ,σ
- 1
?
  εn
0
?
n
?
?
χΥ
1
- ˆZ
- B′
0
-
det
ˆZ∗
- 1 .
λ
- 1 λ
0 1

µ λ
0 1

- µ
Si l’homomorphisme (71) est un isomorphisme, alors tout scindage de la deuxi`eme suite
exacte en d´eﬁnit par image inverse un de la premi`ere. Mais dans les cas typiques qui nous
[int´eressent], L♮
0 (qui n’est pas assez petit pour donner ‘le bon’ G♮
ρ,σ !) n’est pas assez
gros par contre pour donner un isomorphisme dans (71) ! Mais on peut aussi faire une
hypoth`ese suppl´ementaire – savoir que l’image inverse par (70) du ‘tore’ section
(73)
T ′
0 = {
 µ 0
0 1

| µ ∈ˆZ∗} ⊆B′
0 ,
qui est un sous-groupe
(74)
Zρ,σ(0)
=
{u ∈Zρ,σ | son image
 µ λ
0 1

est dans T ′
0, i.e. λ = 0}
⊆
Zρ,σ
satisfaisant
(75)
Zρ,σ(0) ∩Lµ
0 = {1} ,
soit en fait un sous-groupe section ; i.e. que Zρ,σ(0)
-

Υρ,σ soit ´epimorphique, i.e.
isomorphique ; i.e. que l’on a bien
(76)
Zρ,σ = Zρ,σ(0) · L♮
0 .
J’ai de bonnes raisons de penser que (d`es que (69) existe) cette condition est satisfaite
dans tous les cas vraiment utiles. Ce choix d’un
[page 638]
Zρ,σ(0) a la bonne propri´et´e d’ailleurs d’ˆetre ‘fonctoriel’ dans un sens ´evident (cf. plus bas
les questions de fonctorialit´e), ce qui sera essentiel pour avoir un bon formalisme. Ceci


---

116
nous permet donc de d´eﬁnir un sous-groupe (G♮
ρ,σ)0 ⊆G♮
ρ,σ par (68). Si sa d´eﬁnition
n’´etait ainsi un peu trop alambiqu´ee, c’est [ce] groupe ‘plus ﬁn’ qui serait meilleur, et
m´eriterait en fait la notation plus simple G♮
ρ,σ.
Autre fa¸con de proc´eder ?
On cherche en somme des restrictions ad´equates dans la
d´eﬁnition de Zρ,σ, qui impliquent que L♮
0 = L0 ∩S, i.e. que pour l ∈L0, on a
(int(l), 1, 1, 1) ∈Zρ,σ
⇐⇒
l ∈S♮.
Mais dans le cas universel, avec S♮= π0, prenant l = l0, son image dans S/S♮= S/π0 est
l’´el´ement central non trivial de S/π0, l’automorphisme int´erieur qu’il d´eﬁnit dans S+/π0
(et mˆeme dans S/π0) est trivial – donc ce n’est pas par des propri´et´es de cette action
qu’on arrivera `a l’exorciser !
Mais peut-ˆetre est-il pr´ematur´e d’essayer d´ej`a de ‘d´ecouper’ nos groupes G♮
ρ,σ, M♮
ρ,σ ‘aussi
ﬁn que possible’ – peut-ˆetre y a-t-il encore des erreurs d’orientation assez grossi`eres, qui
se rectiﬁeront par l’examen de cas particuliers. Donc je vais renoncer pour l’instant `a con-
tinuer `a investir de l’´energie aux d´ecoupages, et m’en tiendrai donc l`a dans ce sens, quitte
`a y revenir par la suite et `a raﬃner les constructions pr´esentes, qu’il faudra cependant
comparer `a l’occasion `a celles de §48, XI.
[page 639]
5◦) S0M♮
ρ,σ, M♮
ρ,σ, S0Γρ,σ, Γρ,σ . . .
On posera comme dans p. 583
(77)



S0Mρ,σ
=
Zρ,σ ×Υρ,σ N ♮
ρ ×Υρ,σ N ♮
σ ×Υρ,σ Gρ,σ
S0M♮
ρ,σ
=
Zρ,σ ×Υρ,σ N ♮
ρ ×Υρ,σ N ♮
σ ×Υρ,σ G♮
ρ,σ
(78)



Mρ,σ
=
N ♮
ρ ×Υρ,σ N ♮
σ ×Υρ,σ Gρ,σ
M♮
ρ,σ
=
N ♮
ρ ×Υρ,σ N ♮
σ ×Υρ,σ G♮
ρ,σ
(79)



S0Γρ,σ
=
Zρ,σ ×Υρ,σ N ♮
ρ ×Υρ,σ N ♮
σ
Γρ,σ
=
N ♮
ρ ×Υρ,σ N ♮
σ ,
d’o`u [un] diagramme de suites exactes
(79)
1
- S+
-

Mρ,σ
- Γρ,σ
- 1
6
 
6
 
6
 
1
- S♮
-

M♮
ρ,σ
- Γ♮
ρ,σ
- 1
@@
@@
@@
@@
@
@
R

@
@
R

@
@
R

@
@
R

1
- S+
-

S0Mρ,σ - S0Γρ,σ
- 1
6
 
6
 
6
 
1
- S♮
-

S0M♮
ρ,σ - S0Γ♮
ρ,σ
[132] ,


---

117
et des (homomorphismes de) suites exactes
(81)
1
-
= L♮
0
z }| {
SZρ,σ ×SN ♮
ρ × SN ♮
σ × S♮
- S0M♮
ρ,σ
- Υρ,σ
- 1
?
  ?
  1
- SZρ,σ
| {z }
= L♮
0
×SN ♮
ρ × SN ♮
σ × S+
- S0Mρ,σ
- Υρ,σ
- 1
[133]
(82)
1
- SN ♮
ρ × SN ♮
σ × S♮
- M♮
ρ,σ
- Υρ,σ
- 1
?
  ?
  1
- SN ♮
ρ × SN ♮
σ × S
- Mρ,σ
- Υρ,σ
- 1
(83)
1
- L♮
0 × SN ♮
ρ × SN ♮
σ
- S0Γρ,σ
- Υρ,σ
- 1
(84)
1
- SN ♮
ρ × SN ♮
σ
- Γρ,σ
- Υρ,σ
- 1 ,
[et]
(85)



S0Mρ,σ
≃
Mρ,σ ×Υρ,σ Zρ,σ
S0M♮
ρ,σ
≃
M♮
ρ,σ ×Υρ,σ Zρ,σ
(86)
S0Γρ,σ ≃Γρ,σ ×Υρ,σ Zρ,σ
(87)



S0Mρ,σ
≃
Mρ,σ ×Γρ,σ S0Γρ,σ
S0M♮
ρ,σ
≃
M♮
ρ,σ ×Γρ,σ S0Γρ,σ .
Remarque. Cette d´egel´ee de groupes donne un peu le mal de mer. Je ne suis pas sˆur que
les variantes S0 (S0M, S0M♮, S0Γ) soient tr`es utiles. Reste la comparaison [?] entre des
invariants avec ou sans ♮, surtout donc Mρ,σ et M♮
ρ,σ – dont la ‘diﬀ´erence’ est ‘la mˆeme’
qu’entre S+ et S♮, et entre Gρ,σ et G♮
ρ,σ ; de fa¸con pr´ecise, Mρ,σ est invariant dans M♮
ρ,σ,
et G♮
ρ,σ dans Gρ,σ ; on a des isomorphismes
(88)
S+/S♮
-
∼
Gρ,σ/G♮
ρ,σ
-
∼
Mρ,σ/M♮
ρ,σ .
Les groupes Gρ,σ, Mρ,σ jouent par rapport `a G♮
ρ,σ, M♮
ρ,σ le rˆole de fourre-tout, notamment
pour nous permettre de consid´erer les automorphismes ρ, σ de G♮
ρ,σ, M♮
ρ,σ comme induits
par des automorphismes int´erieurs de groupes
132[Deux fois (79).]
133[(80) n’existe pas.]


---

118
[page 640]
environnants Gρ,σ, Mρ,σ.
On a un ´el´ement
(89)
τ ′
M = ( τ ′
ρ
|{z}
∈N ♮
ρ
, τ ′
σ
|{z}
∈N ♮
σ
, τ ′
G
|{z}
∈G♮
ρ,σ
)
au dessus de τ ′
γ ∈Υρ,σ, d’o`u des plongements canoniques
(90)
S♮
τ
-

M♮
ρ,σ
?
  ?
  S
-

Mρ,σ
S♮= image inverse dans Mρ,σ de {1, τΥ} ⊆Υρ,σ
S = image inverse dans Mρ,σ de {1, τΥ} ⊆Υρ,σ
[plut^ot S♮image inverse dans M♮
ρ,σ]. On peut reprendre le diagramme bord´elique
de p. 584, avec des ♮`a la clef . . .
Je vais voir si je peux me dispenser justement de red´evelopper les liens avec Σρ,σ, SGρ,σ
etc. – quitte `a y revenir au besoin par la suite.
6◦) Fonctorialit´es.
(134). Cf. p. 588. En plus de l’homomorphisme surjectif
(91)
S
-
ϕ S′
(135) ,
on suppose que ϕ applique S♮dans S′♮. On d´esignera ici par Zρ,σ, Mρ,σ etc. les invariants
associ´es `a S, [par] Zρ′, σ′ etc. ceux de S′. On a des conditions ´equivalentes comme dans
loc. cit. – o`u on va laisser tomber la consid´eration de ΣS
ρ,σ . . . – qui signiﬁaient que pour
tout
u = (u, µ, ε2, ε3) ∈Zρ,σ
il existe un automorphisme u′ de S′ rendant commutatif
(92)
S+
-
ϕ
S′+
?
u
?
u′
S+
-
ϕ
S′+ ,
lequel u′ sera unique. Il revient au mˆeme de dire que les u ∈Aut(S+) qui proviennent de
Zρ,σ, i.e. qui normalisent L0, et qui transforment ρ, σ en des ´el´ements S♮
τ-conjugu´es `a ρ,
σ, stabilisent le noyau de ϕ (91). On trouve alors
[page 641]
(93)
Zρ,σ
-
ϕZ
Zρ′, σ′ ,
134NB Jusqu’ici (dans 1◦) `a 5◦)) on n’avait pas utilis´e l’hypoth`ese que ρ, σ engendrent S+.
135Il vaut mieux [le] noter S0
- S, cf. p. 643 ﬀ. . . .


---

119
compatible avec les actions de Zρ,σ, Zρ′, σ′ sur S+ resp. S′+, et avec les homomorphismes
Zρ,σ ⊇L♮
0
- S+ ,
Zρ′, σ′ ⊇L′♮
0
- S′+ ,
d’o`u par la construction standard un homomorphisme
(94)
Gρ,σ
-
ϕG Gρ′, σ′
induisant
(95)
G♮
ρ,σ
-
ϕG♮G♮
ρ′, σ′ ,
d’o`u un homomorphisme du diagramme (64) relatif `a (σ, ρ), dans le diagramme analogue
relatif `a (ρ′, σ′), avec ou sans ♮. Il n’en faut pas plus pour que toutes les constructions et
diagrammes du num´ero pr´ec´edent, relatives `a ρ, σ, s’envoient dans celles relatives `a ρ′, σ′.
Remarque. Supposons que S′, S′♮satisfassent `a la condition suivante :
(96)























































Pour tout couple d’´el´ements α′, β′ ∈S′♮
τ, tels que l’on ait
[∗]
[α′, ρ] = [β′, σ]εµ−1
1
pour µ ∈ˆZ convenable
il existe un u′ ∈Aut(S′+) tel que
(97)
u′(ρ) = α′(ρ) ,
u′(σ) = β′(σ) ,
i.e.
(98)
α′−1u′ ∈CentrAut(ρ) ,
β′−1u′ ∈CentrAut(σ) ,
la relation des lacets [∗] s’exprimant en termes de u par la condition
(99)
u′(LS′
0 ) = LS′
0 ,
i.e. u′ normalise S′ .
Alors tout (ρ, σ)-homomorphisme (S, S♮)
- (S′, S′♮) est n´ecessairement admissible.
Nous allons appliquer ceci au cas o`u S est universel – mais pour pouvoir en dire tout ce
qu’on a envie, je vais d’abord parler des sous-groupes
M(0) , M(ρ) , M(σ)
⊆
Mρ,σ .
[page 642]
7◦) Les groupes Mρ,σ[0], Mρ,σ(ρ), Mρ,σ(σ).
Dans le groupe
(100) S0M♮
ρ,σ
=
Zρ,σ ×Υρ,σ N ♮
ρ ×Υρ,σ N ♮
σ ×Υρ,σ G♮
ρ,σ
=
{x = (u, a, b, U) ∈Zρ,σ × N ♮
ρ × N ♮
σ × G♮
ρ,σ | δZ(u) = δρ(a) = δσ(b) = δG(U)} ,


---

120
on introduit trois sous-groupes
(101)









S0Mρ,σ(0)
⊆
S0M♮
ρ,σ
par [la] condition
U
=
iZ(u)
S0Mρ,σ(ρ)
⊆
S0M♮
ρ,σ
par [la] condition
U
=
iρ(a)
S0Mρ,σ(σ)
⊆
S0M♮
ρ,σ
par [la] condition
U
=
iσ(b)
en utilisant maintenant les trois homomorphismes canoniques
(102)









iZ
:
Zρ,σ
-

Gρ,σ
iρ
:
Nρ
-

Gρ,σ
iσ
:
Nσ
-

Gρ,σ .
Ces trois groupes sont manifestement tous trois isomorphes `a Zρ,σ ×Υρ,σ N ♮
ρ ×Υρ,σ N ♮
σ =
S0Γρ,σ ; de fa¸con pr´ecise, dans la suite exacte (52),
1
- S+
- S0Mρ,σ
- S0Γρ,σ
- 1 ,
l’homomorphisme canonique S0Mρ,σ
- S0Γρ,σ induit des isomorphismes entre les groupes
(68) et S0Γρ,σ ; ces trois groupes sont donc des sous-groupes sections.
On d´eﬁnit Mρ,σ[0], Mρ,σ(ρ) (ou Mρ,σ(1/2)) et Mρ,σ(σ) (ou Mρ,σ(−)) comme les images
de S0Mρ,σ(0), S0Mρ,σ(ρ) et S0Mρ,σ(σ) par l’homomorphisme canonique S0Mρ,σ
- Mρ,σ,
ce qui revient `a poser
(103)









Mρ,σ[0]
=
{(a, b, U) ∈M♮
ρ,σ | U ∈Zρ,σ}
Mρ,σ(ρ)
=
{(a, b, U) ∈M♮
ρ,σ | U = a}
Mρ,σ(σ)
=
{(a, b, U) ∈M♮
ρ,σ | U = b} .
Donc les sous-groupes Mρ,σ(ρ), Mρ,σ(σ) de M♮
ρ,σ sont des groupes sections au dessus de
Γ♮
ρ,σ ≃N ♮
ρ ×Υρ,σ N ♮
σ, donc
(104)



M♮
ρ,σ
≃
Mρ,σ(ρ) · S♮
M♮
ρ,σ
≃
Mρ,σ(σ) · S♮
(semi-directs) ,
et de mˆeme
(105)



Mρ,σ
≃
Mρ,σ(ρ) · S+
Mρ,σ
≃
Mρ,σ(σ) · S+
(semi-directs) .
D’autre part, on aura
(106)
1
- L♮
0
- Mρ,σ[0]
- Γρ,σ
- 1
S0Mρ,σ[0]
6
≀
?
≀
1
- L♮
0
- S0Γρ,σ
- Γρ,σ
- 1 ,


---

121
donc l’extension Mρ,σ[0] de Γρ,σ par L♮
0 s’identiﬁe `a l’extension S0Γρ,σ de Γρ,σ par L♮
0, i.e.
`a l’image inverse de l’extension Zρ,σ de Υρ,σ par L♮
0, via l’homomorphisme canonique
[page 643]
(107)
Γρ,σ = N ♮
ρ ×Υρ,σ N ♮
σ
- Υρ,σ .
Donc la donn´ee d’une section de Zρ,σ sur Υρ,σ (cf. `a ce sujet p. 636 ﬀ.) en d´eﬁnit une de
S0Γρ,σ sur Γρ,σ, donc de Mρ,σ[0] sur Γρ,σ. Quand une telle section est ﬁx´ee, on d´enote ce
groupe section par
Mρ,σ(0) ⊆M♮
ρ,σ ,
donc on aura
(108)









Mρ,σ[0]
≃
Mρ,σ(0) · L♮
0
M♮
ρ,σ
≃
Mρ,σ(0) · S♮
Mρ,σ
≃
Mρ,σ(0) · S
[plut^ot Mρ,σ ≃Mρ,σ(0) · S+].
8◦) Retour sur le cas universel, et l’homomorphisme M♮
- M♮
ρ,σ/µρ.
Nous supposons maintenant que S correspond au cas universel GL(2, Z)∧, avec un S♮
quelconque. On va noter le cas universel par un indice 0 : S0, S+
0 , S♮
0 etc. (136), et S′,
S′♮etc. se noteront S, S♮etc.
Je pose
(107)
M♮
=















u ∈M

a)
u(ρ) est S♮-conjugu´e `a ε3[τ](ρ)
b)
u(σ) est S♮-conjugu´e `a ε2[τ](σ)
c)
u(ε0) est S♮-conjugu´e `a εµ
0
d)
u stabilise M♮















⊆M
[137] ,
o`u bien sˆur
µ = χ(u) ,
ε2 = ε2(u) = ε2(µ) ,
ε3 = ε3(u) = ε3(µ)
(138) .
Je dis que M♮est un sous-groupe de M. On peut le voir en reprenant les calculs de la p.
629 ﬀ. Je pr´ef`ere proc´eder ainsi.
[page 644]
On a vu qu’on a
(108)
Zρ0,σ0
-

M[0] = M(0) · LS
0
≃M∼
0,3[0] = M∼
0,3(0) · LS0
0
,
inclusion qui est une ´egalit´e si S♮
0 = S+
0 , et qui identiﬁe Zρ,σ `a M![0] = M(0) · Lπ
0 si
S♮
0 = π ou = π0.
136Ou Zρ0,σ0 etc. . . . On ´ecrira S+
0 au lieu de S+ ∧
0
.
137[Saut dans la num´erotation.]
138NB M♮⊇µ.


---

122
h
(139) En fait, si S♮
0 ⊆π0, alors on trouve
(109)
Zρ,σ =









u =
u0
|{z}
∈M(0)
·
l
|{z}
∈Lπ
0

a)
u(ρ) = α(ρ) avec α ∈S♮
τ
b)
u(σ) = β(σ) avec β ∈S♮
τ
c)
u stabilise S♮









,
et on note que α, β dans a), b) sont d´etermin´es par u = u0l de fa¸con unique, mˆeme
si on suppose seulement u ∈M![0] sans plus, et qu’on exige α, β ∈π0 τ. On sait que
c’est un sous-groupe de Aut(S+
0 ) × ˆZ∗× µ × µ – et en fait, de Aut(S+
0 ) (prop. p. 629).
Comme ce groupe op`ere sur S via M∼
0,3, et mˆeme via M∼!
0,3[0], il s’envoie dans M∼!
0,3[0]
par un homomorphisme de groupes, donc dans M![0] ≃M∼
0,3[0] par un homomorphisme
de groupes.
i
Consid´erons le syst`eme
(110)

S+
0 , Zρ0,σ0, L♮
0
-

Zρ0,σ0, Zρ0,σ0
- Aut(S0), L♮
0
-

S+
0

(cf. ‘digression’ plus bas, 9◦)), qui donne naissance `a
(110′)
Gρ0,σ0 ,
S+
0 ⊆Gρ0,σ0 ,
Zρ0,σ0
-

Gρ0,σ0 ,
et consid´erons le syst`eme analogue `a (110)
(111)


S+
0 ,
M[0]
| {z }
= M(0)·Lπ
0
,
LS
0
|{z}
(engendr´e par ε0)
-

M[0], M[0]
- Aut(S0), LS
0
-

S+
0


,
qui donne naissance (loc. cit. (9◦)) `a la situation
(111′)
 M ,
S+
0 ⊆M ,
M[0]
-

S+
0

.
Or grˆace `a (108), on a un homomorphisme de (110) dans (111), correspondant `a l’identit´e
sur S+
0 , (108) sur Zρ0,σ0, l’inclusion canonique L♮
0
-

LS
0 . Il en r´esulte un homomor-
phisme de (110′) dans (111′), en particulier un homomorphisme canonique de suites ex-
actes
[page 645]
(112)
1
- S+
0
- Gρ0,σ0
- Υρ0,σ0
- 1
?
?
1
- S+
0
- M
- Γ∼
Q
- 1 ,
o`u
Υρ0,σ0
| {z }
≃Zρ0,σ0/Lµ
0
-
ΓQ
|{z}
≃M[0]/LS
0
est aussi induit par (108), et s’identiﬁe `a
(113)
Zρ0,σ0/Lµ
0
- M[0]/LS
0 .
139Cette explicitation ne semble servir `a rien.


---

123
Par d´eﬁnition mˆeme de L♮
0 comme ´etant essentiellement Zρ0,σ0 ∩S+
0 , on voit que (113) est
injectif, donc Gρ0,σ0
- M est toujours injectif (c’est un isomorphisme si S♮
0 ⊇π0 . . . ).
On d´eduit par composition de (112) un homomorphisme de suites exactes
(114)
1
- S♮
0
- G♮
ρ0,σ0
- Υρ0,σ0
- 1
?
?
1
- S+
0
- M
- Γ∼
Q
- 1 .
On voit alors imm´ediatement que l’image de G♮
ρ0,σ0 dans M n’est autre que M♮(107).
On a donc
(115)







M♮
|{z}
d´eﬁni dans (107)
-
∼
G♮
ρ,σ
Υρ0,σ0
-

Γ∼
Q
(140) ,
ce qui montre en mˆeme temps dans la foul´ee que M♮est bien un sous-groupe de M.
On a maintenant
(117)
M♮
ρ0,σ0
def
= N ♮
ρ0 ×Υρ0,σ0 N ♮
σ0 ×Υρ0,σ0 G♮
ρ0,σ0
| {z }
≃M♮
,
o`u
G♮
ρ0,σ0
≃
M♮,
donc
N ♮
ρ0
≃
{u ∈M♮| u(ρ) = ρε3(u)}
N ♮
σ0
≃
{u ∈M♮| u(σ) = σε2(u)} ,
et ﬁnalement on a
(118)



M♮
ρ0,σ0 ≃NM♮(ρ) ×Γ♮
0 NM♮(σ) ×Γ♮
0 M♮,
o`u Γ♮
0 = Υ0 = Υρ0,σ0 ⊆Γ∼
Q , explicit´e dans (116) ,
d’o`u une suite exacte
(119)
1
-
= Lρ×Lσ
z
}|
{
SZρ0 × SZσ0
- M♮
ρ0,σ0
- M♮
- 1 ,
o`u le noyau SZρ0 × SZσ0 est un groupe tout petit, savoir
140NB On a
(116)
Υρ0,σ0 = Γ♮
Q =


u ∈Γ∼
Q

le rel`evement u0 de u en u0 ∈M(0)
satisfait les conditions a) b) d) de (107)



(not´e aussi Υ0 = Γ♮
0, si Γ0 d´enote Γ∼
Q) (141).
141 `A v´eriﬁer.


---

124
[page 646]
(120)
Ker(M♮
ρ0,σ0
-
´epi M♮) ≃SZρ0 × SZσ0 ≃Lρ × Lσ ≃Z/6Z × Z/4Z .
Nous allons am´eliorer encore la situation en d´ecoupant dans M♮
ρ0,σ0 un groupe encore plus
petit, qui soit une extension de M♮par µ.
Notons que
(121)
M♮
ρ0,σ0 = N ♮
ρ0 ×Γ♮
0 N ♮
σ0 ×Γ♮
0 G♮
ρ0,σ0
| {z }
= M♮
⊆N ♮
ρ0 ×Γ0 N ♮
σ0 ×Γ0 M ,
o`u Γ0
def
= Γ∼
Q, et o`u ce dernier produit ﬁbr´e n’est autre que la quantit´e M(♮′)
ρ0,σ0 qui corre-
spondrait au cas de S♮′
0 = S+
0 tout entier (not´e Mρ,σ `a la page 626 et suivantes). Dans ce
groupe on a d´eﬁni le sous-groupe, qui ´etait not´e M♮
ρ,σ `a la page 626, et que je vais plutˆot
noter maintenant M?
ρ,σ, d´eﬁni comme
(122)
M? = N ?
ρ ×Γ0 Z!
σ 0 ×Γ0 M
[142] ,
o`u, on rapelle,
(123)















Nρ0 = NormM(Lρ0) ,
Nσ = NormM(Lσ0) ,
Zσ = CentrM(Lσ0) = CentrM(σ0) ,
N ?
ρ0 = Z!
ρ0 · µτ ′ ⊆Nρ0 ,
o`u Z!
ρ0 = Zρ0 ∩M! ,
N ?
σ0 = Z!
σ0 ∩M!
0 ( = Nσ0 ∩M!
0 )
⊆Nσ0 ,
de sorte qu’on a bien
M? ⊆Nρ0 ×Γ0 Nσ0 ×Γ0 M
(143) .
Ceci rappel´e, on va poser
(124) M♮?
ρ0,σ0 = M♮
ρ0,σ0 ∩M? ⊆M♮
ρ0,σ0
(intersection dans Nρ0 ×Γ0 Nσ0 ×Γ0 M) ,
et consid´erer l’homomorphisme induit par (119),
(125)
M♮?
ρ0,σ0
- M♮
?
  ?
  M?
- M .
142[Plut^ot N ?
ρ0 comme premier facteur ?
Z!
σ0 0 comme deuxi`eme ?
- Questions similaires
dans ce qui suit.]
143Ind´ependant du choix d’un S♮.


---

125
[page 647]
On a vu (p. 626, (55)) que M?
- M fait de M? une extension de M de noyau µρ. Donc
le noyau de M?
ρ0,σ0
- M♮est ´egal `a µρ ∩M?
ρ0,σ0, or il est clair que l’on a µρ ⊆M♮
ρ0,σ0,
cf. (114), donc µρ ⊆M♮?
ρ0,σ0. On trouve donc un homomorphisme de suites exactes
(126)
1
- µρ
-
⊆M♮
ρ0,σ0
z }| {
M?
ρ0,σ0
- M♮
?
  ?
  1
- µρ
- M?
- M
- 1 ,
et il reste `a voir si l’homomorphisme
(∗)
M?
ρ0,σ0
- M♮
est un ´epimorphisme, et sinon, caract´eriser son image. Notons que la d´eﬁnition (124)
donne aussi, compte tenu des expressions (118) pour M♮
ρ0,σ0 et (122) pour M?
(127)
M♮?
ρ0,σ0 ≃N ♮?
ρ0 ×Γ♮
0 Z♮!
σ0 0 ×Γ♮
0 M♮
(144) ,
o`u on a pos´e
(128)



N ♮?
ρ0
= N ?
ρ0 ∩N ♮
ρ0 = N ?
ρ0 ∩M♮
Z♮!
σ0 0 = Z!
σ0 0 ∩N ♮
ρ0 = Z!
σ0 0 ∩M♮,
et l’homomorphisme (∗) n’est autre que la troisi`eme projection du produit ﬁbr´e. Donc
l’image de (∗) n’est autre que l’image inverse, dans M♮, par M♮
- Υ0 = Υρ0,σ0 de l’image
de
(∗∗)
N ♮?
ρ0 ×Γ♮
0 N ♮!
σ0 0
- Γ♮
0 (
-

Γ0 ) .
Il reste donc `a montrer que cet homomorphisme est surjectif, ou encore que les homomor-
phismes



N ♮?
ρ0
-
Γ♮
0
N ♮!
σ0 0
-
Γ♮
0
sont surjectifs (le premier sera alors une extension de Γ♮
0 par µρ, le deuxi`eme un isomor-
phisme). Soit donc u ∈Γ♮
0, provenant de u ∈M♮≃G♮
ρ,σ, satisfaisant donc aux conditions
a), b), c), d) de (107). On voit donc qu’il existe β0 ∈S♮
0 ⊆M♮tel que β−1u0 ∈N(σ0).
Ici j’ai arrˆet´e les v´eriﬁcations, pensant y revenir dans les jours suivants ; il s’av`ere que
ce n’est pas urgent – il importait plutˆot de d´evelopper le cas particulier ‘tour de Fermat’
pour pr´eciser les id´ees du formalisme g´en´eral des Mρ,σ . . .
144Υ0 = Im(M♮) ⊆Γ∼
Q


---

126
[page 648]
9◦) Digression de formalisme des groupes.
amSoient
(1)
G ,
S ⊆G ,
N
-

ϕN
G ,
d’o`u SN = ϕ−1(S) ⊆N
la situation d’un groupe G, sous-groupe invariant S, et sous-groupe N tels que
(2)
N
-
´epi G/S ,
i.e. N/SN
-
∼
G/S .
On va reconstituer cette situation `a partir de la suivante :
(2)
S ,
N ,
SN ⊆N ,
N
-
θ
Aut(S) ,
SN
-
ϕ = ϕSN
S
[145] ,
o`u S, N sont des groupes, SN un sous-groupe distingu´e de N, N
- Aut(S) un homo-
morphisme de groupes, i.e. une action de N sur S, enﬁn SN
- S un homomorphisme
de groupes. On suppose que
(3)







a)
l’action de SN sur S induite par celle de S, soit aussi celle d´eduite de
SN
- S, via l’op´eration adjointe de S, et
b)
SN
- S est compatible avec [l’]action de N.
Il est clair comment (1) d´eﬁnit (2), montrons comment un syst`eme (2) permet de recon-
stituer un syst`eme (1). On part donc de (2), on pose
(4)
S0G = N · S
(semi-direct) ,
on d´eﬁnit un homomorphisme
(5)



SN
-

i
S0G
u
-
u · ϕ(u)−1 = ϕ(u)−1 · u
(146) .
V´eriﬁons que c’est un homomorphisme :
i(u′u)
=
(u′u)ϕ(u′u)−1
i(u′)i(u)
=
u′ϕ(u′)−1uϕ(u)−1
=
u′u(u−1ϕ(u′)u
|
{z
}
= ϕ(u−1)ϕ(u′−1)ϕ(u) par (∗)
)ϕ(u−1)
=
u′uϕ(u−1u′−1 ̸u ̸u−1)
=
(u′u)ϕ((u′u)−1)
=
(u′u)ϕ(u′u)−1 ,
OK.
145[Deux fois (2).]
146NB On a, par hypoth`ese (a), pour u ∈SN, x ∈S
(∗)
u(x) = u x u−1
| {z }
dans S0G = N · S
= ϕ(u) x ϕ(u)−1 ,
donc si x = ϕ(u), on a u(x) = uxu−1 = x, i.e. x = ϕ(u) et u commutent.


---

127
On n’a pas encore utilis´e le fait que [SN] soit distingu´e dans N, et l’hypoth`ese (b) ; ceci
implique que l’image de (4) est distingu´ee dans S0G, car on a, si a ∈N, u ∈SN,
a(u · ϕ(u)−1)a−1 = aua−1
| {z }
∈SN
· aϕ(u−1)a−1
|
{z
}
= ϕ(au−1a−1)
,
i.e. l’homomorphisme (5) commute aux actions de N sur SN et sur S0G ⊇N, donc
l’image de SN est normalis´ee par N ⊆S0G. Il faut encore v´eriﬁer qu’elle est normalis´ee
´egalement par S, mais on a mieux : l’image de SN
-
i
S0G commute `a S, i.e.
[page 649]
pour tout u ∈SN, uϕ(u)−1 induit l’op´eration triviale sur S – ce qui est en eﬀet trivial
par (3 a).
On peut donc poser
(6)
G
def
= S0G/i(SN) ,
on trouve alors un diagramme commutatif
(7)
SN
  

N
@@
R
ϕN
@@
R
ϕSN
S
  

G ,
on voit que l’image de S dans G est un sous-groupe invariant, et que l’on a un isomor-
phisme aur les quotients
(8)
N/SN
-
∼
G/S ,
ce qui implique que l’on a aussi un isomorphisme
(9)
Ker(SN
-
ϕSN S)
-
∼
Ker(N
-
ϕN
G) ,
donc
(10)
ϕN
:
N
-
G
est un plongement
⇕
ϕSN
:
SN
-
S
est un plongement .
On trouve ainsi des ´equivalences de cat´egories inverses l’une de l’autre, entre la cat´egorie
des situations (1), et celle des situations (2).
bmConsid´erons maintenant une situation
(11)



G ,
S ⊆G ,
(ϕi : Ni
- G)i∈I
d’o`u des SNi = ϕ−1
i (S) ,
avec la condition
(12)
∀i ∈I ,
ϕi : Ni
- G/S = Υ
´epimorphique ,


---

128
peut-on la reconstituer `a partir de
(13)
S ,
( Ni , SNi , ϕi , θi )i∈I ,
o`u pour tout i ∈I, (Ni, SNi, ϕi, θi) satisfait les conditions (3 a, b) – o`u bien sˆur pour
tout i ∈I
(14)
θi : Ni
- Aut(S) ,
ϕi : SNi
- S .
Il est tentant de reconstituer G `a l’aide de S et des Ni, comme une sorte de ‘somme
amalgam´ee’ relative `a
SNi
  

plongement
Ni
R
@@
R
ϕi
S

G .
[page 650]
Mais il est plus raisonnable de dire que pour tout i, on reconstitue via (Ni, SNi, ϕi, θi) la
situation (pour i ﬁx´e)
(15)
Ni
- Gi ( ≃G )
6
 
6
 
SNi
- S ,
et qu’on reconstitue (11) lui-mˆeme en se donnant un syst`eme transitif d’isomorphismes
entre les Gi (i ∈I), induisant l’identit´e sur S. Une telle donn´ee implique en premier lieu
la donn´ee d’un syst`eme transitif d’isomorphismes entre les
(16)
Υi
def
= Ni/SNi
– qu’on identiﬁera donc `a un mˆeme groupe
(17)
Υ ,
groupe quotient commun des Ni (par les SNi) .
Identiﬁons maintenant Gi/S ≃Υi `a Υ,
(18)
Gi/S ≃Υ ,
et formons le produit ﬁbr´e
(19)
G =
Y
i∈I Υ
Gi ⊇SI
(147) .
La donn´ee d’un syst`eme transitif d’isomorphismes entre les Gi, induisant l’identit´e sur
les sous-groupes S, et compatible avec le syst`eme transitif d’isomorphismes d´ej`a envisag´e
147G est extension de Υ par SI.


---

129
entre les Υi = Ni/SNi ≃Gi/S, ´equivaut alors `a la donn´ee d’un sous-groupe G de G,
satisfaisant les conditions
(20)



a)
G ∩SI = diagonale δ(S) de SI ,
b)
L’homomorphisme G
- Υ est ´epimorphique .
En d’autres termes, on a construit `a l’aide de (13) et des sy`emes transitifs d’isomorphismes
entre les Υi, une extension G de leur ‘valeur commune’ Υ par SI – et la structure
suppl´ementaire (∗) est la ‘restriction’ de cette extension en une extension de Υ par le
sous-groupe diagonal de SI.


---
