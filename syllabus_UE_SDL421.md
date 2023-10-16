# Outils informatiques pour la linguistique
## Traitement automatique du langage
#
**Résumé**

Ce cours porte sur le traitement automatique des langues. Il est destiné aux étudiants, enseignants et chercheurs en sciences humaines et sociales d'expression francophone, en particulier celles et ceux travaillant en Afrique. Le cours est constitué d'une suite de modules conçus pour guider les apprenant.e.s dans la découverte, la prise en main et l'opérationalisation d'outils et de techniques informatiques en vue de réaliser de manière automatique au semi-automatique des taches spécifiques de traitement de l'information.


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

De manière spécifique, ce cours vise à :

- amener l'apprenant.e à comprendre techniquement le fonctionnement de l'ordinateur ;
- initier l'apprenant.e à interagir avec l'ordinateur en formulant des instructions spécifiques sous forme de texte (par opposition à l'utilisation des boutons, des fenêtres et de la souris dans une interaction graphique) ;
- initier l'apprenant.e à l'automatisation des taches de langage moins complexes, dans le cadre de la recherche en sciences sociales et humaines ;
- initier l'apprenant.e à l'utilisation de Github comme espace de travail collaboratif à distance, d'archivage et de publication des textes de nature diverse.

## Compétences visées

En suivant ce cours de bout en bout, vous pourrez par la suite:

- comprendre techniquement le fonctionnement d'un ordinateur ;
- créer votre propre environnement de travail dans la plateforme Github, d'y publier des textes comme le présent syllabus et de collaborer sur un même projet avec d'autres auteurs ;
- travailler en ligne de commande (interagir avec l'ordinateur à l'aide d'instructions formulées sous forme de texte) ;
- préparer un texte ou une collection de textes en vue du traitement automatique ou semi-automatique de l'information linguistique ;
- réaliser de manière automatique ou semi-automatique des taches de traitement du langage moins complexes évoquées précédemment (extraction et classification de l'information textuelle, fréquence des mots, listes des mots, stylométrie, concordancement, etc.)

## Organistion du cours

Ce cours est organisé en cinq modules.

Le premier module a trait à l'écosystème de l'ordinateur. Il aborde sommairement l'architecture numérique de l'ordinateur et les procédés par lesquels ce dernier enregistre l'information, l'interprète puis la visualise à travers une interface comme l'écran.

Le deuxième module aborde le codage de l'information numérique. Le codage est une technique qui consiste à représenter l'information (par exemple des caractères dans un texte) par des codes standards compréhensibles par toutes les machines. Ce module introduit le système de codage [UNICODE](https://fr.wikipedia.org/wiki/Unicode) qui est le standard international par défaut permettant l'échange de l'information à travers plusieurs plateformes, plusieurs environnements de travail et plusieurs ordinateurs à l'échelle globale.

Le troisième module est relatif à l'interaction en [ligne de commande](https://fr.wikipedia.org/wiki/Interface_en_ligne_de_commande) entre l'usager et l'ordinateur. Ce module passe en revue les commandes (les instructions écrites) essentielles permettant de réaliser des opérations de traitement automatique ou semi-automatique de l'information numérique (textes et nombres).

Le quatrième module traite de corpus en linguistique et en littérature computationnelles. Nous aborderons les méthodes et techniques d'élaboration des corpus de même que quelques outils et techniques d'exploration des corpus.

Le cinquième et dernier module concerne le logiciel [Git](https://fr.wikipedia.org/wiki/Git) et l'environnement de travail [Github](https://github.com/).

Chaque module comporte un tutoriel qui aborde les différentes étapes à suivre en vue de réaliser une compétence donnée. Les modules sont conçus dans une logique progressive et complémentaire. Il est par conséquent recommandé aux débutant.e.s de commencer par le premier module puis de continuer avec les suivants dans leur ordre d'enchaînement. Les apprenant.e.s plus avancé.e.s pourront, à leur guise, choisir quel module aborder en priorité.

## Pré-requis

Pour tirer le meilleur de ce cours et des tutoriels qui l'accompagnent, les apprenant.e.s sont invité.e.s à se munir des outils et des ressources suivants :

- un ordinateur en bon état de fonctionnement ;
- une connexion internet stable ;
- un ou plusieurs textes au format numérique et éditable (le traitement des données sous forme d'image et de textes non éditables tels que le format PDF ne fait pas partie des aspects du présent cours).

En outre, les apprenant.e.s sont invité.e.s à installer sur leurs ordinateurs les logiciels suivants :

- [WSL (Windows Subsystem for Linux)](https://docs.microsoft.com/en-us/windows/wsl/install) ;
- [git](http://git-scm.com/download/win)
- [git bash](https://github-releases.githubusercontent.com)

## Module 1 : Architecture et fonctionnement d'un ordinateur

L'ordinateur est un outil omniprésent dans le quotidien d'un nombre de plus en plus croissant de personnes. Sans doute pour beaucoup de personnes encore, le mot [ordinateur](https://fr.wikipedia.org/wiki/Ordinateur) évoque avant tout un objet ou un assemblage d'objets physiques : desktop/laptop, écran, souris, clavier, etc. En réalité, l'ensemble des composants physiques qui représentent un ordinateur sont avant tout une machinerie et un système : une machinerie car chacun de ces composants est une machine particulière ; système parce que l'ensemble des machines assemblées pour constituer un ordinateur participent d'une même fonction, celle du traitement de l'information. Il serait alors plus approprié de se représenter l'ordinateur comme un système de traitement de l'information. En effet, la physionomie particulière que peut prendre la machinerie d'un ordinateur est en constante évolution ; elle est passée de la machine à caculer inventée par [Charles Babbage](https://fr.wikipedia.org/wiki/Charles_Babbage) en 1835 au [superordinateur](https://fr.wikipedia.org/wiki/Superordinateur) ou supercalculateur. Dans son aspect fonctionnel, le concept d'ordinateur rassemble une gramme très large d'outils de la vie quotidienne : téléphone, micro-onde, voiture, porte électronique, horloge, jeux vidéos, téléviseurs. La propriété commune de ces outils c'est la capacité d'exécuter des taches programmées : afficher une image, sonner à une heure choisie, chauffer à une température donnée pour un temps donné, freiner devant un obstacle, etc.

La science informatique s'occupe, entre autres, d'élaborer les formes d'instructions à partir desquelles les ordinateurs vont pouvoir exécuter des taches précises.

Un programme informatique est une suite d'instructions exécutables par un ordinateur. Par exemple, le texte que vous lisez actuellement sur votre PC ou sur votre smartphone est la traduction d'une instruction par laquelle un moteur de recherche affiche sur l'écran de votre appareil des suites de caractères stockées dans un ordinateur distant, en l'occurrence un serveur.

La formulation d'instructions particulières destinées à être exécutées par un ordinateur est appellée [programmation informatique](https://fr.wikipedia.org/wiki/Programmation_informatique) ou codage. Ces instructions sont organisées en un système de signes appelé [langage de programmation](https://fr.wikipedia.org/wiki/Langage_de_programmation). 