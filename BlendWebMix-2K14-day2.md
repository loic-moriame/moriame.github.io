---
title: Blend Web Mix 2014 : retour sur la journée #2
---

<link href="http://maxcdn.bootstrapcdn.com/bootstrap/3.2.0/css/bootstrap.min.css" rel="stylesheet">
<link href="css/style.css" rel="stylesheet">

# Blend Web Mix 2014 : retour sur le jour 2

Après [mes retours à chaud sur la première journée de Blend Web Mix 2014](BlendWebMix-2K14-day1),
voici mes impressions sur la 2ème journée !


## Organisation *(attention, je râle encore)*

Donc le premier jour, le buffet "petit déjeuner" était introuvable. <br />
Et bien en ce second jour de Blend, le buffet a parfaitement été trouvé par l'ensemble des participants. <br />
Tant et si bien qu'en arrivant 5min en retard par rapport à l'horaire d'ouverture des portes, j'ai difficilement pu sauver une mini viennoiseries.

Je crois que les organisateurs ont sous évalués l'importance du petit déjeuner sur les deux jours. <br />
Dommage *(on se rattrapera au buffet du midi, promis)*.


## Les conférences
Cette deuxième journée s'annonce à nouveau riche au niveau des conférences que j'avais l'intention de suivre. <br />

### La révolution Google Glass
par Alain Regnier ([@altolabs](https://twitter.com/altolabs))

Une conférence "pour passer le temps", car rien ne m'intéressais vraiment avan 10h30 ce jour la. <br />
*(peut-être aurais-je du aller assister à la conférence concernant la dette technique ?)*

1h de présentation des Google Glass, de ce que c'est, ce que ce n'est pas; ce qu'on peut faire et ne pas faire avec. <br />
Je n'ai pas vraiment appris grand chose d'autre que ce qui est déjà publiquement communiqué sur le web. <br />
C'était plus l'occasion de voir des Google Glass en vrai, ainsi que des exemples d'utilisations.

Le présentateur semblait vraiment convaincu de l'avancée technique et des avantages des lunettes connectées. <br />
Personnellement je reste encore circonspect sur le sujet. <br />
C'est plus mon côté geek (assumé) qui me donnerait envie.


### 12 factor app, bonnes pratiques pour développer des applications puissantes et scalables
par Damien Mathieu ([dmathieu](https://twitter.com/dmathieu))

Bien qu'une salle ait été agrandi, il reste toujours des salles ne permettant pas d'accueillir l'ensemble des participants. <br />
Je me suis donc fait refouler à l'entrée de cette conférence que j'aurais bien aimé suivre.<br />
Next !


### Un jeu Web accessible avec HTML 5, JavaScript et ARIA
par Victor Brito ([@victorbritopro](https://twitter.com/victorbritopro)) et Sylvie Duchateau ([@sylduch](https://twitter.com/sylduch))

Conférence "roue de secour" suite aux lacunes de capacité d'accueil des salles de conférences. <br />

Victor et Sylvie commencent par nous expliquer les grands principes de l'accessibilité.<br />
Je retiendrais que l'utilisation des bonnes pratiques [ARIA](https://developer.mozilla.org/fr/docs/Accessibilit%C3%A9/ARIA) permet de faire des réalisations web accessible aux personnes souffrant de déficiences visuelles.<br />
D'ailleurs tout au long de la présention, Sylvie utilisera son clavier braille et un lecteur d'écran.

L'occasion pour ma part de voir "en vrai" l'utilisation d'un clavier braille ainsi qu'un lecteur d'écran.<br />
J'apprends par la même occasion qu'un clavier braille est limité à 40 charactères maximum à la fois. <br />
A anticiper dans les réalisations web. <br />

S'ensuite une démonstation d'un jeu développé pour l'occasion de cette conférence : un jeu de bingo avec mise de départ, sélection du nombre de grille etc.
Grâce au développement des bonnes pratiques [ARIA](https://developer.mozilla.org/fr/docs/Accessibilit%C3%A9/ARIA), je retiendrais une citation :
> Javascript est accessible si vous ne faites pas n'importe quoi avec

A savoir que si vous faites des manipulation DOM via Javascript, il suffit d'employer les bons attributs ARIA pour que les outils à disposition des personnes souffrants de déficiances visuelles (clavier braille, lecteur d'écran etc.) les prennent en compte.

Conférence intéressante, même si la partie démonstration aurait pu être plus courte pour permettre des questions / réponses à la fin de la présentation.

Lien vers la présentation : [http://www.victor-brito.fr/publications/un-jeu-web-accessible-avec-html-5-javascript-et-aria-blend-web-mix-30-10-2014.pdf](http://www.victor-brito.fr/publications/un-jeu-web-accessible-avec-html-5-javascript-et-aria-blend-web-mix-30-10-2014.pdf)



### API fait de la résistance
par Maxime Prades ([@prades_maxime](https://twitter.com/prades_maxime))

Retour d'expérience sur l'utilisation des API chez [zendesk](https://www.zendesk.fr)

Présentation intéressante avec une réelle expérience de la refonte technique par la mise en place d'API pour piloter les produits.<br />

Ce que je retiendrais :

* les API c'est cool, mangez en
* si on commence une nouvelle API : du REST et puis c'est tout (SOAP c'était ~~bien~~ avant !)
* soyez consommateur de vos propres API : rien de tel pour les éprouver et valider leur architecture
* prévoyez des limitations d'utilisations, sous peine d'avoir des utilisateurs "sans scrupules" (ex. max 1000 req/heure)
* pour l'identification, préférez OAuth à tout autre système



### Fluidifiez votre industrialisation Web avec Yeoman & Gulp
par Mathieu Lux ([@Swiip](https://twitter.com/Swiip))

Cette conférence était l'occasion pour son auteur de nous présenter l'utlisation de Yeoman et de Gulp pour facilitez la mise en route de nouvaux projets.

Yeoman pour toute la partie scaffolding (création du squelette de l'application).<br />
Gulp pour tout ce qui concerne la gstion des tâches (remplace Grunt qui est l'outil habituellement utilisé avec Yeoman).

Gulp est comme Grunt, un gestionnaire de tâches.<br />
Mais en mieux.

Pourquoi ?<br />
Car il repose sur les streams Node.js, donc est bien plus rapide dans tout ce qui est manipulation de fichiers (pas de I/O disque incessants pour chaque transformation).<br />
Et l'utilisation des streams permet en même temps de se passer de la verbosité de Grunt pour écrire ses différentes tâches.

Cette présentation a été l'occasion de présenter quelques plug-ins Gulp qui semblent vraiment intéressant à regarder :

* gulp-useref
* gulp-rev, gulp-rev-replace
* etc.

Etant amoureux du couple Yeoman & Gulp, Matthieu a développé un générateur Yeoman basé sur Gulp.<br />
La fin de la présentation sera donc l'occasion de présenter le projet.

Lien vers la présentation : [http://swiip.github.io/yeoman-gulp](http://swiip.github.io/yeoman-gulp)


### AngularJS 2.0: le futur du développement web
par Olivier Combe ([@OCombe](https://twitter.com/OCombe))

Gros condensé d'information au cours de cette conférence.<br />
Et surtout l'occasion d'avoir un retour sur la conférence ngEurope qui avait eu lieu quelques jours plus tôt.

Pendant 1h de présentation, Olivier nous fait donc un retour sur le futur d'Angular : 

* les lacunes de angular 1.x
* les réflexions des développeurs
* la genèse de angular 2.x

Et ne nous voilons pas la face : les changements sont pour le moins radicaux !<br />
Pour faire une analogie grossière, c'est un peu comme le passage entre Symfony 1.x et Symfony 2 : il faudra réapprendre.

Mais les développeurs de chez Google étant malin, ils vont utiliser le futur de Javascript pour bâtir Angular 2.0.<br />
A savoir utiliser le plus possible les nouveaux standars ECMAScript 6

Lien vers la présentation : [http://slides.com/ocombe/ng2](http://slides.com/ocombe/ng2)


### Git ProTips : faire du Git plus vite et mieux grâce à cette sélection d’astuces
par Christophe Porteneuve ([@porteneuve](https://twitter.com/porteneuve))

La seule conférence pleinière à laquelle j'aurais l'occasion d'assister sur les deux jours de Blend (les autres pleinières ne m'intéressant que très peu, voir pas du tout la plus part du temps).

Pendant 1h, Christophe nous fournis le plein de bons conseils et démistifie des commandes parfois mal connues.

Ce que je retiendrais comme conseils de cette conférence :

* 1 commit = 1 périmètre réduit, d’un coup, ni plus, ni moins.
* on commit souvent, on push rarement
* avant de push, on fait le ménage en local pour pas pourir origin/master
* dès qu'un développement prend plus de 10 secondes : on créer une branche !
* un log bien configuré = lisibilité assurée
* on peu chercher dans les log le nom d'une fonction (ex. : git lg -L :getCheckIns:app/lib/persistence.js)

Malheureusement, la présentation étant très dense, nous n'aurons pas eu l'occasion de voir "rerere" en action.<br />
Mais qu'à cela ne tienne, depuis Christophe a publié [un article sur le sujet](http://www.git-attitude.fr/2014/11/04/git-rerere/)

Lien vers la présentation : [http://delicious-insights.com/talks/blend2014-git-protips](http://delicious-insights.com/talks/blend2014-git-protips) <br />
La vidéo de la conférence : [http://youtu.be/ypR-rEBCoag](http://youtu.be/ypR-rEBCoag)

### Architecture REST : On ne va pas se mentir.
par William Durand ([@couac](https://twitter.com/couac))

Fin de Blend par une bonne grosse conférencec technique à propos des architectures RESTfull.<br />
Un bon complément à la conférence sur les API par nos amis de chez zendesk un peu plus tôt dans la journée.

Cette conférence aura été pour moi l'occasion de découvrir le modèle de maturité de Richardson (Richardson Maturity Model). <br />

C'est un modèle qui décompose l’approche REST en trois étapes qui introduisent progressivement les principaux éléments de REST (Ressources ; Verbes et Codes retours HTTP ; Contrôles hypermédia) pour passer d’un modèle RPC sur HTTP à un modèle RESTFul.

Le level 3 de ce modèle est le contrôle hypermedia : vos endpoint doivent se suffir à eux-même pour découvrir l'ensemble de votre API.<br />
En effet, chaque endpoint (en commencant par le plus bas : "/") répond de telle façon qu'il décrit les liens qu'il a vers chaque sous-partie (endpoint) des objets qu'il représente.

Pas très claire ? <br />
La présentation est en lien un peu plus bas ;)

Une fois les bases de ces grands principes expliqués, William nous présente comment les mettre en place au sein d'un projet basé sur Symfony 2. <br />
*(il tien donc sa promesse qui était "peu de php, beaucoup de REST") ;)*

Lien vers la présentation : [https://speakerdeck.com/willdurand/architecture-rest-on-ne-va-pas-se-mentir-blendwebmix](https://speakerdeck.com/willdurand/architecture-rest-on-ne-va-pas-se-mentir-blendwebmix)

<div class="alert alert-warning" role="alert">
  <strong>Pull-Request !</strong> Une erreur de typo ? Grammar Nazi ?
  N'hésite pas à faire <a href="https://github.com/moriame/moriame.github.io/pulls">une PR !</a>
</div>
