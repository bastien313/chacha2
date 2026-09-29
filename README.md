# 🚗☕❤️ Une journée pas comme les autres

Petit dessin animé 2D (≈ 1 min 50) : un homme brun se lève, boit son café, part au boulot dans sa voiture
gris foncé, éternue aux WC… et se bloque le dos. Sa magnifique femme infirmière le soigne, il rentre chez lui
(toujours en voiture gris foncé), répare le lit qui grince, lui fait un bisou — la maison tremble, ses hanches
craquent, et il y a des cœurs partout.

Tout tient dans un seul fichier, `index.html` (HTML + CSS + JavaScript, dessin dans un `<canvas>`,
bruitages générés en direct, aucune dépendance à installer).

## Voir l'animation en local

Ouvre simplement `index.html` dans un navigateur, puis clique sur **Lancer l'animation**
(barre espace = pause, la barre du bas permet d'avancer / reculer et de couper le son).

## Publier avec GitHub Pages

1. Sur GitHub, va dans **Settings → Pages**.
2. Dans **Build and deployment → Source**, choisis **Deploy from a branch**.
3. Choisis la branche qui contient `index.html` et le dossier **/ (root)**, puis **Save**.
4. Après une minute, l'animation est en ligne sur `https://bastien313.github.io/chacha2/`.

## L'ancienne page

La page interactive « Charlène mon amour » (le cœur qui bat + la Roue de l'Amour) est conservée
dans `coeur.html` : `https://bastien313.github.io/chacha2/coeur.html`.

## Personnaliser

Dans `index.html` :
- le déroulé et les durées : tableaux `SCENES` et `CAPTIONS` (temps en secondes) ;
- les sons : objet `SFX` et liste `EVENTS` ;
- les personnages : fonction `person()` (cheveux, tenue) et couleurs `SK`, `HAIR`, `HAIRW` ;
- test rapide d'un instant précis : `index.html?t=51.5` (secondes).
