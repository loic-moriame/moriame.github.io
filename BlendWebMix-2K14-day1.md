---
title: Blend Web Mix 2014 : retour sur la journée #1
---

<link href="http://maxcdn.bootstrapcdn.com/bootstrap/3.2.0/css/bootstrap.min.css" rel="stylesheet">
<link href="css/style.css" rel="stylesheet">

# Blend Web Mix 2014 : retour sur le jour 1

Cette année encore j'ai la chance de pouvoir participer à la Blend Web Mix à Lyon <br />
Je vais faire un rapide compte-rendu sur les conférences auxquelles j'ai participées.

Pour mes retours sur la 2eme journée, c'est par ici : [Blend Web Mix 2014 : retour sur le jour 2](BlendWebMix-2K14-day2)

## Organisation *(attention, coup de gueule)*

Commençons directement par ce qui fache et qui gâche un peu l'événement : les failed au niveau de l'organisation.

Les deux années précédentes, la Blend (appelons la comme ça entre nous, ça sera plus simple) avait lieu à la Cité Internationale, au Centre des Congrés.

Cette année, elle avait lieu touhours à la Cité Internationale, mais à l'Amphitéatre.

Nous passons donc d'une organisation sur deux étages (un pour les conférences, un pour les pauses repas / goûter) à une organisation sur 4 étages.

Et autant le dire tout de suite : l'organisation ne semble pas avoir réussi à suffisament appréhender le changement.

---

Tout commence par l'accueil des participants et des orateurs : aucune gestion différentes entre les deux.<br />
Tout le monde dans la même file d'attente.

Vous aviez imprimé votre badge à l'avance pour gagner du temps ?<br />
Débrouillez-vous pour trouver la fille dédiée !

Vous n'aviez pas pré-imprimé votre badge ?<br />
Bah on ne les a pas imprimés à l'avance, on va le faire en live !<br />
Ah dommage, l'imprimante tombe en rade trop rapidement...

---

Mais revenons sur le changement de l'emplacement de la Blend cette année et le passage d'un événement géré sur 4 étages.<br />
A moins d'assister très règulièrement à des événements à l'Amphitéâtre de la Cité Internationale, savez-vous où se trouvent les salles "Gratte Ciel" et "Tête d'Or" ? <br />
Comment nous accédons à l'amphitéâtre ?<br />
Et bien moi non plus.

- pro-tips #1 : les réponses se trouvent entre l'étage -1 et l'égage 2 (évident)
- pro-tips #2 : prenez les ascenceurs pour avoir les réponses (de plus en plus évident)

Donc nous recevons notre programme avec des noms de salles et vamos amigos !<br />
Débrouille toi pour savoir où elles sont.<br />
Aucune indication sur les étages correspondant.<br />
Pas plus d'indication pour trouver le petit déjeuner (viennoiseries, café, jus de fruit tout ça).<br />
Et pourtant c'est vital pour bien commencer la journée ! (surtout si comme moi, vous n'aviez pas petit-déjeuné epxrès avant de venir).


Mais le point le plus négatif restera certainement les salles sous-dimensionnées pour un tel événement.<br />
Quasiment à chaque conférence qui ne se déroulait pas dans la salle plénière, des participants était contraint... de ne pas assister à la dite conférence par manque de place !<br />
(par chance, j'ai réussi à assister à toutes les conférences que je voulais).

Sérieusement les organisateurs de la Blend : Tristan Nitot en conférence dans une des plus petite salle ? <br />
**ARE YOU KIDDING ME ?!**

Bref, pour conclure sur cette partie, je trouve personnellement que l'organisation n'a pas du tout assuré cette année.


## Les conférences
Après ce "petit" coup de gueule d'introduction, rejouons le match des différentes conférences auxquelles j'ai pu assister.


### Écouter sa communauté, les bons outils pour développer le meilleur produit
par Christophe Gagin ([@chrisgagin](https://twitter.com/chrisgagin))


Malheureusement, cette conférence ayant commencé en retard, je n'ai pas pu rester assez longtemps pour tout voir.<br />
Je retiendrais donc de cette conférence :

- faire un produit qui réponde à un besoin
- écouter ses utilisateurs
- accepter la critique
- recueillir les retours négatifs à temps

Et niveau outils :

- uservoice
- segment.io
- KISSmetrics
- Google Analytics
- Intercom

Lien vers la présentation : [Blend Web Mix - chrisgagin - azendoo.pdf](https://www.dropbox.com/s/jr3pl06wu4br13n/Blend Web Mix - chrisgagin - azendoo - sans notes.pdf)



### Comment Docker révolutionne le web
par Geoffrey Bachelet ([@ubermuda](https://twitter.com/ubermuda), [geoffrey.io](http://geoffrey.io))

J'avoue, j'ai assisté à cette conférence car c'était Geoffrey qui la faisait (moi une groupie ? noooon).

Etant donné que c'était une conférence généraliste sur Docker, je n'ai pas trop appris grand chose.
Quelques bonnes pratiques d'architecture "fault tolerant" grâce à l'utilisation des ambassador.
J'aurais personnellement aimé avoir plus d'informations concernant l'orchestration (via FIG).

Lien vers la présentation : [https://speakerdeck.com/ubermuda/comment-docker-revolutionne-le-web](https://speakerdeck.com/ubermuda/comment-docker-revolutionne-le-web)



### On recode du cloudup en 20minutes
par Nicolas Chambrier ([@naholyr](https://twitter.com/naholyr))

Conférence sur Node.js, les streams en particulier.<br />
Que retenir de cette conférence ?<br />
1. Nicolas Chambrier est un artiste née (et méconnu) ;)
2. Les streams c'est quand même bien cool, mais dans un contexte bien particulier uniquement.

Les streams peuvent servir à faire l'upload d'un fichier et le stocker dans deux endroits en même temps (stockage local FS + stockage dans un système genre Amazon AWS).<br />
On peu aussi imaginer l'upload d'une vidéo et commencer à la regarder en streaming dès les premiers octets reçu : on n'est donc pas obligé d'attendre l'upload complet avant de commencer à regarder la vidéo.


Exemple d'application concrète : (https://cloudup.com)

Lien vers la présentation : [https://speakerdeck.com/naholyr/blendwebmix-14-streams-node-dot-js](https://speakerdeck.com/naholyr/blendwebmix-14-streams-node-dot-js)<br />
Exemple de code implémentant les streams : [https://github.com/naholyr/file-share-server](https://github.com/naholyr/file-share-server)



### Éditer du code ET prendre son pied : combien de lignes de codes à la minute ?
par David Boureau ([@davidb583](https://twitter.com/davidb583))

Le speach de la conférence : (honteusement copié depuis le site de la Blend, oui. Et alors ?)<br />
"*Editer du code, une tâche fastidieuse ? En tout cas une tâche obligatoire. Nous allons identifier tout ce qui est pénible et mettre en place une stratégie pour prendre du plaisir au quotidien.*"

J'avoue ne pas avoir trop accroché à cette conférence.

Ce que j'en retiendrais :

1. les développeurs doivent savoir taper au clavier sans le regarder <br/>
*si ce n'est pas le cas, faire des exercices de dactylographie jusqu'à ce que ça soit le cas*

2. connaître et utiliser les raccourcis claviers <br />
*et modifier les raccourcis claviers dans ses IDE pour gagner du temps*



### 100 % de revue de code
par Agnès Haasser ([@tut_tuuut](https://twitter.com/tut_tuuut))

Retour sur un cas pratique mis en place depuis près d'un an chez TEA : l'utilisation des pull-request pour avoir une revue de code effectuée à 100%. <br />
(bon en fait on découvrira pendant la conf' qu'ils utilisent les PR pour tout. Absolument tout)

Avantage des pull-request pour faire relire son code par quelqu'un d'autre ?

- asychrone : n'interrompt pas les autres dans leurs tâches (il regarderons les PR quand il pourrons).
- "sécurité" des passages en production : pas de mise en production sans 3 validations de chaque PR
- historique du code : "*mais que s'est-il passé pendant mes vacances ?*" (où mon congé parental)

Lien vers la présentation : [http://tut-tuuut.github.io/100-pourcents-de-revue-de-code](http://tut-tuuut.github.io/100-pourcents-de-revue-de-code)

### Front-end Dev Avengers : Brunch + fb-flo + Chrome DevTools : les super-héros d’un développement front fluide et rapide
par Christophe Porteneuve ([@porteneuve](https://twitter.com/porteneuve))

Ahhhhhh Christophe ! <br />
Depuis que j'ai fais ma première formation JS Total, je suis tout simplement fan de lui. <br />
Faites vous plaisir : assistez à une de ses conférences pour voir ce que c'est qu'un bon orateur avec de l'humour. <br />
Au moins une fois. <br />

Bref, Christophe nous a présenté ses outils pour réaliser du développement front (css, js, html) de façon fluide et rapide. <br />
Ses exemples ses basent sur les outils internes à Chrome, car pour l'instant IE et Firefox n'ont pas encore réduit le gap qui les sépare (mais ce n'est qu'une question de temps). <br />

Au menu :

- comment éditer son CSS et qu'il soit injecté dans la page courante (sans la recharger)
- idem avec les fichier JS
- et si j'ai plein de fichier CSS / JS que je doit concaténer / mininifer, je fais comment ?

Les outils à regarder :

- [brunch.io](http://brunch.io) : watcher / compilater à la volée (très rapidement)
- [browsersync](http://www.browsersync.io) : le mode Ghost qui permet de reproduire un comportement sur plusieurs navigateurs
- [fb-flo](https://github.com/facebook/fb-flo) : gère l'injection CSS / JS et le hot-swapping des fichiers (permet de prendre les modifications en compte sans recharger la page \o/)
- les workspaces (Chrome Dev Tools) : pour enregistrer localement les modifications faites dans les Chrome Dev Tools


Lien vers la présentation : [http://delicious-insights.com/talks/blend2014-dev-avengers](http://delicious-insights.com/talks/blend2014-dev-avengers) <br />
Lien vers le screencast lié à la présentation : [http://quick.as/6op4urjk](http://quick.as/6op4urjk)


### Pssst... tu veux voir ma stack ? Outils pour simplifier la vie d’un développeur
par Matthias Dugué ([@m4d_z](https://twitter.com/m4d_z), [m4dz.net](http://m4dz.net))

Présentation de différents outils pour développer dans de bonnes conditions (où du moins avoir le choix dans des outils intéressants et recommandés). <br />
Conférence très intéressante. <br />
La liste des différents outils présentés étant tellement importante, je vais me contanter de vous laisser consulter le slide vous-même :P <br />
(vous ne devriez avoir aucun soucis à comprendre le slide même sans avoir assisté à la présentation). <br />

Voici tout de même les thèmes abordés :

- System : shell, ruby, python, node.js
- Front-end dependencies : packages managers
- Automation : tasks runner, scaffolding
- Testing : boxes (vagrant, docker.io), provisionning (puppet, chef, ansible), JS tests frameworks, Scripting tests
- Back to code : CSS tools (sass/less, stylus, auto-prefixer), linters, templating, modules, devtools
- Devops : Continuous Integration, déploiement

Lien vers la présentation : [http://talks.m4dz.net/pssst_tu_veux_voir_ma_stack.html](http://talks.m4dz.net/pssst_tu_veux_voir_ma_stack.html)


<div class="alert alert-warning alert-pull-request" role="alert">
  <p><strong>Pull-Request !</strong><br> Une erreur de typo ? Grammar Nazi ? <br>
  N'hésitez pas à faire <a href="https://github.com/moriame/moriame.github.io/pulls">une PR !</a>
  </p>
</div>