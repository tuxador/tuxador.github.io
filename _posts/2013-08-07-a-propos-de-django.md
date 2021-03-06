---
layout: post-light-feature
title: À propos de django
description: "Prélude aux billets techniques concernant django, j'explique ce qui m'a motivé à opter pour django."
categories: articles
date: 2015-08-09
image: 
        feature: soft-trees.jpg
---

# Pourquoi Django

Je suis en ce moment en plein apprentissage de développement du [framework django](www.djangoproject.com), le framework pour "perfectionnistes pressés".

>Django is a high-level Python Web framework that encourages rapid development and clean, pragmatic design.
Built by experienced developers, it takes care of much of the hassle of Web development, so you can focus on writing your app without needing to reinvent the wheel. 
It’s free and open source.

Aprés un mois de "théorie" notamment  une lecture intensive de documentation [officielle](https://docs.djangoproject.com/fr/1.8/), chez [openclassroom](http://openclassrooms.com/courses/developpez-votre-site-web-avec-le-framework-django/les-formulaires-6) et [chez les filles](https://http://tutorial.djangogirls.org/fr/) m'ont permis de démarrer mes ~~gribouillages~~  experimentations.

## Pourquoi pas un CMS

### Parceque j'ai déjà développé une application avec [Joomla](https://joomla.org), l'an dernier.
À l'époque je n'avais quasiment aucune expérience de *web developpement* , aucun bagage théorique.
Un CMS (j'ai testé wordpress puis joomla) est un fantastique outils pour des gens comme moi, sans connaissances techniques, pour pouvoir bénéficier du travail d'une communauté trés active et déployer rapidement une appli.
J'étais émerveillé par des extensions **WYIWYG**, fonctionnant *out of the box*, et au design alléchant, grâce à [bootstrap](https://getbootstrap.com)
Mon outil magique était l'extension [**Fabrik**](https://www.frabrikar.com):
  - Création rapide de formulaires 
  - autocomplétion des champs, un *must* !
  - Création et (re)nommage de tables MySQL correspondantes, juste magique!
  - l'export en PDF, grâce à l'outil [DOMPDF](https://github.com/dompdf).
  
Ce fut une trés belle experience pour moi, quasiment deux mois de nuits blanches!
Seulement voilà, l'ensemble bien que fonctionnel et assez agréable à utiliser, restait "magique" dans le sens où je ne comprenais pas, *exactement*, comment ça fonctionnait.
Et ce n'était pas juste une question d'auto-satisfaction, plutôt le contraire:
  - Comment débogguer ce ~~merdier~~ truc quand on ne sait même pas les rudiments du PHP, sur lequel l'ensemble est bâti? 
  - Comment personnaliser mes formulaires enregistrés ? la lecture attentive du wiki dompdf m'a donné une piste, l'explication est laconique, ou me parait telle vu mon ignorance du domaine.
  - Comment gérer les mises à jour sans casser l'ensemble? cette mésaventure m'est arrivée à chaque MAJ joomal...
  - et quid de la base de données? MySQL est t-il  le bon choix? des amis du service technique m'ont suggéré que non.
  
Toujours est t-il que je n'étais pas peu fier de mon boulot, et j'ai presenté le travail d'abord aux collègues *toubibs*, leur réaction était ...mitigée.
Puis ce fut au tour du service IT de l'hopital, d'abord de l'enthousiasme,un brin de méfiance (bah oui un toubib ça ne fait pas de *web dev*), ensuite de l'agacement, forcer l'équipe à s'initier au déploiment maiheu!!

+ Tout cela m'a donné goût à la recherche, j'ai fait quelques tuto php, css(bootstrap) et j'avoue ne pas trop aimer la façon de faire à la php, allez savoir pourquoi.
Le fait est que je suis de nature *chaotic good*, développer en php ne m'aide pas vraiment à structurer mes pensées...

### Parceque j'aime bien python: 
Dans ma "quête" numérique, et devant cette frustration du manque de connaissances *profondes* en info, j'ai pris la décision d'apprendre un langage informatique, autre que php s'il vous plaît!
Les deux concurrents sont naturellement [Ruby](www.ruby.org) et (Python)[https://python.org]
J'ai choisi ce dernier pour differentes raisons, notamment 
  - la possibilité d'intégration d'outils scientifiques avec le framework django,
  - la structure *carrée* du code
  - l'esprit DRY (don't repeat yourself) 
  - l'intégration de la BDD (**PostgreSQL**)[https://postgresql.org] reputée plus solide que MySQL, mais hélas non compatible avec l'extension fabrik de joomla.
  

  
