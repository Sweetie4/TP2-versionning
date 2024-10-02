# Tuto README

## Qu'est-ce qu'un README ?

Un README, qui peut se traduire littéralement par 'lisez-moi', est un fichier de documentation permettant de communiquer les infomrations importantes d'un dossier. Souvent mis en avant par les dépôts distants, ils permettent aux personnes qui découvrent le projet de savoir : 
 - Ce qu'il fait, 
 - En quoi le projet est utile, 
 - Comment le prendre en main,
 - Où les utilisateurs peuvent obtenir de l’aide
 - Qui maintient et contribue au projet 

## Quel est la syntaxe d'un README ?
Il peut être un simple fichier texte (.txt), mais aujourd'hui c'est souvent un fichier markdown (.md).
Le markdown est un langage de balisage qui permet de simplement ajouter un lien derrière un texte ou de varier la taille de la police pour les titres. Sur la plupart des outils de dépots distant, ces fichiers markdown sont interprétés de manière à avoir une table des matières automatiques par exemple.

Voici des exemples de syntaxe que l'on peut retrouver dans un fichier README.md : 

* Le titre : Permet de hiérarchiser et d'organiser le README. Il y a deux manières de le signaler : soit on utilise des #, avec le nombre de # augmentant quand on baisse dans la priorité 
    * # exemple avec 1 #
    * ## exemple avec 2 #
* Le bloc de code : Permet de rendre plus visible le code. C'est souvent utilisé pour afficher les commandes à entrer pour l'installation d'un projet par exemple. On le forme avec trois back tilts (`) encadrant le texte
 ```exemple```
* Les liens : Permettent de mettre des liens hypertexte dans le code. Dans le cas d'un README, on peut l'utiliser pour rediriger vers la documentation d'un module utilisé par exemple. On utilise des [] pour le texte cliquable, et des () pour le lien.
[Exemple qui renvoie vers le dépôt](https://github.com/Sweetie4/TP2-versionning/tree/main)

## Quelle est la structure un README ?

La structure d'un readme peut être variable, mais voici un exemple d'oragnisation : 

# Titre du projet

_Une brève description d'en quoi consiste le projet et en quoi il est utile._

## Installation

_Une liste d'instructions expliquant comment mettre le projet en place_


## Usage

_Comment utiliser le projet_

## Dev kit

_Ensembles des technologies et dépendances du projet avec leur version_

## Contributeurs

_Ensemble des contributeurs du projet_

## Contributions

_Règles de contributions_

## License

_License du projet_