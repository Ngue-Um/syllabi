# Outils pour la production du matériel didactique numérique et multimédia en langues camerounaises (LACC2342 — ENS Yaoundé)

**Enseignant** : Prof. Emmanuel Ngue Um
**Institution** : École Normale Supérieure de Yaoundé — Département des Langues et Cultures Camerounaises
**Public** : Élèves-professeurs de Niveau 2
**Année universitaire** : 2025-2026, Semestre 2
**Horaire** : mardi, 8h – 10h
**Volume horaire** : 28 heures (14 séances de 2 heures)
**Évaluation** : Contrôle continu 30 % + Projet d'équipe progressif 70 %
**Prérequis** : Technologies vocales pour les langues africaines peu dotées (LCC2, S1)

---

## Objectif général

Concevoir et prototyper, à partir des ressources ALCAM publiées sur la plateforme Mozilla Data Collective (mdc) et en dialogue avec une IA générative comme Claude, des matériels didactiques numériques et multimédias pour l'enseignement des langues nationales dans le secondaire, en conformité avec les programmes officiels du MINESEC (classes de 6e, 5e, 4e et 3e).

## Objectifs spécifiques

- S'approprier la structure et les contenus des programmes officiels de langues nationales du MINESEC (6e / 5e et 4e / 3e).
- Maîtriser la structure des jeux de données ALCAM (TSV + audio) et les recombiner pour des usages didactiques.
- Orchestrer, avec une IA générative (Claude), des scénarios didactiques conformes à l'approche par compétences en vigueur au Cameroun.
- Intégrer les audios ALCAM et leur traduction française dans des prototypes d'applications ou de plateformes interactives d'enseignement.
- Documenter, évaluer et publier un matériel didactique numérique réutilisable.

---

## Plan du cours

### Partie I — Cadrage didactique et technique (4 séances / 8 h)

#### Séance 1 — Introduction générale et cadrage

- Rappel des acquis de LCC2 : ASR, TTS, NMT, enjeux éthiques.
- Passage des technologies linguistiques à la production didactique : quoi, pour qui, pour quoi ?
- Présentation du dispositif : équipes de projet, langue de référence, calendrier, livrables.
- Inscription collective sur la plateforme Mozilla Data Collective : [mdc — Institut des Humanités numériques africaines](https://mozilladatacollective.com/organization/cmfv3ichk000amd07piai0zoz).

#### Séance 2 — Les programmes officiels de langues nationales du MINESEC

- Architecture des programmes : approche par compétences, entrée par les situations de vie, domaines de vie, familles de situations.
- Programme 6e / 5e : Module I (Diversité linguistique), Module II (Productions segmentales), Module III (Suprasegmentaux), Module IV (Syntagme nominal), Module V (Syntagme verbal), Module VI (La phrase).
- Programme 4e / 3e : approfondissement, textes, productions langagières en contexte.
- Volume horaire secondaire : 2 h hebdomadaires, coefficient 2.
- TP 1 : cartographier en binôme les « savoirs essentiels » d'un module MINESEC sur les contenus disponibles dans un jeu ALCAM.

#### Séance 3 — Les ressources ALCAM sur mdc

- Généalogie du projet ALCAM : Atlas Linguistique du Cameroun, listes lexicales, phrases-types.
- Lecture d'un fichier ALCAM TSV : colonnes `OrigID`, `EditID`, `FrenchRef`, `French`, `POS`, `Class`, `Morf`, `Word`, `FrenchEx`, `LangEx`, `LangPars`, `FrenchPars`.
- Les 16 jeux ALCAM publiés sur mdc : Basaa, Ewondo, Bulu, Gbaya, Tikar, Fong, Mvele, Bakossi, Tuki-Tumbele, Tuki-Tukombe, Balom, Badjia, Banoo, Mipa, Yezoum, Diboum.
- TP 2 : chaque équipe choisit sa langue de référence et son corpus ALCAM ; inventaire des champs et des audios disponibles.

#### Séance 4 — Les audios ALCAM et l'articulation texte-son-traduction

- Structure des dossiers `audio_files/` et `audio_files_MP3/` : correspondance avec les identifiants ALCAM.
- Qualité sonore, normalisation, lecture programmatique (Python, ffmpeg, navigateur).
- Principes didactiques pour l'usage de l'audio en classe : compréhension orale, production orale, discrimination phonétique, reconnaissance tonale.
- TP 3 : extraire d'un corpus ALCAM 20 paires `(phrase-langue, audio, traduction française)` pertinentes pour le Module II (segmentaux) du programme 6e / 5e.

### Partie II — Orchestration des scénarios didactiques avec l'IA (4 séances / 8 h)

#### Séance 5 — IA générative et enseignement des langues

- Panorama des IA génératives utiles en 2026 : Claude, GPT, Gemini, Mistral ; modalités (texte, audio, vision).
- Ce qu'une IA générative peut faire pour l'enseignement des langues nationales : plan de cours, exercices gradués, reformulations, évaluation formative, fiche pédagogique.
- Ce qu'une IA générative ne doit pas faire : substitut au locuteur natif, arbitre des normes dialectales, producteur non vérifié de contenu culturel.
- Éthique et droits : sources, consentement, biais linguistique, hallucinations.

#### Séance 6 — Principes de l'invite pédagogique (*prompting* didactique)

- Anatomie d'une invite efficace : rôle, contexte, tâche, contraintes, format de sortie, ressources injectées.
- Patrons d'invites pour le cours de langue nationale : « plan de séance », « situation d'apprentissage », « famille d'exercices », « fiche d'évaluation », « remédiation ».
- Techniques d'injection de données : coller un extrait de TSV ALCAM et 3 audios, demander à Claude de produire une fiche conforme à un module MINESEC.
- TP 4 : écrire, en binôme, une invite qui génère une fiche de séance de 6e à partir d'un extrait ALCAM Ewondo (Module II, production segmentale).

#### Séance 7 — Atelier de simulation I : scénariser un cours de 6e / 5e

- Point de départ : module MINESEC au choix + jeu ALCAM de la langue de référence de l'équipe.
- Production : un plan complet de séance de 2 h avec situation de vie, compétences visées, savoirs essentiels, déroulement, supports audio-texte, évaluation.
- Co-rédaction homme-IA : génération, relecture critique, correction, enrichissement.
- Livrable : fiche de séance rédigée, validée par l'équipe.

#### Séance 8 — Atelier de simulation II : scénariser un cours de 4e / 3e

- Même démarche, avec le programme 4e / 3e (syntaxe, textes, production écrite).
- Ajout d'une composante multimédia (image, extrait audio, court texte issu de l'oral) et d'une évaluation formative interactive.
- Livrable : fiche de séance de 2 h, annotée, prête à être testée devant des élèves de l'ENS Annexe ou d'un établissement partenaire.

### Partie III — Prototypage d'outils interactifs (6 séances / 12 h)

#### Séance 9 — De la fiche à l'application : architectures possibles

- Fiche papier → fiche numérique → application autonome → plateforme en ligne.
- Briques techniques accessibles : HTML/CSS/JS, React, Streamlit, Flask, Gradio.
- Modalités d'intégration audio : balise `<audio>`, API Web Audio, lecteurs personnalisés.
- Présentation de prototypes existants : apps pédagogiques en bambara, wolof, swahili.

#### Séance 10 — Devoir sur table (3/4 du cours)

- Épreuve écrite de 2 h portant sur les séances 1 à 9.
- Questions sur le programme MINESEC, la structure ALCAM, l'éthique de l'IA générative, l'invite didactique.
- Exercice : produire, papier-crayon, un plan de séance à partir d'un extrait ALCAM fourni.
- Le devoir compte pour 30 % de la note finale.

#### Séance 11 — Atelier de prototypage I : interface web minimale

- Mise en place, avec l'appui de Claude, d'une page web qui affiche 20 phrases ALCAM avec leur audio et leur traduction française.
- Règles d'accessibilité : boutons visibles, sous-titres, contrôle du débit, lecture répétée.
- Déploiement local et sur une plateforme gratuite (GitHub Pages, Vercel, Netlify).
- Livrable intermédiaire : maquette fonctionnelle partagée par URL.

#### Séance 12 — Atelier de prototypage II : exercices interactifs

- Ajout d'activités didactiques : appariement audio-texte, discrimination tonale, dictée, QCM de compréhension.
- Stockage des scores en mémoire (sans base de données) ; export CSV pour l'enseignant.
- Gestion du multi-langue ALCAM : choix de la langue à l'accueil.
- Livrable : version v2 du prototype avec au moins trois types d'exercices.

#### Séance 13 — Atelier de prototypage III : vers une plateforme

- Structuration en modules conformes au programme MINESEC : un parcours par module.
- Suivi minimal de l'apprenant : profil anonyme, progression, feedback.
- Documentation : README, guide de l'enseignant, guide de l'apprenant.
- Publication du code source sur GitHub, du jeu de données enrichi sur mdc.

#### Séance 14 — Restitution et soutenance

- Démonstration live par chaque équipe : 15 minutes de présentation + 10 minutes de questions.
- Évaluation croisée entre équipes sur une grille commune (pertinence didactique, conformité MINESEC, qualité technique, éthique).
- Bilan du semestre et perspectives : mise en contact avec des enseignants du secondaire pour une expérimentation en 2026-2027.

---

## Méthodologie

- Approche projet : équipes de 3 à 4 élèves-professeurs, une langue ALCAM par équipe, un prototype livré à la fin du semestre.
- Co-rédaction homme-IA : toutes les productions (fiches, exercices, code) sont co-construites avec Claude, puis validées et corrigées par les élèves-professeurs.
- Ancrage institutionnel : conformité stricte aux programmes MINESEC des classes de 6e, 5e, 4e et 3e.
- Science ouverte : code et matériels didactiques publiés sous licence ouverte (CC-BY pour les contenus, MIT ou Apache-2.0 pour le code).

## Évaluation

- **Contrôle continu (30 %)** : devoir sur table en séance 10 ; portée : séances 1 à 9.
- **Projet d'équipe progressif (70 %)** : conception d'un outil didactique numérique pour une langue ALCAM, conforme à un ou deux modules MINESEC.
    - Évaluation de mi-parcours (séance 10, en même temps que le devoir) : deux fiches de séance (6e/5e et 4e/3e), cahier des charges du prototype, maquette papier (20 % des 70 %).
    - Évaluation finale (séance 14) : prototype fonctionnel déployé en ligne, code source public, documentation, soutenance orale, démonstration avec au moins un utilisateur extérieur (80 % des 70 %).

## Catalogue des langues ALCAM disponibles sur mdc

Les équipes choisissent leur langue de référence parmi les 16 jeux de données ALCAM publiés par l'Institut des Humanités numériques africaines :

- Basaa, Ewondo, Bulu, Gbaya, Tikar, Fong, Mvele, Bakossi, Tuki-Tumbele, Tuki-Tukombe, Balom, Badjia, Banoo, Mipa, Yezoum, Diboum.

Pour chaque langue, les équipes disposent : (i) du fichier TSV de phrases ALCAM, (ii) du dossier d'audios MP3, (iii) des traductions françaises embarquées dans le TSV.

## Ressources

- Mozilla Data Collective — Institut des Humanités numériques africaines : <https://mozilladatacollective.com/organization/cmfv3ichk000amd07piai0zoz>
- MINESEC — Programmes des Langues Nationales, classes de 6e et 5e (août 2014).
- MINESEC — Programmes des Langues Nationales, classes de 4e et 3e (décembre 2014).
- Anthropic — Claude : <https://claude.com>
- Documentation Streamlit : <https://docs.streamlit.io>
- Documentation React : <https://react.dev>
- Syllabus pré-requis : Ngue Um, E. (2026). *Technologies vocales pour les langues africaines peu dotées*. <https://github.com/Ngue-Um/syllabi/blob/main/Technologies%20vocales%20pour%20les%20langues%20africaines%20peu%20dot%C3%A9es.md>
- Syllabus complémentaire (Niveau 1, S2) : Ngue Um, E. (2026). *Outils pour la transcription numérique des langues camerounaises*.

## Quelques références indicatives

- MINESEC (2014). *Programmes d'études des classes de 6e et 5e : Langues Nationales*. Yaoundé : Inspection Générale des Enseignements.
- MINESEC (2014). *Programmes d'études des classes de 4e et 3e : Langues Nationales*. Yaoundé : Inspection Générale des Enseignements.
- Tadadjeu, M., & Sadembouo, E. (1979). *Alphabet général des langues camerounaises*. Yaoundé : Université de Yaoundé.
- Ngue Um, E. (2024). *Humanités numériques africaines : vers des plateformes ouvertes pour les langues peu dotées*. Institut des Humanités numériques africaines.
- Dombrowski, Q., Gniady, T., & Kloster, D. (2019). *The Programming Historian*. https://programminghistorian.org — pour l'initiation aux briques techniques.
