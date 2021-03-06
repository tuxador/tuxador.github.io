---
layout: post
title: "Salam World"
description: "Presentation."
category: articles
tags: [blog, latex, python]
image:
  feature: soft-trees.jpg
---

Cet espace sera une sorte d'aide-mémoire pour tous mes éxperimentations plus ou moins _geek_ , mes découvertes ainsi que des projets perso.  
Je m'intéresse actuellement à deux aspects complémentaires liées à mon activité médicale: 
 
1- Créer une application pour la gestion numérique des dossiers médicaux, facilitant le travail collaboratif et permettant la pérsistance des données.
2- Exploiter cette base de données et permettre ainsi de produire des papiers intéressants: rapports d'activité, posters, études prospectives...  

À ce jour j'ai réalisé une application web grâce au framework [Joomla](httpss://www.joomla.org), hélas j'ai énormément de mal à la déployer au service de l'hôpital (tournant sous windows server).
Le problème n'est pas tant technique mais *humain*.
Le workflow initial était: 

+ formulaires web (dossier patient)
+ base de donnée mysql 
+ export CSV 
+ graphiques et tableaux avec [Rstudio](https://github.com/rstudio)
+ présentations et posters avec [**pandoc**](https://github.com/jgm/pandoc) et [reveal.js](https://github.com/hakimel/reveal.js)

Je me suis récemment intéressé au langage **python** , et à ses outils notemment l'excellent framework [django](https://djangoproject.com), que je découvre ~~péniblement~~  doucement, et j'essaie d'intégrer toute une batterie (*either included or not* ;) ) de packages me permettant d'automatiser au maximum les diffrentes tâches:
+ crispy forms pour la génération de formulaires 
+ postgresql comme base de données.
+ django-easy-pdf pour créer des rapports médicaux de qualité professionnelle.
+ les outils scientifiques **numpy** , **scipy** et **matplotlib** en complément/comparaison avec l'excellent Rstudio.

Je détaillerai *inchallah* chaque aspect de cette longue quête numérique.

Au passage je parlerai aussi de mes "outils de travail" : Archlinux, plasma5 et kde5, kate et l'éditeur atom que j'ai testé avec beauoup d'interêt hier.
