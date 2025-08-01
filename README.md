# Frontend Mentor - Suite landing page solution

Ceci est ma solution au défi [Suite landing page sur Frontend Mentor](https://www.frontendmentor.io/challenges/suite-landing-page-tj_eaU-Ra). Les défis de Frontend Mentor m’aident à améliorer mes compétences en HTML et CSS en réalisant des projets concrets basés sur des maquettes professionnelles.

## Table des matières

- [Aperçu](#aperçu)
  - [Le défi](#le-défi)
  - [Capture d’écran](#capture-décran)
  - [Liens](#liens)
- [Mon processus](#mon-processus)
  - [Technologies utilisées](#technologies-utilisées)
  - [Ce que j’ai appris](#ce-que-jai-appris)
  - [Développement futur](#développement-futur)
  - [Ressources utiles](#ressources-utiles)
- [Auteur](#auteur)
- [Remerciements](#remerciements)

## Aperçu

### Le défi

Les utilisateurs doivent pouvoir :

- Visualiser la mise en page idéale selon la taille de l’écran (desktop, tablette, mobile)
- Voir les effets au survol (hover) sur les éléments interactifs
-Accéder à une interface propre et bien alignée


### Capture d’écran

![Aperçu du design](image-1.png)

![Aperçu du design](image-2.png)

![Aperçu du design](image-3.png)

> ⚠️ Remplace `screenshot.jpg` par une capture réelle de ton site (tu peux utiliser Firefox ou l'outil FireShot).

### Liens

- Code source : [https://github.com/MouhamedSyll22/SUITE-LANDING-PAGE](https://github.com/MouhamedSyll22/SUITE-LANDING-PAGE)
- Site en ligne : [ https://mouhamedsyll22.github.io/SUITE-LANDING-PAGE/]( https://mouhamedsyll22.github.io/SUITE-LANDING-PAGE/)

## Mon processus

### Technologies utilisées

- HTML5 sémantique
- CSS personnalisé avec variables
- Flexbox
- CSS Grid
- clamp() pour les tailles de texte fluides
- Responsive design avec media queries
- Design mobile-first
- Git et GitHub pour la gestion de version et la mise en ligne

### Ce que j’ai appris

- J’ai compris comment structurer une section **hero**,  de manière claire et responsive.
- J’ai appris à Appliquer des tailles de texte adaptatives avec `clamp()` pour que les textes restent lisibles peu importe l’écran.
- J’ai amélioré ma logique CSS pour gérer la disposition en **desktop**, **tablette** et **mobile** sans dupliquer les styles.
- J’ai pratiqué l’alignement des contenus et images côte à côte, ainsi que la gestion des espacements.
- Bien utiliser GitHub pour la publication
#### Exemple de code :

```css
.btn--solid {
  display: flex;
  align-items: center;
  justify-content: center;
  padding: 0.75em 2em;     /* Padding proportionnel */
  font-size: clamp(0.85rem, 2vw, 1rem);   /* Même taille que .hero__content p */
  width: fit-content;     /* Largeur selon le texte */
  border-radius: var(--corner-radius-6, 6px);
  background: var(--colors-neutral-900, #172339);
  color: var(--clr-white);
  margin-top: 1.5rem;     /* Espace sous le texte */
}

