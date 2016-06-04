---
layout: post-light-feature
title: Dites *hello* à kardio
description: "Prélude aux billets techniques concernant django, j'explique ce qui m'a motivé à opter pour django."
categories: articles
date: 2016-06-03
image: 
        feature: soft-trees.jpg
---
# Dites *hello* à kardio

Par la grâce du Bon Dieu je suis fier d'annoncer la sortie de ma première version de [kardio](https://bitbucket.org/kaddourkardio/kardio) et sa disponibilité en téléchargement libre et sous licence `GPL2`.
Je remercie les personnes qui m'ont soutenus toute cette période, presque 5 mois depuis mon premier *commit*.

[django](https://www.djangoproject.com) est vraiment génial, il offre une cohérence et une puissance impressionnantes, et apprendre en même temps python et django a été un réel plaisir.

## TODO

### Déploiment en production:

Le directeur a encore une fois tenu sa parole en nous offrant un joli pc all-in-one de chez *lenovo*, le modèle s20-00 il me semble.
il tourne avec un processeur atom z34xx (j'ai oublié les réferences) et offre des pérformances plus que correctes.
Je voulais garder le win8.1 pré installé en dual boot avec [kubuntu 16.04](https://kubuntu.org) mais secure boot m'avait posé quelques soucis.
J'ai donc fini par mettre une kubuntu lts, choix logique car l'absence d'accès à une connexion internet m'imposait d'installer une distro "prête à l'emploi" ou *out of the box* comme le diraient certains.

L'équipe semble apprécier la nouveauté et d'autres centres de cardiologies veulent une installation chez eux.

Pour l'instant je travaille uniquement en mono poste, et pas régulièrement, sur le serveur de test intégré à django. Je sais que ce n'est pas une bonne idée, mais le manque de temps fait que je traine à mettre nginx et gunicorn en marche pour un *vrai* serveur de prod'.

### installation à alger

Je vais passer ce mois ci chez mes collègues à Mustapha, je serai heureux de retrouver des gens de qualité et partager mon experience avec eux.
Le professeur Benkhedda a aimé ma démonstration et va certtainement beaucoup m'aider à déployer chez lui.
Techniquement, je pense devoir cloner mon DD du bureau avec **clonezilla** pour aller le plus vite possible.

## Du coté de la néphro

Moi et Amir avons décidé de mettre en place une app pour tenir le registre national des **greffes renales**.
Lui est un *officionados* du `php` veut se lancer dans l'aventure django. Il faut dire qu'en à peine 48h on a déjà mis en place la partie backend (model + admin) et j'en suis vraiment content.
Je me sens plus à l'aise avec cet outil et je pense même à enrichir mes models avec des `querysets` pour les rendre plus DRY.
Bosser avec amir est très stimulant intellectuellement et me pousse à donner le meilleur de moi-même.

## Epilogue

Donc aprés un "silence " de plusieurs mois je compte revenir à un rythme plus regulier de blogging, et c'est comme par hasard que ça tombe le jour de mon  anniversaire!
Je vais enrichir ce blog avec des billets plus techniques, et pourquoi pas des billets médicaux (oops).
