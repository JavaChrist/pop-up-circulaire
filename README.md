# Pop-up Circulaire

Ce projet présente une animation de pop-up circulaire intégrant plusieurs icônes interactives. Chaque icône est animée et placée dans un cercle de blobs. L'utilisateur peut cliquer sur une icône pour effectuer des actions spécifiques.

## Fonctionnalités

- **Animation circulaire** : Les icônes sont disposées de manière circulaire autour d'un bouton central.
- **Icônes interactives** : Chaque blob contient une icône cliquable représentant une action ou un lien. Certaines icônes mènent à des pages externes.
- **Responsivité** : L'animation et la disposition sont adaptées pour les écrans de différentes tailles.

## Fichiers

- **index.html** : Fichier HTML contenant la structure de la page et les éléments de l'animation.
- **style.css** : Fichier CSS pour la mise en forme et les animations des icônes et du bouton.
- **script.js** : Fichier JavaScript gérant l'interaction et les animations des blobs.
- **/assets/icone/** : Dossier contenant les icônes utilisées dans l'animation.

## Détails des éléments

- **`btn-menu`** : Bouton central qui déclenche l'animation des blobs autour de lui.
- **`blob-1` à `blob-8`** : Blobs circulaires contenant des icônes représentant différentes actions. Chaque blob est stylisé et animé avec CSS.
- **Icônes** :
  - `balance.svg`
  - `cloche.svg`
  - `coffee.svg`
  - `credit-card.svg`
  - `football.svg`
  - `headphone.svg`
  - `microphone.svg`
  - **Logo Javachrist** : Lien vers [www.javachrist.fr](https://www.javachrist.fr)

## Installation

1. Clonez le repository :
   ```bash
   git clone https://github.com/votre-utilisateur/pop-up-circulaire.git
Ouvrez le fichier index.html dans un navigateur.
Utilisation
Cliquez sur le bouton central pour faire apparaître ou disparaître les blobs circulaires.
Chaque blob est cliquable et peut exécuter une action spécifique ou rediriger vers une autre page.
Personnalisation
Ajout d'icônes : Pour ajouter de nouvelles icônes, placez vos fichiers SVG dans le dossier /assets/icone/, puis ajoutez un nouveau blob dans le fichier HTML avec la structure suivante :

html
Copier le code
<div class="blob blob-X"><img src="/assets/icone/votre-icone.svg" alt="description" class="icone"></div>
Remplacez X par le numéro suivant dans la séquence.

Style et animation : Modifiez le fichier style.css pour ajuster les styles ou les animations des blobs et des icônes.

Technologies utilisées
HTML5
CSS3
JavaScript : pour la gestion des interactions et des animations.
Auteurs
Créé par Javachrist.

Licence
Ce projet est sous licence MIT.