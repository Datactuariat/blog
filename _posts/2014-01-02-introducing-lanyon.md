---
layout: post
title: DÉTECTER LA FRAUDE PAR L’ANALYSE DES RÉSEAUX SOCIAUX
---

### Une approche innovante mais balbutiante

En 2014, deux tiers des assureurs avaient améliorés leur dispositif de détection de fraude, avec une hausse moyenne de 3 % du nombre de cas identifiés. Cette performance modeste illustre la complexité de détecter les cas frauduleux. L’assureur ne dispose en effet que de données limitées qui ne concernent ni le comportement, ni le mode de vie de ses assurés. Ces informations, particulièrement pertinentes pour identifier la fraude, n’ont pourtant jamais été aussi disponibles, collectées et exploitables via les réseaux sociaux.

L’analyse des réseaux sociaux<sup>1</sup>  pour combattre la fraude est abondamment citée comme cas d’usage dans la littérature relative au Big Data. L’exploitation actuelle de ces réseaux se limite cependant à une analyse manuelle et a posteriori des profils suspects. La transition vers une exploitation industrielle constitue un enjeu majeur des futurs dispositifs de lutte contre la fraude.

Si les GAFA (Google, Amazon, Facebook, Apple) connaissent suffisamment leurs utilisateurs pour en prédire le comportement, qu’en est-il des assureurs ? Quelles données apparaissent pertinentes pour détecter la fraude ? Quelles informations sont réellement disponibles sur les réseaux sociaux ?

### Facebook comme source de données ?

Dès lors que l’on s’intéresse aux données personnelles, Facebook s’impose comme une source d’informations incontournable. Les données publiques de ses utilisateurs sont d’ailleurs déjà utilisées par les assureurs d’autres pays pour prouver certains cas de fraude : 

> « Elle publie une photo de profil avec sa bague prétendument volée » 

> « Déclaré non-fumeur, il fume sur ses photos Facebook »  

> « Il est filmé en train de mettre en scène l’accident de sa Ferrari »  

Au-delà de l’analyse de contenu publié par un assuré, les données concernant le réseau d’amis peuvent s’avérer précieuses dans la fraude en RC AUTO. En effet, l’analyse des liens entre les individus impliqués dans un accident permet de savoir si ces derniers se connaissent. Un degré de proximité élevé implique un fort risque de fraude à la déclaration, les assurés s’étant potentiellement mis d’accord pour modifier le contexte ou les conséquences de l’accident.

### Les données de Facebook appartiennent à Facebook

L’accès aux données et aux services de Facebook se fait au travers d’une API<sup>2</sup> . Un développeur peut utiliser l’API de Facebook pour requêter des données publiques (évènements, participants, pages de fans, etc..) ou des données personnelles. La collecte de données personnelles nécessite cependant une connexion avec l’utilisateur, ce qui suppose la création d’une application, d’un site web ou d’un système d’inscription lié à Facebook. 

Le numéro deux de l’assurance auto aux Etats-Unis (GEICO) impose ainsi l’inscription à son site via Facebook, ce qui lui permet de collecter des données sur l’ensemble de ses clients. Cette approche suppose néanmoins une totale dépendance vis à vis de Facebook qui est le seul à décider des modalités d’usages et des données disponibles via son API. Des dizaines de startups en ont fait l’amère expérience l’année dernière lorsque Facebook a décidé de ne plus rendre disponible la liste d’amis des comptes publics. Les nouvelles règles de l’API ne permettent plus de récupérer l’ensemble des amis d’un assuré, mais seulement ceux utilisant également l’application.

<p align="center">
  <img src="http://darky-ben.fr/siafraudill.jpg" alt="Données collectables ou non sur Facebook en 2016"/>
  <span align="right"><i>Données collectables ou non sur Facebook en 2016</i></span>
</p>


### Les données de Facebook, terreau fertile pour la diktyologie<sup>3</sup>.

Les données Facebook sur les utilisateurs présentent une réelle pertinence dans le cadre de la lutte contre la fraude. L’analyse automatique du contenu publié par un client (en arrêt maladie mais postant des photos de vacances à la plage) reste à ce jour au stade expérimental et requiert l’utilisation d’outils d’analyse spécifiques (text mining / analyse d’image). Mais d’autres données comme le réseau d’amis peuvent d’ores et déjà faire l’objet d’une exploitation industrielle.

L’accès à ces données présente un réel coût d’entrée sans garantie sur la pérennité des solutions développées. En dernier recours, une collecte des informations par web scraping permettrait de s’affranchir des contraintes de l’API au prix d’une technicité accrue.

Le principal obstacle à l’exploitation des réseaux sociaux pourrait in fine ne pas être technique mais juridique. Une collecte massive d’informations personnelles viendrait en effet contredire quelques principes clés de la CNIL<sup>4</sup>  :

* Une collecte loyale qui présuppose un consentement préalable des personnes concernées ;
* Une collecte transparente qui présuppose que le collecteur d’informations dévoile son identité et ses intentions ;
* Une collecte respectueuse du droit des personnes qui impose de pouvoir accéder, contester ou rectifier les données collectées.

Malgré un potentiel certain, l’exploitation des réseaux sociaux au sein des modèles de détection de fraude ne pourra être envisagée tant que cette hypothèque juridique n’aura pas été levée.

___

<sup>1</sup> SNA pour Social Network Analysis  
<sup>2</sup> Application Programming Interface  
<sup>3</sup> Etude et théorie des réseaux  
<sup>4</sup> Commission nationale de l’informatique et des libertés  
