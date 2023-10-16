# Outils informatiques pour la linguistique
## Traitement automatique du langage
#
**Résumé**

Ce cours porte sur le traitement automatique des langues. Il est destiné aux étudiants, enseignants et chercheurs en sciences humaines et sociales d'expression francophone, en particulier celles et ceux travaillant en Afrique. Le cours est constitué d'une suite de modules conçus pour guider les étudiants dans la découverte, la prise en main et l'opérationalisation d'outils et de techniques informatiques en vue de réaliser de manière automatique au semi-automatique des taches spécifiques de traitement de l'information.


## Présentation générale du cours

Le [Traitement Automatique du Langage (TAL)](https://fr.wikipedia.org/wiki/Traitement_automatique_des_langues) consiste à faire exécuter par la machine des tâches de langage humain telle que la production de la parole et la production d'écrits. Le TAL consiste également à réaliser les opérations d'extraction et de modélisation de l'information linguistique dans le cadre de la recherche en sciences sociales et humaines. Le TAL occupe une place centrale dans les statrégies de communication des organisations, des industries, et mêmes des États. Ceci invite à adapater la perspective de a formation universitaire en sciences du langage. 

Quelques applications courantes résultant du **TAL** sont :

- la traduction automatique ;
- la reconnaissance automatique de la voix ; en anglais, *Automatic Speech Recognition (ASR)* ;
- la synthèse de la voix (exemple : faire lire un texte par la machine) ;
- la correction orthographique (généralement intégrée dans les éditeurs de textes tels que WORD mais aussi, les téléphones "intelligents") ;
- le résumé automatique ;
- le concordancement ;
- la stylométrie ;
- la textométrie ;
- l'analyse des sentiments ;
- la reconnaissance d'entités nommées ; en anglais,*Name Entity Recognition* ;
- etc.

L'automatisation de certaines de ces tâches, par exemple la traduction automatique et la reconnaissance automatique de la voix nécessite des technologies complexes. Le développement de ces technologies repose sur une haute expertise en informatique mais aussi, requiert des quantités de données importantes en vue d'entraîner la machine à exécuter des tâches spécifiques. Par exemple, dans le cadre de *l'apprentissage automatique* ou [Machine Learning](https://fr.wikipedia.org/wiki/Apprentissage_automatique), il faut mobiliser des données d'entraînement (ou d'apprentissage) conséquentes pour que la machine puisse produire des résultats satisfaisants.

Voilà pourquoi les logiciels qui permettent la traduction automatique ou la reconnaissance de la voie sont généralement fournis pour des compagnies ou des organisations bien dotées en ressources humaines et financières.

À côté des tâches complexes telles que la traduction automatique et la reconnaissance de la voie, il existe une gamme de tâches plus souples et réalisables avec un minimum de connaissances informatiques et de ressources. Parmi ces tâches accessibles, on peut citer :

- l'extraction d'informations ciblées dans un texte, un ensemble de textes (par exemple, l'ensembles des émoticones dans un forum [Whatsapp](https://fr.wikipedia.org/wiki/WhatsApp)) ou un tableur (Excel ou Google Sheet, par exemple) ;
- la classification de l'information à partir d'une ou de plusieurs sources (par exemple, l'ensembles des émoticones exprimant des émotions positives dans un forum [Whatsapp](https://fr.wikipedia.org/wiki/WhatsApp)) ;
- la modélisation du style d'un internaute (par exemple, pouvoir reconnaître le style d'un internaute qui se cache derrière plusieurs "faux" profils) ;
- la compilation d'une liste de mots à partir d'un texte ou d'un ensemble de textes (exemple, le vocabulaire d'un internaute ou d'un auteur particulier) ;
- la fréquence des mots dans un ou plusieurs textes ;
- la collocation ou concordancement (par exemple, faire ressortir les mots qui apparaissent ensemble, les uns à côtés des autres) ;
- etc.

## Objectif général du cours

L'objectif général de ce cours est d'initier les étudiants à la lecture distante.

## Objectifs spécifiques

De manière spécifique, ce cours vise :

- l'anayse les réseaux sociaux comme territoires numériques où se déploient des discours spécifiques;
- l'initiation aux techniques et outils de collecte, d'organisation et de normalisation des données langagières sur les réseaux sociaux ;
- l'initiation à la lecture distante à l'aide de [Voyant tools](https://voyant-tools.org/) et [R](https://www.r-project.org/about.html).

## Compétences visées

En suivant ce cours de bout en bout, vous pourrez par la suite :

- analyser les stratégies de captage de l'attention utilisée par les média/réseaux sociaux tels que [Youtube](https://www.youtube.com/), [Facebook](https://web.facebook.com/?_rdc=1&_rdr), [Instagram](https://www.instagram.com/), [X](https://twitter.com/?lang=en), etc. ;
- collecter de manière automatique ou semi-automatique des données textuelles, photographiques, audio et audiovisuelles sur les réseaux sociaux ;
- transcrire automatiquement ou semi-automatiquement des vidéos et des audios collectées sur les média/réseaux sociaux ;
- analyser les textes des réseaux sociaux de manière critique (modéliser les sentiments et/ou les opinions des "influenceurs, par exemple) dans une perspective computationnelle.

## Organistion du cours

Ce cours est organisé en trois modules.

Le premier module a trait à l'espace numérique en tant qu'espace discursif. Nous définirons en les approfondissant, les concepts de "territoire numérique", de "communauté de discours", d'"économie de l'attention", d'"algorithme", de "techno-pouvoir".

Le deuxième module a trait à la collecte des données sur les média/réseaux sociaux. Nous aborderons les techniques de captage massif (*web scrapping*) des textes, des images, des audios et des vidéos, à l'aide des outils graphiques mais aussi, en ligne de commande (pour les plus hardis et les aventuriers ![Alt text](image.png) !!) 

Dans le troisième module, nous aborderons la lecture distante. Nous verrons comment explorer les données textuelles plus ou moins massives, pour extraire les paramètres les plus significatifs tels que les opinions et les sentiments. 


## Pré-requis

Pour tirer le meilleur de ce cours, les aétudiants sont invités à se munir des outils et des ressources suivants :

- un ordinateur en bon état de fonctionnement ;
- une connexion internet stable ;

En outre, les étudiants sont sont invités à installer sur leurs ordinateurs les logiciels suivants :

- [WSL (Windows Subsystem for Linux)](https://docs.microsoft.com/en-us/windows/wsl/install) ;
- [git](http://git-scm.com/download/win)
- [git bash](https://github-releases.githubusercontent.com)

Pour maximiser le temps impartis aux sessions communes en salle (lundi, de 7:30 à 9:30), l'installation de ces logiciels se fera en dehors de ces sessions. Les étudiants qui souhaitent se faire assister dans l'installation des logiciels devront se signaler auprès des enseignants.

## Module 1 : Les média/réseaux sociaux comme territoires numériques.

Ce module est basé sur l'article publié par Ngué Um et Ndindjock et intitulé [La dynamique des discours cybernétiques Point de rencontre entre « territoire numérique » et « communauté discursive » sur les réseaux sociaux ?](https://publications-prairial.fr/balisages/index.php?id=601). 