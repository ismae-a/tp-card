# Travaux Pratiques : intégrer une "Card" en HTML / CSS

- Cloner ce repo,
- Puis comme dirait *R.* : "next, next, next",
- Votre livrable sera l'URL de votre repo sur Github ou Gitlab

## Consignes globales

- Vous êtes censé réaliser ce TP **sans aide extérieure**, mais ce n'est pas grave si vous le faites&#8239;: dans ce cas, laissez un commentaire indiquant où (et pourquoi) vous avez cherché de l'aide.
- Il est **inutile de reproduire à la perfection** les couleurs exactes, les arrondis ou autre détail décoratif&hellip; mais si ça vous intéresse&nbsp;:
  - la valeur de l'arrondi est de `16px`,
  - la valeur de gouttière est de `12px` sur petit écran et `24px` sur grand écran,
  - et la couleur de fond de la card est `aliceblue`.
- Merci de **noter le temps** que vous avez passé pour réaliser votre TP.

Deux versions de ce TP sont possibles :

- Version 1 : HTML et CSS "vanilla"
- Version 2 : Tailwind (si vous êtes chaud)

Les consignes spécifiques pour chaque version sont disponibles sous l'image d'illustration&hellip;

![Consignes pour la card](tp/consignes.png "Consignes pour la card]").

## Version 1 : HTML / CSS vanilla

Reproduire la Card telle que présentée dans l'image `consignes.png`, en HTML et CSS :

1. Opter pour une structure HTML adaptée dans le fichier `index.html`.
2. Appliquer les styles CSS sous le commentaire `/* Ma solution */` dans le fichier `styles.css`.

**Note :** Les assets (images) sont dans le dossier `/images`.

**Note :** Merci de vous renseigner pour comprendre l'intérêt de `@layer` présent dans le fichier `styles.css`.

## Version 2 : Tailwind

Reproduire la Card telle que présentée dans l'image `consignes.png`, à l'aide de Tailwind.

Se servir de l'outil en ligne <https://play.tailwindcss.com/> *(juste parce que ça va plus vite que d'installer plein d'outillage)* et **placer la partie `@layer reset {...}` dans l'onglet `CSS` de Tailwind Play** pour appliquer les styles sur `body`.

URL des assets *(uniquement nécessaires si vous passez par Tailwind Play)* :

- icone "homme" : <https://assets.codepen.io/9425/020-man-1.svg>
- icone "femme" : <https://assets.codepen.io/9425/022-woman-1.svg>
- icone "licorne" : <https://assets.codepen.io/9425/002-unicorn.svg>
- icone "filters" : <https://assets.codepen.io/9425/icon-filters.svg>
- icone "edit" : <https://assets.codepen.io/9425/icon-edit.svg>
- icone "charts" : <https://assets.codepen.io/9425/icon-charts.svg>
