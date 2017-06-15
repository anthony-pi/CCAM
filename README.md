# CCAM
Recherche dans la Classification Commune des Actes Médicaux

## Présentation rapide
**RHAPI** est une API RESTful qui s'inscrit totalement dans l'émergence actuelle des applications full Front-End.

**RHAPI** fournit l'ensemble de l'architecture Back-End ainsi que les logiques *Métiers*, pour des applications à destination des professionels de santé dont il ne restera qu'à écrire l'interface utilisateur.

[Zumatec](http://www.zumatec.com) propose ici un exemple utilisant les fonctionnalités CCAM de RHAPI.

Comme la plupart des API RESTful, RHAPI est explorable directement depuis un navigateur ou une application telle que `curl`.

Pour retrouver les mots clefs et les codes des actes associés à un terme médical comme *trijumeau*, on peut ainsi faire de simples requêtes `GET` sur le serveur de démonstration RHAPI :
  - [https://demo.rhapi.net/demo01/CCAM?texte=trijumeau](https://demo.rhapi.net/demo01/CCAM?texte=trijumeau)
  - avec curl : 
