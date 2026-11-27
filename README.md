# CA5 Course en durée – N'EPS numérique

PWA de course en durée en EPS (champ d'apprentissage 5 : « Réaliser et orienter son activité physique pour développer ses ressources et s'entretenir »).
Emilie BIDAULT et Quentin DELISLE. L'application reprend tout le modèle « CA1 Demi-fond – N'EPS numérique » et y ajoute les données propres au CA5.

**Fonctions reprises de Demi-fond :**
- chrono, saisie des plots, contrats d'allure, VMA ;
- barème et pénalités (marche, arrêt, changement de rythme) ;
- piste en anneau ou couloir aller-retour ;
- tests VMA, jeux, piliers ;
- synthèse, historique, fiches PDF.

**Ajouts CA5 :**
- thèmes d'entraînement et zones d'intensité ;
- fréquence cardiaque et ressentis ;
- bilans de séance et régulation ;
- carnet d'entraînement ;
- évaluation bac GT, bac pro et CAP.

## Mise en ligne
L'installation et le mode hors connexion demandent une adresse **https**.

- **La Forge (GitLab Pages)** : déposez ce dossier à la racine d'un dépôt. Le fichier `.gitlab-ci.yml` publie le site à chaque envoi sur la branche principale.
- **Netlify Drop** : glissez le dossier sur https://app.netlify.com/drop.
- **GitHub Pages** ou serveur de l'établissement en https : déposez le dossier tel quel.

Installation :
- **iPad** : Safari → Partager → « Sur l'écran d'accueil ».
- **Android** : Chrome → bouton « 📲 Installer », ou menu ⋮ → « Installer l'application ».

Ouvrez l'application une première fois avec une connexion. Elle fonctionne ensuite hors connexion, et les données restent sur chaque appareil.

Les données et les QR de cette application sont séparés de ceux de l'appli Demi-fond : les deux peuvent être installées sur la même tablette.

## Rôle de chaque tablette
Au premier lancement, choisissez **Tablette enseignant** (code **0000** par défaut) ou **Tablette élève**. Le bouton 🔒 verrouille l'espace enseignant.

## Parcours enseignant (8 étapes, comme Demi-fond)
Ce qui est propre au CA5 est indiqué en **gras**.
1. **Préparer le cycle** :
   - classes, piste (anneau ou couloir) et plots ;
   - **courses proposées d'après le livret** : L2 Entretien 3 × 10 min, L3 Forme 3 × (6 min + 3 min), L4 Sportif 5 × 1' · 5 × 2' · 5 × 1', L5-L7 « Ma séance » à l'allure du thème de l'élève, épreuves types 20 min, 1500 m et 400 m ;
   - **🎯 thèmes Entretien, Forme et Sportif** : % de VMA, FC d'entraînement (Karvonen), ressentis attendus, caractéristiques de l'entraînement ;
   - **échelles de ressentis au choix** : Borg 0-10, perception de l'effort, ressenti cardio-pulmonaire, ressenti musculaire, test de la parole ;
   - **réglages de la FC** : prise sur 6 s, 15 s, 30 s ou cardio ; FC max 220 − âge (G) / 226 − âge (F) ;
   - barème et pénalités (marche, **plot non atteint au signal ou attente au plot plus de 2 s**, changement de rythme ; tout est modifiable) ;
   - signaux sonores (**annonce de chaque minute activée par défaut**) ;
   - cycle et **piliers d'après les points d'attention du livret** ;
   - séquence.
2. **Piliers & maîtrise** (échauffement, respiration, placement, engagement, allure, passages aux balises, entraînement adapté au thème, récupération ; analyse, bilan et coopération en option) : positionner, auto et co-évaluation, comparaison élèves / enseignant, suivi, **❤️ FC & ressentis** (grille par période), **🔍 bilans & régulation** (charge, conseil, décision de l'élève), évaluation de fin de cycle **avec les référentiels CA5**.
3. **Projet de course** : contrats des élèves, **🎯 thème d'entraînement de chaque élève** (allure, plots/min, FC cible, objectif), projet de l'élève, calculateur d'allure, table % VMA. Le contrat par défaut de l'élève devient l'allure de son thème (option désactivable).
4. **Entraînement du jour** : chrono, tuiles (+1 plot, soucoupe, marche / arrêt / rythme), **❤️ FC et 💬 ressenti sur chaque tuile**.
5. **Tests VMA** : demi-Cooper, VAMEVAL, Luc Léger, Gacon 45/15, **❤️ FC de repos, FC max et Ruffier-Dickson**.
6. **Jeux** : Zombie Frac', Gare aux loups, Run Express, Kart'Endurance (inchangés, à adapter).
7. **Résultats et bilans** : synthèse, toutes les courses, historique, **📓 carnet d'entraînement** (graphiques allure, FC, charge, ressenti ; vue de la classe ; carnets PDF), fiches PDF, CSV, sauvegarde, code.
8. **Tablettes élèves** : QR de la séance (classe ou équipe) et récupération des saisies. Les thèmes, FC, ressentis et bilans circulent avec les plots.

## Tablette élève
Mêmes écrans que Demi-fond, avec deux boutons en plus :
- **🎯 Mon thème d'entraînement** : choix du thème, de l'allure et de l'objectif, âge et FC de repos ;
- **❤️ Mon bilan et mon carnet** : périodes, FC 1 min après, effort de la séance, fatigue, plaisir, décision pour la prochaine séance, carnet.

## Repères CA5 utilisés
- **FC max** : 208 − 0,7 × âge (Tanaka), 220 − âge, ou FC max mesurée.
- **Zone cardiaque** : FC repos + % × (FC max − FC repos), méthode de Karvonen.
- **Charge de séance** : effort perçu (0-10) × minutes d'effort, méthode de Foster.
- **Récupération** : baisse de la FC en 1 min. Repères indicatifs : 30 et plus = très bonne, 20 à 29 = bonne, 12 à 19 = moyenne, moins de 12 = à améliorer.

## Évaluation
Modèles prêts à l'emploi, uniquement CA5 :
- **Lycée GT · CA5 (AFL)** : AFL1 = Produire /8 + Analyser /4, d'après les repères du livret ;
- **Bac pro · CA5 (AFLP)** ;
- **CAP · CA5 (AFLP)**.

Pour chaque modèle, 12 points correspondent à l'épreuve de fin de séquence. Les 8 autres points portent sur 2 éléments au choix, et l'élève choisit la répartition 4/4, 6/2 ou 2/6.

Les descripteurs des degrés sont des propositions. Dans les intitulés officiels, le mot « mobile » a été remplacé par « thème d'entraînement ». Tout se modifie dans Piliers & maîtrise → Évaluation de fin de cycle → Grille d'évaluation.

## Nouveautés version 1.2
- Écran de course (élève et enseignant) : plus de liste des courses, un simple menu déroulant « ⏱ Course ».
- Courses de départ : deux courses modèles (continue 2 × 12 min, fractionnée 6 × 3 min) et les trois épreuves ; les leçons proposées sont retirées (une course déjà saisie dans une vraie classe est conservée).
- Les modèles de course sont sous les réglages de la course.
- L'allure selon le thème d'entraînement se coche dans les réglages de chaque course (bloc « Pendant la course »), et n'est plus dans 🎯 Thèmes.
- Anciens iPad : fenêtres (code enseignant…) et espacements corrigés pour Safari 11 à 14.

## Nouveautés version 1.1
- **Anciens iPad** : le code est converti pour Safari 11 et plus (iOS 11 à 15), avec les fonctions récentes ajoutées si elles manquent.
- **Classes & élèves** : date de naissance (âge et FC max calculés), FC de repos, FC max mesurée, test de Ruffier-Dickson facultatif. Import CSV : colonnes `Naissance` et `FC repos` reconnues.
- **Demi-Cooper** : saisie en *tours + plots* (par défaut) ou au plot d'arrêt numéroté ; l'affichage indique toujours tours et plots.
- **Veille** : l'écran reste allumé tant qu'un chrono tourne (Wake Lock, ou vidéo muette sur iPad) ; les chronos des tests suivent l'horloge réelle.
- **Modèles de course** : enregistrer une course comme modèle, créer une course depuis un modèle ; dans la Séquence, ajouter une course depuis un modèle et revenir la modifier.
- **Luc Léger** : protocole test 6e ou Léger 1988, bips calés sur l'horloge audio, annonce vocale du palier, import de la bande son officielle, tableau d'équivalences (navettes, distance, VO2max, demi-Cooper).

## Mise à jour
Remplacez les fichiers, puis changez `VERSION` dans `sw.js` (par exemple `course-duree-v6`). Les données sont conservées.

## Crédits
Certaines idées pédagogiques (tests VMA, Bats tes perfs, fractionnés, course d'équipe, pelotons et jokers) s'inspirent de l'application « Demi-fond N'EPS » de Quentin Delisle.
