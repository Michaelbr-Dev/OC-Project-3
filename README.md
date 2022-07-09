# OCR-Projet-3

Dynamisez une page web avec des animations CSS (ohmyfood!)

## Author

- Michael Briquet

## Technologies

- [![Made-with-HTML](https://img.shields.io/badge/Made%20with-HTML-e34c26)](https://developer.mozilla.org/fr/docs/Web/HTML)
- [![Made-with-SASS](https://img.shields.io/badge/Made%20with-SASS-c6538c)](https://sass-lang.com/guide)
- [![wakatime](https://wakatime.com/badge/user/c061a4e1-542b-4c9a-9bf0-6d10ba96fece/project/6ff68130-8049-496b-9cc7-5db241f0bd96.svg)](https://wakatime.com/badge/user/c061a4e1-542b-4c9a-9bf0-6d10ba96fece/project/6ff68130-8049-496b-9cc7-5db241f0bd96)

## Maquette

<p align="center">
<img src="https://raw.githubusercontent.com/Michaelbr-Dev/OCR-Projet-3/main/public/images/github/maquette-gh.png">
</p>

## Éléments fournis par l'entreprise virtuelle.

- La maquette pour les résolutions téléphone nous est donné.
- Toutes les images présentes sur le site sont aussi livrés en format xl.
- Les icones proviennent de [Font Awesome](https://fontawesome.com/)
- Les couleurs sont : violet #9356DC - rose clair #FF79DA - vert pâle #99E2D0
- Les polices sont ["Shrikhand"](https://fonts.google.com/specimen/Shrikhand) et ["Roboto"](https://fonts.google.com/specimen/Roboto)

## Cahier des charges

### Technologies

- Le développement devra se faire en CSS, sans JavaScript.
- Aucun framework ne devra être utilisé, en revanche l’utilisation de SASS serait un plus.
- Aucun code CSS ne devra être appliqué via un attribut style dans une balise HTML.
- Tout le code doit être versionné sur GitHub et le site devra être accessible sur
  Github Pages une fois terminé.

### Compatibilité

La cible étant les personnes connectées et pressées, le site sera développé en utilisant
l’approche mobile-first. Pour cette raison, seules des maquettes mobiles seront réalisées.

Sur tablette et desktop, le site devra s’adapter, mais ces supports n’étant pas prioritaires,
leur mise en page est libre.

- L’ensemble du site devra être responsive sur mobile, tablette et desktop.
- Les pages devront passer la validation W3C en HTML et CSS sans erreur.
- Le site doit être parfaitement compatible avec les dernières versions desktop de
  Chrome et Firefox.
- [Le code devra utiliser les balises sémantiques et ne doit contenir aucune erreur ni alerte au validateur W3C HTML et CSS.](https://validator.w3.org/nu/?doc=https://michaelbr-dev.github.io/OCR-Projet-3/)

### Contenu des pages

Page d’accueil (x1)

- Affichage de la localisation des restaurants. À terme il sera possible de choisir sa
  localisation pour trouver des restaurants proches d’un certain lieu.
- Une courte présentation de l’entreprise.
- Une section contenant les 4 menus sous forme cartes. Au clic sur la carte,
  l’utilisateur est redirigé vers la page du menu.

Pages de menu (x4)

- 4 pages contenant chacune le menu d’un restaurant.
  Footer
- Le footer est identique sur toutes les pages.
- Au clic sur “Contact”, un renvoi vers une adresse mail est effectué.
  Header
- Le header est présent sur toutes les pages.
- Sur la page d’accueil, il contient le logo du site.
- Sur les pages de menu, il contient en plus un bouton de retour vers la page d’accueil

### Effets graphiques et animations

Les effets accessibles au clic ou au survol sont visibles sur la maquette. Ils devront utiliser
les animations ou transitions CSS, pas de JavaScript ni de librairie.

Boutons

- Au survol, la couleur de fond des boutons principaux devra légèrement s’éclaircir.
  L’ombre portée devra également être plus visible.
- À terme, les visiteurs pourront sauvegarder leurs menus préférés. Pour ça, un
  bouton "J’aime" en forme de cœur est présent sur la maquette. Au clic, il devra se
  remplir progressivement. Pour cette première version, l’effet peut être apparaître au
  survol sur desktop au lieu du clic.

Page d’accueil

- Quand l’application aura plus de menus, un “loading spinner” sera nécessaire. Sur
  cette maquette, nous souhaitons en avoir un aperçu. Il devra apparaître pendant 1 à
  3 secondes quand on arrive sur la page d'accueil, couvrir l'intégralité de l'écran, et
  utiliser les animations CSS (pas de librairie). Le design de ce loader n’est pas défini,
  toute proposition est donc la bienvenue tant qu’elle est cohérente avec la charte
  graphique du site.

Pages de menu

- À l’arrivée sur la page, les plats devront apparaître progressivement avec un léger
  décalage dans le temps. Ils pourront soit apparaître un par un, soit par groupe
  “Entrée”, “Plat” et “Dessert”. Un exemple de l’effet attendu est fourni.
- Le visiteur peut ajouter les plats qu'il souhaite à sa commande en cliquant dessus.
  Cela fait apparaître une petite coche à droite du plat. Cette coche devra coulisser de
  la droite vers la gauche. Pour cette première version, l’effet peut apparaître au survol
  sur desktop au lieu du clic. Si l’intitulé du plat est trop long, il devra être rogné avec
  des points de suspension. Un exemple de l’effet attendu est fourni.

## Notes sur la réalisation du projet

- L'integration est faite sur l'éditeur Visual Studio Code avec les plugins [Live server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer), Le thème, l'UI et les raccourcis clavier sont personnalisés.

## Visualiser le site

- [Projet 3 - ohmyfood!](https://michaelbr-dev.github.io/OCR-Projet-3/)
