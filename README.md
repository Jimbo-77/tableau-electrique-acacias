# tableau-electrique-acacias
représentation des tableaux électriques de la rénovation

## Contenu

- `index.html` : page web interactive autonome (HTML, CSS et JavaScript dans un seul fichier, sans dépendance). Un clic sur un module du tableau affiche sa fiche : calibre, référence Legrand, section, différentiel amont, usage, points desservis et remarques.

Pour l'instant, la page est un exemple à 3 appareils (ID3, E3, P3).

## Ajouter un module

Les modules sont décrits dans la liste `MODULES`, au début du script de `index.html`. Chaque entrée correspond à un appareil, dans l'ordre sur le rail. La largeur se règle avec `modules` (1 module = 17,5 mm).

## Voir la page

Ouvrir `index.html` dans un navigateur, ou activer GitHub Pages sur la branche `main`.
