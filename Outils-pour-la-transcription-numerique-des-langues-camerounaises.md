# Outils pour la transcription numérique des langues camerounaises (LACC1322 — ENS Yaoundé)

**Enseignant** : Prof. Emmanuel Ngue Um
**Institution** : École Normale Supérieure de Yaoundé — Département des Langues et Cultures Camerounaises
**Public** : Élèves-professeurs de Niveau 1
**Année universitaire** : 2025-2026, Semestre 2
**Horaire** : mardi, 10h – 12h
**Volume horaire** : 28 heures (14 séances de 2 heures)
**Évaluation** : Contrôle continu 30 % + Projet personnel progressif 70 %
**Prérequis** : Technologies Linguistiques pour les Langues Africaines (LCC1, S1)

---

## Objectif général

Outiller les élèves-professeurs de langues et cultures camerounaises pour transcrire numériquement les langues camerounaises, depuis la saisie au clavier jusqu'à la transcription assistée par la reconnaissance automatique de la voix (ASR), en s'appuyant sur les ressources publiées sur la plateforme Mozilla Data Collective (mdc) sous la bannière de l'Institut des Humanités numériques africaines.

## Objectifs spécifiques

- Identifier les obstacles à la transcription numérique des langues camerounaises utilisant l'Alphabet général des langues camerounaises (AGLC).
- Installer, configurer et utiliser les principaux claviers virtuels qui prennent en charge les caractères de l'AGLC.
- Comprendre les fondements, l'état de l'art et les limites de la reconnaissance automatique de la voix pour les langues peu dotées.
- Participer activement à la constitution de jeux de données vocales pour les langues camerounaises en contribuant à la plateforme Mozilla Data Collective via l'outil SABRE.
- Documenter et publier un corpus personnel d'enregistrements en langue camerounaise selon les standards ouverts de mdc.

---

## Plan du cours

### Partie I — Aspect liminaire : les claviers virtuels et l'AGLC (3 séances / 6 h)

#### Séance 1 — Introduction générale et cadrage

- Rappel des acquis de LCC1 : technologies linguistiques, corpus, panorama des langues camerounaises.
- Transcription manuelle vs transcription numérique : enjeux pour l'enseignement secondaire.
- Présentation du dispositif du cours, du calendrier, des livrables et des critères d'évaluation.
- Inscription sur la plateforme Mozilla Data Collective : [mdc — Institut des Humanités numériques africaines](https://mozilladatacollective.com/organization/cmfv3ichk000amd07piai0zoz).

#### Séance 2 — L'Alphabet général des langues camerounaises (AGLC)

- Historique de l'AGLC (1979), comité ad hoc, contexte PROPELCA.
- Inventaire des graphèmes vocaliques, consonantiques et suprasegmentaux ; règles d'écriture ; variantes.
- Difficultés typographiques courantes (caractères absents des claviers standard, encodage Unicode).
- Référence : [Alphabet général des langues camerounaises (AGLC) — Wikipédia](https://fr.wikipedia.org/wiki/Alphabet_g%C3%A9n%C3%A9ral_des_langues_camerounaises).
- TP 1 : identifier dans un échantillon de textes ALCAM (Basaa, Ewondo, Bulu, Tikar) les graphèmes AGLC non présents sur un clavier AZERTY standard.

#### Séance 3 — Claviers virtuels I : Gboard (Android) pour l'AGLC

- Principe du clavier virtuel sur smartphone : dispositions, dictionnaires, saisie gestuelle.
- Configuration de Gboard pour la saisie de langues camerounaises : claviers multilingues, raccourcis, dictionnaires personnels.
- Limites et contournements (accents combinants, tons, caractères particuliers `ɛ ɔ ŋ ʉ ɨ`).
- TP 2 : saisir dix phrases-témoins ALCAM sur Gboard dans la langue de référence de chaque élève-professeur.

#### Séance 4 — Claviers virtuels II : Keyman (SIL)

- Historique et philosophie de Keyman : clavier libre, multi-plateforme, orienté langues minoritaires.
- Installation de Keyman sur Windows, macOS, Android et iOS ; choix d'un clavier Keyman pour l'AGLC (claviers `cameroon_aglc`, `sil_cameroon_qwerty`, etc.).
- Création d'une disposition Keyman personnalisée avec Keyman Developer : principes de base.
- TP 3 : installer Keyman, choisir un clavier AGLC et ressaisir les dix phrases-témoins de la séance 3 ; comparer l'ergonomie.

### Partie II — Aspect principal : la reconnaissance automatique de la voix (9 séances / 18 h)

#### Séance 5 — Introduction aux technologies vocales

- Qu'est-ce que la voix numérique ? échantillonnage, spectrogramme, formats audio (wav, flac, mp3).
- Tour d'horizon : ASR (speech-to-text), TTS (text-to-speech), diarisation, wake-word, traduction vocale.
- Cas d'usage pour l'enseignement des langues nationales : transcription automatique des contes, sous-titrage des cours en ligne, évaluation de la prononciation.

#### Séance 6 — État de l'art de l'ASR

- Approches historiques : HMM-GMM, HMM hybrides, DNN.
- Approches contemporaines de bout-en-bout : CTC, attention, transformers.
- Modèles de référence 2020-2026 : DeepSpeech, wav2vec 2.0, Whisper, MMS, XLS-R, SeamlessM4T.
- Métriques d'évaluation : WER, CER, taux d'insertion / substitution / omission.

#### Séance 7 — ASR pour les langues peu dotées

- Définition : langues peu dotées, langues à faibles ressources numériques.
- Rareté des données annotées : causes et conséquences pour l'apprentissage automatique.
- Stratégies : apprentissage par transfert, fine-tuning, auto-apprentissage (self-supervised), multi-tâches, multilingue.
- Focus local : où en sont les langues camerounaises ? Étude des publications récentes.

#### Séance 8 — Visite guidée de Mozilla Data Collective (mdc)

- Présentation de la plateforme Mozilla Data Collective : mission, modèle de gouvernance, licences.
- Exploration de l'espace de l'Institut des Humanités numériques africaines : [mdc/IHNA](https://mozilladatacollective.com/organization/cmfv3ichk000amd07piai0zoz).
- Étude comparée de trois jeux de données publiés par l'enseignant (Basaa, Ewondo, Fong) : structure des fichiers ALCAM, fichiers audio associés, métadonnées.
- TP 4 : chaque élève-professeur ouvre un compte mdc, commente et « like » au moins trois jeux de données de l'IHNA.

#### Séance 9 — Structurer un jeu de données vocales

- Principes FAIR (Findable, Accessible, Interoperable, Reusable) appliqués aux langues.
- Le triptyque ALCAM : phrase cible en langue, traduction française, enregistrement audio.
- Métadonnées minimales : locuteur, sexe, âge, région, langue, dialecte, conditions d'enregistrement.
- Consentement éclairé et éthique de la collecte : charte de l'IHNA.

#### Séance 10 — Devoir sur table (3/4 du cours)

- Épreuve écrite de 2 h portant sur les séances 1 à 9.
- Questions courtes (AGLC, claviers, ASR), question réflexive (langues peu dotées), micro-exercice de transcription.
- Le devoir compte pour 30 % de la note finale.

#### Séance 11 — L'outil SABRE : présentation

- Présentation de SABRE (*Speech Annotation and Basic Recording Environment*) : [SABRE — mdc dataset toolbox](https://mdc-dataset-toolbox-ifuhj.ondigitalocean.app/sabre).
- Architecture fonctionnelle : enregistrement, segmentation, validation, export.
- Workflow conseillé pour atteindre 2 heures d'audio propres.
- TP 5 : création du projet SABRE personnel ; choix de la langue de référence ; enregistrement-test de 5 minutes.

#### Séance 12 — Atelier SABRE I : enregistrement supervisé

- Préparation du locuteur : protocole de consentement, script, environnement calme, matériel.
- Techniques de lecture : débit, intonation, reprise, corrections à chaud.
- Validation au fil de l'eau : écoute de retour, étiquetage, annotation.
- Objectif à l'issue de la séance : chaque élève-professeur doit avoir accumulé **au moins 45 minutes d'audio validé**.

#### Séance 13 — Atelier SABRE II : contrôle qualité et enrichissement

- Revue qualitative du corpus : détection des segments inutilisables, ré-enregistrement.
- Enrichissement : ajout de transcriptions AGLC, traduction française, notes de prononciation.
- Export et dépôt sur mdc (espace personnel ou espace de l'IHNA).
- Objectif : porter chaque corpus à **2 heures d'audio validé**, conforme aux exigences de mdc.

#### Séance 14 — Restitution et soutenance

- Présentation par chaque élève-professeur de son corpus : 10 minutes de présentation + 5 minutes de questions.
- Retour d'expérience : difficultés rencontrées, choix du corpus source, enseignements.
- Publication officielle des corpus sur mdc sous licence ouverte (CC-BY ou CC-BY-SA selon choix du locuteur).

---

## Méthodologie

- Approche pratique : chaque séance combine apport théorique (30 min) et TP (1 h 30), sauf les séances 6-7 à dominante théorique et 10 (évaluation).
- Focus local : les exemples, exercices et corpus sont pris dans les 16 langues ALCAM déjà publiées sur mdc, au choix de chaque élève-professeur selon sa langue maternelle ou de référence.
- Interdisciplinarité : linguistique, didactique, informatique, éthique des données.
- Science ouverte : tous les livrables étudiants sont publiés sous licence ouverte, au bénéfice de la communauté.

## Évaluation

- **Contrôle continu (30 %)** : devoir sur table en séance 10 ; portée : séances 1 à 9.
- **Projet personnel progressif (70 %)** : constitution d'un corpus de **2 heures d'audio** en langue camerounaise via SABRE, publié sur mdc sous la bannière de l'Institut des Humanités numériques africaines.
    - Évaluation de mi-parcours (séance 10, en même temps que le devoir) : avancement technique, choix de langue, qualité des premiers enregistrements (20 % des 70 %).
    - Évaluation finale (séance 14) : volume effectif (≥ 2 h), qualité sonore, pertinence de la transcription AGLC, exhaustivité des métadonnées, soutenance orale (80 % des 70 %).

## Catalogue des langues ALCAM disponibles sur mdc

Les élèves-professeurs peuvent choisir leur langue de référence dans les 16 jeux de données ALCAM déjà publiés par l'Institut des Humanités numériques africaines sur mdc :

- Basaa, Ewondo, Bulu, Gbaya, Tikar, Fong, Mvele, Bakossi, Tuki-Tumbele, Tuki-Tukombe, Balom, Badjia, Banoo, Mipa, Yezoum, Diboum.

## Ressources

- Mozilla Data Collective — Institut des Humanités numériques africaines : <https://mozilladatacollective.com/organization/cmfv3ichk000amd07piai0zoz>
- SABRE — Speech Annotation and Basic Recording Environment : <https://mdc-dataset-toolbox-ifuhj.ondigitalocean.app/sabre>
- Alphabet général des langues camerounaises : <https://fr.wikipedia.org/wiki/Alphabet_g%C3%A9n%C3%A9ral_des_langues_camerounaises>
- Keyman (SIL Global) : <https://keyman.com>
- Gboard (Google Android) : <https://support.google.com/gboard>
- Ministère des Enseignements Secondaires du Cameroun — Programmes de Langues Nationales (6e / 5e et 4e / 3e).
- Syllabus pré-requis : Ngue Um, E. (2025). *Technologies Linguistiques pour les Langues Africaines*. <https://github.com/Ngue-Um/syllabi/blob/main/Technologies-linguistiques-pour-les-langues-africaines.md>

## Quelques références indicatives

- Baevski, A., Zhou, H., Mohamed, A., & Auli, M. (2020). wav2vec 2.0: A Framework for Self-Supervised Learning of Speech Representations. *NeurIPS*.
- Radford, A., et al. (2022). Robust Speech Recognition via Large-Scale Weak Supervision (Whisper). *arXiv:2212.04356*.
- Pratap, V., et al. (2023). Scaling Speech Technology to 1000+ Languages (MMS). *Meta AI*.
- Tadadjeu, M., & Sadembouo, E. (1979). *Alphabet général des langues camerounaises*. Yaoundé : Université de Yaoundé.
- Ngue Um, E. (à paraître). *Humanités numériques et langues africaines : enjeux de la constitution de corpus vocaux ouverts*.
