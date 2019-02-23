# Formations

L'intégration des membres n'est pas un point fort chez Cedille...

Ce repo tente donc de corriger ce problème en regroupant les informations pertinentes sur divers projets/sujets en lien avec le club.
Avoir ces présentations permettront d'introduire les membres à ces projets de manière (un peu plus) structurée.

Attention, les documents retrouvés ici ne sont pas très complets; ce sont plutôt des aides-visuels utilisés lors des ateliers.

### Quelques lignes directrices

- Rester claire et concis. Les diapositives ne devraient pas contenir d'explication détaillée, mais plutôt les idées.
- Garder en tête un public cible qui ne s'y connait pas encore. Cela permet d'intégrer les membres, peu importe leurs _background_.
- Faire attention à l'orthographe.

### Utilisation

Les présentations sont générées au format PDF avec les outils `pandoc` et `beamer`. Pour générer le fichier PDF, il faut
installer `pandoc` et `markdown`.

Par la suite, on peut utiliser cette commande pour construire la présentation:

```
pandoc servers.md -t beamer -o servers.pdf
```

#### Pour les membres: N'hésiter pas à faire un pull-request pour tout ce qui est :

- Ajout d'informations
- Correction de fautes
- Ajout de formations

