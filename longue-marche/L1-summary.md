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