# Projet en informatique pour les sciences humaines

Ce projet reprend le travail de threading des widgets du add-on [Textable](http://textable.io/) du logiciel [Orange](https://orangedatamining.com/) effectué par Antonin Schnyder en proposant de remonter l'architecture de threading d'un étage dans la hiérarchie de classes de Textable. 

Ce repository contient les scripts développés dans le cadre du projet ainsi qu'un rapport détaillé des modifications apportées à Textable.

## Installation

Pour tester ces versions des widgets, il vous faut : 

- accéder au dossier `site-packages` de Orange (sur MacOS : /Orange3.app/Contents/Frameworks/Python.framework/Versions/3.9/lib/python3.9/site-packages/)
- copier le contenu du dossier `LTTL` dans `site-packages/LTTL`
- copier les widgets du dossier `widgets_Johan` dans `site-packages/_textable/widgets`
- Lancer Orange et tester les widgets !

## Architecture du repo

- `LLTL` : Contient les fichiers LTTL threadés par Antonin Schnyder

- `rapport` : Contient les fichiers du rapport

- `widgets_Johan` : Contient les versions des widgets et de `TextableUtils.py` développés dans le cadre de ce projet


## Crédits

Projet réalisé par Johan Cuda (johan.cuda@unil.ch) sous la supervision de Aris Xantos (aris.xantos@unil.ch) dans le cadre du "Projet en informatique pour les sciences huamines" à l'Université de Lausanne, Section des sciences du langage et de l'information.

