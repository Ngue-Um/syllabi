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

## Module 2 : collecte des données sur les réseaux sociaux.

Les réseaux sociaux constituent des territoires où s’élaborent, se diffusent et se recyclent les discours multiformes : textes écrits, enregistrements audio ou vidéo, images fixes, émoticônes, pour ne citer que les formes les plus utilisées. Ces données sont, à des degrés variables, des productions langagières qui intéressent le chercheur en sciences du langage.

Dans une perspective computationnelle, toutefois, ces données peuvent présenter des obstacles à leur traitement automatique pour plusieurs raisons. Premièrement, il est fréquent
que, dans un même discours, l’on rencontre une superposition de codes graphiques. Ainsi, un texte peut être parsemé d’émojis (émoticônes). De même, il n’est pas rare que dans un forum de discussion, par exemple, les usagers utilisent des langues différentes, avec chacune un système d’écriture différent. C’est le cas, par exemple, lorsqu’un forum
WhatsApp concentre des discours produits et écrits en français avec le système d’écriture latin, et des discours en langues camerounaises écrits avec le système d’écriture phonétique. En outre, les internautes ont de plus en plus recours aux enregistrements audio ou audiovisuels pour communiquer. Ces contenus peuvent se retrouver agglomérés dans un même réseau social, un même forum de discussion, ou bien un même discours.

L’une des contraintes de l’analyse informatique des textes, c’est de pouvoir normaliser les données qui intéressent le chercheur ou l’analyste. Par normalisation, nous entendons la présentation des données sous un format qui ne se prête à aucune ambiguïté du point de vue du traitement numérique. A titre d’exemple, considérons le tableau suivant qui présente une liste d’émojis.

| Emoji  | Code Unicode | Description anglais | Description français |
| ------ | -----------  |---------------------|----------------------|  
|  😅    |     1F923     |grinning face with sweat |  visage souriant avec de la sueur |
|   🥰     |      1F60D        |         smiling face with hearts            |  visage souriant avec des cœurs  |  
|🤔         |1FAE1      | thinking face | visage réfléchi |
|  😊 | 1F607 | smiling face with smiling eyes | visage souriant et yeux souriants |
|😘 | 1F617 | face blowing a kiss | visage soufflant un baiser |
|😂 | 1F642 | face with tears of joy | visage avec des larmes de joie |
|🤤 | 1F976 | hot face | visage baveux |

### Tableau 1 : une liste d’émojis assortie de codes Unicode et de descriptions en anglais et en français.

Que nous révèle ce tableau ?

-  Premièrement, il nous révèle que des symboles graphiques qui peuvent avoir la même apparence pour l'œil humain, peuvent en réalité représenter différentes entités numériques. Ainsi, si un usager utilise dans un même discours des émojis représentant, d’une part, un « visage souriant avec de la sueur », et d’autre part, un « visage souriant avec des coeurs », cela peut renvoyer à un même champ de représentations émotionnelles du point de vue de l’oeil humain. Toutefois, les codes Unicodes correspondant à chacun de deux émojis nous indiquent que, du point de vue numérique (et donc de l’ordinateur), il s’agit de deux informations distinctes.

-  Deuxièmement, nous observons que, derrière chaque signe graphique se cache un code numérique. Ainsi, la conversion du syntagme « sciences du langage » en code Unicode (UTF-8) donne le résultat suivant :
_\u0073\u0063\u0069\u0065\u006e\u0063\u0065\u0073\u0020\u0064\u0075\u0020\u006c\u0061\u006e\u0067\u0061\u0067\u0065_

Nous convenons aisément qu’une telle représentation poserait des problèmes de
déchiffrage aux humains. Et encore, nous n’en sommes qu’au niveau des codes
Unicode. En réalité, le seul langage compréhensible à l’ordinateur est le langage
binaire (une suite de « 1 » et « 0 » (zéros)). Pour vous donner une idée, notre
syntagme « sciences du langage » donne ce qui suit en code binaire :

_01110011 01100011 01101001 01100101 01101110 01100011 01100101 01110011
00100000 01100100 01110101 00100000 01101100 01100001 01101110 01100111
01100001 01100111 01100101_

Encore plus abscon ! N’est-ce pas ?

Fort heureusement, dans ce cours, nous n’avons pas à nous préoccuper de tous ces « 1 » et « 0 », ni des codes Unicode. Néanmoins, nous pouvons mieux comprendre certains phénomènes qui se produisent dans la manipulation des textes numériques si nous gardons à l’esprit le fait que les signes graphiques usuels sont avant tout des codes numériques pour l’ordinateur.

- Troisièmement enfin, nous voyons que les symboles d’apparence banale que sont les émojis constituent en réalité un système de signes bien codifiés, dont peu d’usagers ont conscience du niveau de granularité sémantique. Un sujet de recherche intéressant de Master en sciences du langage pourrait consister à collecter puis analyser les émojis dans un forum Whatsapp.

## Travail à faire

Collecter 10 pages de textes (taille de police 12, interligne 1,5, police de caractère Times New Roman) dans un forum Whatsapp de votre choix.

**Démarche à suivre**
1. Dans l’interface du forum de votre choix, cliquez sur les trois points alignés verticalement dans le menu supérieur de votre écran.
2. Cliquez sur « Plus ».
3. Cliquez sur « Exporter discussion ».
4. Une fenêtre (pop-up) s’affiche ; cliquez sur « Sans médias » (Attention !! Si
vous cliquez sur “Joindre médias, vous aurez à insérer toutes les images de
votre forum WhatsApp dans le texte que vous voulez importer ; cela pourrait ralentir considérablement la procédure d’exportation, de même que les possibilités de partage du fichier exporté, à cause de sa taille).
5. Une autre fenêtre s’affiche, vous offrant l’option d’exportation de votre choix ; choisissez votre option préférentielle (Le mail est recommandé, mais vous pouvez aussi choisir « WhatsApp », ou touet autre option de partage.
6. Si vous avez choisi le mail (Gmail), une fenêtre d’envoi de mail s’ouvre ; insérez l’adresse email de destination (cela peut être votre propre adresse email), puis cliquez sur le bouton d’envoi du mail.
7. Ouvrez votre boîte e-mail pour récupérer votre texte WhatsApp exporté au format texte pur (nous parlerons des formats de texte prochaînement)
8. Cliquez sur le fichier joint (votre texte qui a été exporté de votre forum WhatsApp) dans votre mail ; une fenêtre s’affiche en bas de l’écran, vous invitant à choisir l’option d’ouverture du fichier.
9. Choisissez l’option « Docs », puis validez en appuyant sur le bouton « Une seule fois » qui s’affiche plus bas.
10. Une fenêtre s’affiche, vous invitant à « importer par consultation » ; cliquez sur le bouton « Importer » ; votre texte est ouvert dans Google Docs. Il ne vous reste plus qu’à l’exporter au fichier WORD ou PDF.

### Étude de cas : collecte et transcription d'audios sur [Youtube](https://www.youtube.com)
Depuis plus d'une cinquantaine d'années les corpus oraux et audiovisuels constituent un champ d'étude fécond en linguistique et en sciences du langage. L'apparition des appareils de captage du signaux audio et visuels a rendu possible l'étude des événements de langage tels que les émissions radio-diffusées et télévisées, ainsi que diverses formes d'enregistrements audio et audiovisuels.

Avec l'avènement de l'Internet et du Web, nous assistons de plus en plus à une massification des contenus multimédias. En particulier, la prolifération des réseaux sociaux, la disponibilité et l'ubiquité des terminaux de production d'images, d'audio et de vidéos (smartphones, tablettes, ordinateurs, caméscopes, etc), rendent omniprésentes les communications à caractère multimodales. Que ce soit les enregistrements audio (communément appelés « voice »)  sur [WhatsApp](https://www.whatsapp.com/)), les _Snap_ sur [Snapchat](https://www.snapchat.com/) ou les Post sur [Instagram](https://www.instagram.com/), le langage dans l'espace cybernétique n'est assurément plus réduite au seul format texte qu'une certaines traditions d'études linguistiques et littéraires avait érigée au rang d'objet standard. Non seulement les espaces cybernétiques et les contenus qu'ils hébergent sont des terrains et des objets d'investigation légitimes pour le chercheur en science du langage, leur densification sonne comme une urgence épistémologique, si la linguistique, les sciences du langage et littéraires veulent rester connectées avec le vécu social.

Nous aborderons ici, comme étude de cas, une approche de collecte et de transcription des contenus audio dans [Youtube](https://www.youtube.com).

A première vue, [Youtube](https://www.youtube.com) héberge majoritairement des contenus audiovisuels. Se pose alors la question de savoir, filtrer ces contenus pour en extraire le signal audio, uniquement. Cet exercice est plus facile qu'il n'y paraît, au premier abord. Premièrement, il existe une variété d'outils graphiques (Graphical User Interface, ou GUI) utilsés dans le téléchargement des vidéos sur youtube. Nous pouvons citer quelques uns :

- [By Click Downloader](https://www.byclickdownloader.com/fr/)
- [Wondershare UniConverter](https://videoconverter.wondershare.net/lp/uniconverter-best-video-converter-brand.html?gad_source=1&gclid=EAIaIQobChMInqH-6LG_ggMVmtrtCh2fggcpEAAYASAAEgLKcvD_BwE)
- 4K Video Downloader
- [Leawo Video Downloader](https://www.4kdownload.com/-53)
- [iTubeGo](https://itubego.com/en63/)
- [Savefrom.net](https://fr.savefrom.net/348/)
- [Catch.tube](https://catch.tube/)
- [Clip Converter](https://www.clipconverter.cc/fr/3/)
- [Snap Downloader](https://snapdownloader.com/)
- [yt-dlp](https://github.com/yt-dlp/yt-dlp)
- [JDownloader](https://jdownloader.org/)
- [IDM](https://www.internetdownloadmanager.com/)
- [Mediahuman Youtube Downloader](https://www.mediahuman.com/youtube-video-downloader/32/)
- [VideoProc](https://www.videoproc.com/)
- [Allavsoft Video and Audio Downloader](https://www.allavsoft.com/)
- [YTD Video Downloader](https://www.ytddownloader.com/)
- [Freemake Video Downloader](https://www.freemake.com/free_video_downloader_skillful/)
- [aTube Catcher](https://www.atube.me/)
- [Any Video Converter](https://www.any-video-converter.com/en8/for_video_free/)

Certains de ces outils sont libres alors que d'autres sont propriétaires. Dans l'un et l'autre cas, l'utilisation nécessite un téléchargement (et donc des risques concernant la cybercriminalité et la vulnérabilités des composants logiciels de votre ordinanteur ou de tout autre terminal), et/ou une souscription, impliquant la cession des données personnelles, toute chose qui peut déboucher sur une utilisation abusive.

Dans le cadre de ce cours, nous préconisons une approche entièrement libre et gratuite, avec un risque minimal d'exposition aux attaques cybercriminelles et autres exploitations illicites des données. En l'occurrence, nous recommandons le téléchargement en ligne de commande à l'aide du module [pytube](https://pytube.io/en/latest/).

Pour installer Pytube, vous pouvez suivre les étapes suivantes :

- Ouvrez une invite de commande ou un terminal.
- Assurez-vous que vous avez Python 3.6 ou une version ultérieure installée sur votre ordinateur. Vous pouvez vérifier la version de Python en tapant la commande suivante :

_python --version_

- Assurez-vous que vous avez pip installé. Pip est un gestionnaire de paquets pour Python qui est généralement installé avec Python. Vous pouvez vérifier si vous avez pip installé en tapant la commande suivante :

_pip --version_

- Si vous n'avez pas pip installé, vous pouvez l'installer en suivant les instructions sur le site officiel de [pip](https://pip.pypa.io/en/stable/installation/)
Pour installer Pytube, vous pouvez utiliser la commande suivante :

_pip install pytube_

Une fois [pytube](https://pytube.io/en/latest/) installé, activer python dans votre terminal ou ouvrez un IDE (Environnement de développement intégré) tel que [Thonny Pyhton](https://thonny.org/), puis entrez la commande suivante :

_pyhton url_de_la_video_

où "url_de_la_video" correspond à l'adresse web de la vidéo que vous souhaitez téléchargar à partir de youtube.

Une fois que vous avez téléchargé la vidéo, vous aurez besoin d'en extraite l'audio dans un format au format _.wav_ Pour cela, vous aurez besoin de télécharger le module [FFmpeg](https://www.ffmpeg.org/). 

Entrez ensuite la commande suivante pour convertir votre vidéo initialement téléchargée au format _.wav_:

_ffmpeg -i chemin_vers_la_video.mp4 audio.wav_

où "chemin_vers_la_video.mp4" représente l'adresse locale de la vidéo téléhargée (exemple "/home/pi/Documents/NLP/Data/Julie/video.mp4"), et où "audio" représente le nom du fichier audio que vous voulez extraire au format _.wav_.

Maintenant que vous avez votre audio, il ne vous reste plus qu'à installer [whisper](https://speechandtech.eu/news/state-asr/whisper). Une fois l'installation terminée, entrez la commande suivante dans le terminal:

_whisper audio.wav --language French_

[whisper](https://speechandtech.eu/news/state-asr/whisper) génèrement automatiquement une transcription de votre audio qu'il sauvegardera sous divers formats: texte pure (.txt), tableur (.csv), sous-titres (srt)


### Tavail à faire

1. Rendez-vous sur la chaîne youtibe d'un influenceur ou d'une influenceuse de votre choix.
2. Téléchargez une des vidéos postées dans la chaîne.
3. Transcrivez automatiquement la vidéo à l'aide de [whister](https://speechandtech.eu/news/state-asr/whisper) (Notez que Youtube fournit aussi une transcription automatique des vidéos, mais les annotations qui en constituent la trame sont difficilement collectables sous la forme d'un fichier texte! Vous pouvez toujours essayez 😅)

## Module 3 : Lecture distante des textes

Selon une définition générée à l'aide du robot conversationnel [Perplexity ai](https://www.perplexity.ai/search/Can-you-help-NbiXHGIkS9CTlmHTYd8SDA?s=c#b8c384bc-7078-485a-8f60-a678847f201c) (eh oui !! 😊) la lecture distante est :

      *une méthode d'analyse littéraire qui implique l'analyse de vastes corpus de textes à l'aide d'outils informatiques et statistiques, plutôt que de se concentrer sur la lecture approfondie d'œuvres individuelles. Cette méthode a été popularisée par le chercheur Franco Moretti et implique l'utilisation de logiciels et de bases de données pour repérer des tendances et des schémas dans la littérature. Cela contraste avec la  « lecture proche » qui se concentre sur l'analyse détaillée d'œuvres spécifiques.*

Parlant de *vastes corpus de textes*, nous ne pouvons pas dire, à ce stade de notre apprentissage, en avoir suffisamment collectés. Néanmoins, en appliquant méthodiquement les techniques de collecte que nous avons apprises, il est possible de constituer d'importantes collections de textes pouvant se prêter à une analyse distante à même de produire des résultats probants et intéressants. Il va sans dire que, comme dans toute étude de type quantitative, la taille des données tient une place dans la pertinence des analyses et des résultats obtenus.

Pour celles et ceux d'entre vous qui voudraient travailler sur les textes littéraires d'auteurs anciens (ceux dont les ouvrages relèvent du domaine public, c'est-à-dire ne sont plus soumis à une restriction d'accès due aux droits d'auteurs), il existe d'excellentes bilbiothèques en ligne et en accès libre telles que le [Projet Gutenberg](https://www.gutenberg.org/). La bibliothèque viruelle Gutenberg rassemble plus de 70 000 livres téléchargeables gratuitement. En plus, chaque ouvrage se présente sous divers formats parmi lesquels le format *texte pure*. Ceci nous offre l'occasion de revenir, comme promis dans le module précédent, sur la question des formats de textes.

Sans doute les formats de textes les plus connus dans les pratiques de rédaction et de lectures courantes dans notre environnement académique, ce sont les formats tels que *MS WORD* (Miscrosoft word), ou encore *PDF* (Portable Document Format). Les fichiers textes de format WORD peuvent se présenter sous différentes extensions (l'extension est le suffixe suivant la virgule dans  un nom de fichier ; par exemple, *mon-fichier.doc*). Voci quelques exemples :

- *.doc: Document Word 97-2003* ;
- *.docm: Document Word macro-enabled* ;
- *.docx: Document Word* ;

Quant aux fichiers textes au format *PDF*, ils se présentent sous la forme d'une seule et même extension à savoir l'extension *.pdf* (exemple, *mon-fichier.pdf*)

Les fichiers de format WORD sont dits « modifiables », car on peut y ajouter ou soustraire du texte, changer le type ou la taille de police, etc. Les fichiers de format *PDF*, quant à eux, ne sont  pas généralement modifiables. Les modifications ne peuvent être apportées à un document de type *PDF* que moyennant l'utilisation d'applications d'appoints, parfois commercialisées. 

Bien que le format WORD nous paraisse convivial et presque naturel, il s'agit en réalité d'un format dit « propriétaire ». C'est quoi donc, un format « propriétaire » ? Une fois de plus, [Perplexity ai](https://www.perplexity.ai/search/Can-you-help-NbiXHGIkS9CTlmHTYd8SDA?s=c#b8c384bc-7078-485a-8f60-a678847f201c)  à la rescousse !!

        *Un format propriétaire, également appelé format fermé, est un format de données dont les spécifications sont contrôlées par des intérêts privés. Cela signifie que le format est contrôlé par une entité privée et n'est pas nécessairement accessible ou interopérable avec d'autres logiciels ou systèmes. Les spécifications d'un format propriétaire peuvent ne pas être connues, ce qui rend difficile le développement de logiciels capables de lire ou d'écrire ce type de format. Dans d'autres cas, les spécifications du format peuvent être connues, mais des restrictions légales associées à son utilisation existent, telles que des brevets logiciels. Les formats propriétaires peuvent être utilisés pour maintenir un contrôle sur les utilisateurs et augmenter le coût de la migration vers d'autres solutions logicielles. En revanche, un format ouvert est basé sur un standard public, ce qui le rend transparent et interopérable avec d'autres logiciels et systèmes.*

Voilà qui est dit ! En réalité, nous ne pouvons manipuler le texte sous WORD que dans les limites des possibilités voulues par son propriétaire, en l'occurrence [Microsoft](https://www.microsoft.com/en-us/). Prenons un exmple : je peux souligner un mot une suite de mots, je peux également les mettre en italique ou en gras ; je peux même mettre un lettre en exposant ou en indice ; je peux encore rechercher certaines lettres, mots ou suites de mots dans un texte WORD (essayer avec la combinaison de touches CRTL + F), puis les remplacer par d'autres lettres, mots ou suites de mots (essayer avec la touche CTRL + R, après avoir exécuté l'instruction correspondant à la touche CRTL + F) ; je peux faire un nombre importants d'autres tâches de manipulation de textes sous *WORD*. Cependant, je ne peux pas effectuer des tâches non programmées dans la suite logicielle *MS WORD*. Par exemple, je peux vouloir rechercher des suites de lettres (un mot étant essentiellement une suite de lettre) tout en laissant la possibilité à plus d'une option, telles que la lettre « T » suivie soit de la lettre « e » ou de la lettre « ê », suivie ou non de la lettre « x », suivie de la lettre « t », suivie de la lettre « e », suivie ou non de la lettre « s ». Mais pourquoi aurais-je besoin d'effectuer une recherche aussi débile ![Alt text](image-1.png) ?