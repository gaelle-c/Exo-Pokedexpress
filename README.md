> Exercice réalisé dans le cadre de la formation DWWM JavaScript au sein de l'école O'Clock en 2020

---

# Pokédex

Apprentis professeurs Chen, j'ai une requête pour vous ! Je souhaiterais un pokédex tout beau, tout neuf !

Un pokédex, est une sorte de dictionnaire de tous les pokémon (petites créatures fictives et adorables). Ces derniers peuvent se battre
et disposent de caractéristiques de combat appelées statistiques. Chaque pokémon possède aussi un ou deux types (plante, roche, feu...).

Vous aurez besoin pour cette mission des outils suivants :
- NodeJS
- PostGreSQL
- HTML et CSS
- npm
- express et ses copains

Une base de données à importer vous est fournie à la racine du projet : `pokedex.sql`. Elle contient la liste des pokémon et leurs types. Vous n'avez pas à la modifier.

## Instructions

Voici la liste des pages à faire, vous avez un aperçu de chacune dans le dossier résultat :

- Une page d'accueil qui liste tous les pokémon de la base (home.png)
- Une page détail d'un pokémon qui affiche son type et ses stats (detail.png)

La police utilisée est Bree Serif sur Google Fonts. Pour les couleurs, utilisez une pipette :wink:. Pour celles des types, elle est fournie dans la base.

## Par où commencer ?

Voilà quelques pistes pour vous aider :

- Commencez par installer express, pg, et toute autre dépendance nécessaire avec npm
- Mettez en place les dossiers nécessaires (#SoC !)
- Vous aurez besoin d'un controller principal (mainController.js)
- Il y a deux routes à créer
- Pour récupérer les types d'un pokémon, il faut utiliser une jointure sur la table `pokemon_type`
- Les images sont déjà prêtes et portent le nom du numéro du pokémon dans le dossier `public/img`
- Pour les barres de statistiques, la valeur maximale est de 255. On peut donc utiliser un produit en croix pour le remplissage :wink:

## Bonus

Je veux ajouter une fonctionnalité : récupérer des pokémons selon leur type.

Il nous faudra donc :

- Une page qui liste les types de la base (types.png) quand on clique sur l'un on arrive sur la page suivante
- Une page qui liste les pokémon filtrés par le type cliqué sur la page précédente (electrik.png)
