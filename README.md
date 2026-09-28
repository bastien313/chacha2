# ❤️ Charlène mon amour

Page web interactive : appuie sur le cœur pour le faire battre… jusqu'à ce qu'il explose,
puis fais tourner la Roue de l'Amour pour découvrir ta récompense.

Tout tient dans un seul fichier, `index.html` (HTML + CSS + JavaScript, sons générés en direct,
aucune dépendance à installer).

## Voir la page en local

Ouvre simplement `index.html` dans un navigateur.

## Publier avec GitHub Pages

1. Sur GitHub, va dans **Settings → Pages**.
2. Dans **Build and deployment → Source**, choisis **Deploy from a branch**.
3. Choisis la branche qui contient `index.html` (par ex. `main`) et le dossier **/ (root)**, puis **Save**.
4. Après une minute, la page est en ligne sur `https://bastien313.github.io/chacha2/`.

## Personnaliser

Dans `index.html` :
- le prénom : cherche `Charlène` ;
- les messages du cœur : tableau `MSGS` ;
- les textes illisibles de la roue : tableau `SEGS` ;
- la récompense : fonction `buildRewardText` (et `'TURLUTUTU'` dans `land`).
