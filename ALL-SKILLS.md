# Industrie du Maroc — Toutes les Compétences

**Accès rapide:** github.com/nizarezz/idm-skills

---

## Table des matières

1. [Fact Checker](#1-fact-checker)
2. [Source Verification](#2-source-verification)
3. [AI Writing Detox](#3-ai-writing-detox)
4. [Newsroom Style](#4-newsroom-style)
5. [Story Angle Finder](#5-story-angle-finder)
6. [Article Builder](#6-article-builder)
7. [Interview Prep](#7-interview-prep)
8. [Pre-Publication Review](#8-pre-publication-review)
9. [Newsletter Builder](#9-newsletter-builder)
10. [Content Repurposer](#10-content-repurposer)
11. [Social Media Publisher](#11-social-media-publisher)
12. [Press Release Analyzer](#12-press-release-analyzer)
13. [Editorial Translation](#13-editorial-translation)
14. [PDF Media Kit Builder](#14-pdf-media-kit-builder)
15. [Presentation Builder](#15-presentation-builder)

---

## Comment utiliser

1. Copiez la compétence ci-dessous
2. Collez-la dans ChatGPT, Claude, ou tout autre assistant IA
3. Ajoutez votre texte, données, ou questions
4. L'IA appliquera la compétence à votre travail

---

# COMPÉTENCES ÉDITORIALES

---

## 1. Fact Checker

**À quoi ça sert:** Vérifier systématiquement les affirmations factuelles avant publication.

**Quand l'utiliser:**
- Avant de publier un article contenant des chiffres
- Vérifier les déclarations de dirigeants industriels
- Contrôler les statistiques gouvernementales
- Valider les données de production, d'investissement ou d'emploi

**Comment l'utiliser:**
```
Utilise le fact-checker pour vérifier: [votre affirmation ici]
```

**Sources marocaines à consulter:**
- HCP (Haut-Commissariat au Plan) — hcp.ma
- ONPIMC — onpimc.org
- AMIF — amif.ma
- ONHYM — onhym.ma
- Ministère de l'Industrie — mi.gov.ma

**Sortie attendue:**
- Affirmation extraite et classifiée
- Sources primaires consultées
- Niveau de vérification (Vrai, Plutôt vrai, Mi-vrai, Plutôt faux, Faux, Faux grotesque)
- Modèle de correction trilingue

**Le skill complet:** github.com/nizarezz/idm-skills/blob/main/core-editorial/fact-checker/SKILL.md

---

## 2. Source Verification

**À quoi ça sert:** Évaluer si une source est fiable et digne de confiance.

**Quand l'utiliser:**
- Recevoir une information d'un source inconnue
- Évaluer un communiqué de presse d'une entreprise
- Vérifier la crédibilité d'un expert interviewé
- Déterminer si une source secondaire est utilisable

**Comment l'utiliser:**
```
Évalue cette source: [description ou lien de la source]
```

**Sortie attendue:**
- Score de fiabilité (1-10)
- Type de source (primaire, secondaire, tertiaire)
- Biais potentiels identifiés
- Recommandation d'utilisation

**Le skill complet:** github.com/nizarezz/idm-skills/blob/main/core-editorial/source-verification/SKILL.md

---

## 3. AI Writing Detox

**À quoi ça sert:** Éliminer les tics de langage de l'IA dans un texte rédigé.

**Quand l'utiliser:**
- Réviser un texte généré par ChatGPT, Claude ou autre IA
- Nettoyer un texte avant publication
- Supprimer les mots interdits en français, arabe et anglais
- Rendre un texte plus naturel et journalistique

**Mots interdits en français:**
- « Dans le paysage »
- « En tant que »
- « Joue un rôle crucial »
- « De pointe »
- « Optimiser »
- « Levier »
- « Synergie »
- « Panorama »

**Comment l'utiliser:**
```
Nettoie ce texte avec le ai-writing-detox: [coller votre texte]
```

**Sortie attendue:**
- Liste des mots interdits trouvés
- Remplacements suggérés
- Texte nettoyé
- Score de naturalité

**Le skill complet:** github.com/nizarezz/idm-skills/blob/main/core-editorial/ai-writing-detox/SKILL.md

---

## 4. Newsroom Style

**À quoi ça sert:** Appliquer le style éditorial d'Industrie du Maroc à un texte.

**Quand l'utiliser:**
- Rédiger un nouvel article
- Réviser un texte existant pour le conformer au style IDM
- Vérifier la ponctuation, les majuscules, l'orthographe des noms marocains

**Règles clés:**
- Ponctuation française (deux points, guillemets français « »)
- Majuscules aux institutions marocaines (ONPIMC, HCP, Ministère de l'Industrie)
- Noms arabes en caractères arabes + translittération
- Abréviations: ONPIMC, HCP, AMIF, ONEE, MASEN, etc.

**Comment l'utiliser:**
```
Applique le style newsroom IDM à ce texte: [coller votre texte]
```

**Sortie attendue:**
- Texte reformulé selon le style IDM
- Liste des corrections apportées
- Suggestions d'amélioration

**Le skill complet:** github.com/nizarezz/idm-skills/blob/main/core-editorial/newsroom-style/SKILL.md

---

## 5. Story Angle Finder

**À quoi ça sert:** Trouver des angles éditoriaux pour un sujet donné.

**Quand l'utiliser:**
- Débuter la couverture d'un nouveau secteur industriel
- Trouver une approche originale pour un sujet traité par d'autres médias
- Générer des idées pour un dossier thématique
- Préparer un pitch à la rédaction

**Comment l'utiliser:**
```
Trouve des angles éditoriaux sur [votre sujet]
```

**Exemple:**
```
Trouve des angles sur l'industrie textile marocaine après les accords de libre-échange
```

**Sortie attendue:**
- 6-8 angles éditoriaux structurés
- Pour chaque angle: titre, accroche, sources potentielles, cible lecteur
- Différenciation par rapport aux concurrents

**Le skill complet:** github.com/nizarezz/idm-skills/blob/main/core-editorial/story-angle-finder/SKILL.md

---

## 6. Article Builder

**À quoi ça sert:** Construire un article structuré à partir de notes et de recherches.

**Quand l'utiliser:**
- Rédiger un article à partir de vos prises de notes
- Structurer un dossier complexe
- Transformer des informations brutes en texte publication
- Créer un article de fond ou une analyse sectorielle

**Comment l'utiliser:**
```
Construis un article avec l'article-builder: [coller vos notes et informations]
```

**Sortie attendue:**
- Article structuré avec titres et sous-titres
- Introduction, développement, conclusion
- Citations intégrées
- Sources listées

**Le skill complet:** github.com/nizarezz/idm-skills/blob/main/core-editorial/article-builder/SKILL.md

---

## 7. Interview Prep

**À quoi ça sert:** Préparer une interview d'un dirigeant industriel ou institutionnel.

**Quand l'utiliser:**
- Avant d'interviewer un PDG, DG ou responsable ministériel
- Préparer des questions ciblées par secteur
- Anticiper les réponses et préparer des relances

**Comment l'utiliser:**
```
Prépare une interview avec l'interview-prep: [nom de la personne, poste, secteur]
```

**Sortie attendue:**
- Profil de l'interviewé (recherche web)
- 10-15 questions organisées par thème
- Questions de relance
- Points de vérification post-interview

**Le skill complet:** github.com/nizarezz/idm-skills/blob/main/core-editorial/interview-prep/SKILL.md

---

## 8. Pre-Publication Review

**À quoi ça sert:** Revue finale structurée avant publication.

**Quand l'utiliser:**
- 24 heures avant la publication
- Revue de dernière minute par l'éditeur
- Vérification complète avant un numéro spécial

**Ce que vous vérifiez (3 couches):**
1. **Couche 1:** Faits et chiffres (noms, titres, données)
2. **Couche 2:** Style et rédaction (ponctuation, grammaire, ton)
3. **Couche 3:** Légal et éthique (droit de réponse, diffamation, sources)

**Comment l'utiliser:**
```
Revue pré-publication avec le pre-publication-review: [coller l'article]
```

**Sortie attendue:**
- Liste de contrôle complète (150+ points)
- Erreurs classifiées par criticité (Critique/Élevée/Moyenne/Basse)
- Recommandations spécifiques avec corrections

**Le skill complet:** github.com/nizarezz/idm-skills/blob/main/core-editorial/pre-publication-review/SKILL.md

---

# OUTILS EMPLOYÉS

---

## 9. Newsletter Builder

**À quoi ça sert:** Créer des newsletters B2B professionnelles pour l'industrie.

**Quand l'utiliser:**
- Préparer la newsletter hebdomadaire IDM
- Créer un bulletin sectoriel pour les abonnés
- Synthétiser l'actualité industrielle de la semaine

**Contenu types:**
- Titre accrocheur (60 caractères max)
- Résumé exécutif (3-4 bullet points)
- Sections par secteur (Automobile, Mines, Énergie, etc.)
- Événements à venir
- Appel à l'action

**Comment l'utiliser:**
```
Crée une newsletter avec le newsletter-builder: [sujets à couvrir cette semaine]
```

**Le skill complet:** github.com/nizarezz/idm-skills/blob/main/employee-tools/newsletter-builder/SKILL.md

---

## 10. Content Repurposer

**À quoi ça sert:** Transformer un article en formats multiples.

**Quand l'utiliser:**
- Adapter un article long en contenu social media
- Créer un résumé pour la newsletter
- Générer des extraits pour LinkedIn, Twitter, Instagram
- Préparer un script vidéo court

**Formats disponibles:**
- Fil Twitter/X (5-8 tweets)
- Post LinkedIn professionnel
- Carrousel Instagram (5 slides)
- Script vidéo YouTube (2 minutes)
- Résumé newsletter (150 mots)

**Comment l'utiliser:**
```
Réutilise cet article avec le content-repurposer: [coller l'article ou lien]
```

**Le skill complet:** github.com/nizarezz/idm-skills/blob/main/employee-tools/content-repurposer/SKILL.md

---

## 11. Social Media Publisher

**À quoi ça sert:** Créer du contenu optimisé pour les réseaux sociaux professionnels.

**Quand l'utiliser:**
- Publier un article sur LinkedIn
- Créer un fil Twitter/X
- Annoncer un événement industriel
- Partager une analyse sectorielle

**Plateformes supportées:**
- LinkedIn (posts, articles longs, newsletters)
- Twitter/X (fils, threads)
- Instagram (carrousels, stories)

**Comment l'utiliser:**
```
Prépare du contenu social avec le social-media-publisher: [sujet ou article]
```

**Le skill complet:** github.com/nizarezz/idm-skills/blob/main/employee-tools/social-media-publisher/SKILL.md

---

## 12. Press Release Analyzer

**À quoi ça sert:** Analyser et évaluer un communiqué de presse reçu.

**Quand l'utiliser:**
- Recevoir un communiqué d'entreprise
- Décider si le sujet mérite couverture
- Identifier les claims à vérifier
- Préparer un pitch basé sur le communiqué

**Analyse fournie:**
- Résumé exécutif (3 phrases)
- Claims factuels à vérifier
- Score d'actualité (1-10)
- Angle suggéré pour IDM
- Sources additionnelles à consulter

**Comment l'utiliser:**
```
Analyse ce communiqué avec le press-release-analyzer: [coller le communiqué]
```

**Le skill complet:** github.com/nizarezz/idm-skills/blob/main/employee-tools/press-release-analyzer/SKILL.md

---

## 13. Editorial Translation

**À quoi ça sert:** Traduire du contenu entre français, arabe et anglais avec terminologie industrielle.

**Quand l'utiliser:**
- Traduire un article d'une langue à une autre
- Adapter un communiqué de presse international
- Préparer une version multilingue d'un dossier
- Vérifier la cohérence terminologique trilingue

**Langues:**
- Français ↔ Arabe
- Français ↔ Anglais
- Arabe ↔ Anglais

**Règles de traduction:**
- Noms propres marocains: arabe + translittération
- Institutions: noms officiels trilingues (voir IDM-TERMINOLOGY.md)
- Unités: conversions précises (DH/EUR/USD, tonnes/kWh, etc.)
- Pas de traduction littérale des concepts techniques

**Comment l'utiliser:**
```
Traduis cet article en arabe avec le editorial-translation: [coller l'article]
```

**Le skill complet:** github.com/nizarezz/idm-skills/blob/main/employee-tools/editorial-translation/SKILL.md

---

# OUTILS DE PRODUCTION

---

## 14. PDF Media Kit Builder

**À quoi ça sert:** Créer des documents PDF professionnels et brandés.

**Quand l'utiliser:**
- Créer un dossier de presse
- Préparer une présentation sectorielle
- Générer un rapport annuel condensé
- Produire une fiche technique entreprise

**Types de documents:**
- Dossier de presse (communiqué + photos + contacts)
- Fiche entreprise (profil, données financières, contacts)
- Rapport sectoriel (statistiques, tendances, prévisions)
- Présentation événement (programme, intervenants, logistique)

**Couleurs IDM:**
- Bleu principal: #003366
- Bleu secondaire: #0066CC
- Or: #CC9900
- Gris foncé: #333333

**Comment l'utiliser:**
```
Crée un PDF avec le pdf-media-kit-builder: [type de document et contenu]
```

**Le skill complet:** github.com/nizarezz/idm-skills/blob/main/production/pdf-media-kit-builder/SKILL.md

---

## 15. Presentation Builder

**À quoi ça sert:** Créer des présentations HTML professionnelles.

**Quand l'utiliser:**
- Créer des rapports sectoriels avec visualisation de données
- Construire des profils d'entreprise
- Concevoir des supports d'événement
- Préparer des présentations pour l'équipe éditoriale

**Workflow en 6 étapes:**
1. Définir les besoins (public, contenu, style)
2. Rechercher les données (sources marocaines)
3. Créer le plan (structure pyramidale)
4. Planifier le contenu (cartes par diapositive)
5. Générer le design (HTML avec couleurs IDM)
6. Post-traitement (preview, export)

**Couleurs IDM:**
- Bleu principal: #003366
- Bleu secondaire: #0066CC
- Or: #CC9900

**Comment l'utiliser:**
```
Crée une présentation sur [sujet] avec le presentation-builder
```

**Le skill complet:** github.com/nizarezz/idm-skills/blob/main/production/presentation-builder/SKILL.md

---

# WORKFLOWS

---

## Workflow Article Complet

```
1. Story Angle Finder → Trouver l'angle
2. Interview Prep → Préparer les interviews
3. [Conduire les interviews]
4. Article Builder → Rédiger l'article
5. AI Writing Detox → Nettoyer le texte
6. Newsroom Style → Appliquer le style IDM
7. Fact Checker → Vérifier les claims
8. Pre-Publication Review → Revue finale
9. Publication
```

## Workflow Social Media

```
1. Article publié → 2. Content Repurposer → 3. Social Media Publisher
```

## Workflow Multilingue

```
1. Article en français → 2. Editorial Translation → 3. Version arabe
4. Editorial Translation → 5. Version anglaise
6. Pre-Publication Review → 7. Publication trilingue
```

## Workflow PDF & Présentation

```
1. Article final → 2. PDF Media Kit Builder → 3. PDF brandé
                     ↓
4. Presentation Builder → 5. Présentation HTML
```

---

# SOURCES DE DONNÉES MAROCAINES

---

| Source | Données | Site |
|--------|---------|------|
| **HCP** | Statistiques industrielles, emploi, PIB | hcp.ma |
| **ONPIMC** | Commerce extérieur, exportations/importations | onpimc.org |
| **AMIF** | Investissements étrangers | amif.ma |
| **ONHYM** | Hydrocarbures, mines, énergies renouvelables | onhym.ma |
| **MASEN** | Énergie solaire et renouvelable | masen.ma |
| **ONEE** | Électricité et eau | onee.ma |
| **CRI** | Investissements | cri.ma |
| **Ministère de l'Industrie** | Politiques, réglementations | mi.gov.ma |
| **CNSS** | Sécurité sociale, emplois déclarés | cnss.ma |
| **EXTT (Office des Changes)** | Statistiques de commerce extérieur | extt.ma |

---

# AIDE

---

**Problème avec une compétence?**
- Vérifiez que le lien GitHub est correct: `github.com/nizarezz/idm-skills`
- Contactez l'équipe éditoriale IDM

**Compétence manquante?**
- Les compétences sont régulièrement mises à jour
- Suggérez une nouvelle compétence à l'équipe technique

---

*Industrie du Maroc Magazine — Compétences IA*
*Version 1.0.0 — 13 juillet 2026*
