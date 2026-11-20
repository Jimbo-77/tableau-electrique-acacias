# tableau-electrique-acacias
représentation des tableaux électriques de la rénovation

## Contenu

- `index.html` : page web interactive autonome (HTML, CSS et JavaScript dans un seul fichier, sans dépendance). Un clic sur un module du tableau affiche sa fiche : calibre, référence Legrand, section, différentiel amont, usage, points desservis et remarques.

La page représente le tableau principal (4 rangées + coffret des télérupteurs) et le tableau des combles, avec le disjoncteur de branchement, le répartiteur modulaire (rangée 4) et ses liaisons vers les têtes de groupe, les peignes et les emplacements réservés aux télérupteurs connectés.

## Ajouter un module

1. Décrire l'appareil dans l'objet `E`, au début du script de `index.html` (fonctions `dj()` pour un disjoncteur, `id()` pour un interrupteur différentiel, `tl()` pour un emplacement de télérupteur).
2. Ajouter son repère dans la rangée voulue de `PANELS`, à sa place sur le rail.

Un disjoncteur placé après un interrupteur différentiel est automatiquement relié au peigne de cet ID.

## Voir la page

Ouvrir `index.html` dans un navigateur, ou activer GitHub Pages sur la branche `main`.
