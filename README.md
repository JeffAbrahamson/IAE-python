# Python

Ce cours comporte trois séances de deux heures chacune.  L'objectif du
cours est de présenter une introduction à python ciblé aux étudiants
en économie et statistiques.  Nous allons prendre comme hypothèse au
moins les suppositions suivante :

* Vous savez programmer.  Python n'est pas la première langue de
  programmation que vous voyez ou avec laquelle vous travaillez.
* Vous vous intéressez aux statistiques et l'étude de l'économie.  En
  outre, vous connaissez probablement mieux ces deux sujets que le
  prof.  Aussi, nos exemples sortiront de ses domaines, mais
  l'objectif reste comment utiliser python pour traiter les exemples
  et, plus tard, les vraies tâches informatiques dans vos vies.
* Vous êtes suffisamment compétent en anglais pour lire des textes
  simples (surtout, tutoriels) en anglais.

# Outils et support

Il est bien évidemment impératif que vous puissiez écrire et essayer
des programs en python.  Avant la première séance, il convient donc de
télécharger et installer python sur votre ordinateur.  La bonne
nouvelle, c'est que c'est gratuit et (selon votre système
d'exploitation) relativement simple.

## Linux

C'est un de rare cas dans la vie où tout est plus facile sur linux.
Afin, pour une certain définition de "facile".  Il suffit d'installer
python3 (attention : souvent python = python2) et virtualenv.
Virtualenv vous crée un environnement pour python largement
indépendant de ce qui est présent sur votre ordinateur.

Sur ubuntu, on peut taper

    $ sudo apt-get update
	$ sudo apt-get install python3-virtualenv virtualenv python python3
	$ sudo apt-get install gcc g++ python3-dev

Puis, dans votre répertoire de travail :

    $ virtualenv --python=python3 venv
	$ . venv/bin/activate                   # N'oubliez pas le "." au début.
	$ pip install -r requirements.txt

Le fichier `requirements.txt` se trouve [ici](requirements.txt).

Cela marche également sur MacOS si vous êtes à l'aise dans le terminal.

## MacOS, Windows

Apparemment l'usage de python sur Windows marche très bien sauf quand
ce n'est pas le cas.  Les systèmes MacOS et linux sont beaucoup plus
répandus dans le domaine de stat/ML/data science.  Ceci dit, un
produit commercial avec une très bonne offre gratuit existe :
[anaconda](https://www.anaconda.com/).  Il est téléchargeable
[ici](https://www.anaconda.com/download/#linux).

