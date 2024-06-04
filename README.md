# Projet en informatique pour les sciences humaines

Ce projet reprend le travail de threading des widgets du add-on [Textable](http://textable.io/) du logiciel [Orange](https://orangedatamining.com/) effectué par Antonin Schnyder en proposant de remonter l'architecture de threading d'un étage dans la hiérarchie de classes de Textable. 

Ce repository contient les widgets et scripts développés dans le cadre du projet ainsi qu'un rapport détaillé des modifications apportées à Textable.

## Installation

Pour tester ces versions des widgets, il vous faut : 

- [Installer](https://orangedatamining.com/download/) Orange sur votre machine
- Accéder au dossier `site-packages` de Orange (sur MacOS : /Orange3.app/Contents/Frameworks/Python.framework/Versions/3.9/lib/python3.9/site-packages/)
- Copier le contenu du dossier `LTTL` dans `/site-packages/LTTL`
- Copier les fichiers du dossier `widgets_Johan_Cuda` dans `/site-packages/_textable/widgets`
- Lancer Orange et tester les widgets !

## Architecture du repo

- `LTTL` : Contient les fichiers LTTL modifiés par Antonin Schnyder

- `rapport` : Contient les fichiers du rapport ainsi qu'une version PDF

- `widgets_Johan_Cuda` : Contient les versions des widgets et de `TextableUtils.py` développés dans le cadre de ce projet


## Crédits

Projet réalisé par Johan Cuda (johan.cuda@unil.ch) sous la supervision de Aris Xantos (aris.xantos@unil.ch) dans le cadre du "Projet en informatique pour les sciences humaines" à l'Université de Lausanne, Section des sciences du langage et de l'information.

