# GTA651 — Séance 01 / 15 — L'IA générative et l'ère agentique : orchestrer des experts sans en être un

> Guide de studio (version Markdown). PDF équivalent : `docs/lab-guides/GTA651-01_lab.pdf`.

## En bref

- **Date :** 6 mai 2026
- **Horaire :** 8 h 30 – 11 h 30
- **Lieu :** Sherbrooke
- **Temps estimé :** 150 min (~2.5 h)

## Objectif

Comprendre le changement de paradigme fondamental de l'IA générative : la couche de complexité technique monte, ce qui permet à un gestionnaire d'affaires d'orchestrer des agents spécialisés (développeur, analyste, opérations) sans avoir à être l'un d'eux. Analyser trois déploiements réels — Klarna, GitHub Copilot Enterprise, Morgan Stanley — pour identifier quel rôle spécialisé chaque agent remplace ou augmente. Produire une fiche d'opportunité agentique pour votre propre contexte.

## Résultats d'apprentissage

- Expliquer la trajectoire historique de l'IA (règles → ML → deep learning → génératif → agentique) et ce qui rend le tournant actuel structurellement différent.
- Décrire le paradigme de l'orchestration agentique : la complexité technique est abstraite vers le haut, ce qui donne aux gestionnaires le contrôle de rôles spécialisés via des agents.
- Analyser trois cas réels (Klarna, GitHub Copilot Enterprise, Morgan Stanley) en identifiant pour chacun le rôle spécialisé orchestré et la valeur créée.
- Évaluer un cas d'usage agentique selon des critères de faisabilité, d'impact et de risque.
- Produire une fiche d'opportunité agentique identifiant quel rôle spécialisé un agent pourrait jouer dans une organisation donnée.

## Points clés

- L'IA a traversé 70 ans de cycles hype/désillusion. Un gestionnaire doit savoir où nous en sommes dans le cycle pour investir intelligemment.
- L'IA générative est la première technologie où l'interface est le langage naturel — c'est pourquoi elle transforme les fonctions d'affaires, pas seulement l'IT.
- La complexité technique de l'IA monte vers le haut — vous n'avez plus besoin d'être développeur, analyste ou spécialiste pour diriger un agent qui l'est.
- Klarna : un gestionnaire orchestre 700 agents équivalents. Ce n'est plus une question de recrutement — c'est une question de pilotage.
- GitHub Copilot Enterprise : la barrière entre 'avoir une idée' et 'l'implémenter' s'effondre pour les non-développeurs.
- Morgan Stanley : des décennies d'expertise de recherche, accessibles en secondes par n'importe quel conseiller.
- Le schéma est le même dans les trois cas : le gestionnaire orchestre un rôle spécialisé via un agent au lieu de l'embaucher ou d'en être un.
- Un déploiement agentique viable = problème réel + rôle spécialisé identifié + impact mesurable + risque gérable + humain responsable.

## Idées reçues à déjouer

- **Mythe :** L'IA générative, c'est juste ChatGPT
  **Réalité :** ChatGPT est une interface. L'IA générative est une capacité technologique déployée dans des centaines de systèmes professionnels — agents de service client, outils de développement, assistants d'analyse — souvent invisibles pour l'utilisateur final. Klarna, GitHub Copilot et Morgan Stanley n'utilisent pas "ChatGPT" — ils construisent des agents spécialisés sur des modèles fondationnels.
- **Mythe :** Les agents IA vont remplacer mon emploi immédiatement
  **Réalité :** Les cas que nous étudions montrent le contraire : Klarna a redirigé ses agents humains vers les cas complexes, Morgan Stanley a rendu ses conseillers plus efficaces, Accenture a augmenté la productivité de 12 000 développeurs (GitHub Copilot Enterprise, 2023–2024). Ce qui change, c'est le type de travail qui reste humain : le jugement, la relation, la stratégie. Ce cours vous prépare à être celui qui orchestre les agents, pas celui qui est orchestré.
- **Mythe :** C'est une question technologique, pas stratégique
  **Réalité :** Les décisions stratégiques les plus critiques autour de l'IA agentique ne sont pas techniques : Quel rôle spécialisé dois-je automatiser en premier ? Quelles décisions restent humaines ? Comment mesurer la valeur créée ? Comment gérer les risques d'erreur d'agent ? Ce sont des questions de gestion, pas d'ingénierie.
- **Mythe :** Si Klarna a remplacé 700 agents, on peut tout automatiser
  **Réalité :** Le même Klarna a publiquement réajusté sa stratégie en 2024-2025 : trop de remplacement humain a dégradé la qualité perçue, et l'entreprise rappelle des humains pour les cas à forte valeur (CEO Siemiatkowski, mai 2025). La leçon n'est pas « automatisez moins », mais « le bon niveau d'automatisation est une décision stratégique mesurable, pas un maximum à atteindre ». Les chiffres impressionnants du déploiement initial (2/3 des conversations, −5 % en coûts) restent réels — mais ils doivent être lus avec leur correctif post-déploiement. C'est la marque d'une vraie discipline managériale : assumer publiquement les ajustements.

## Déroulé

### Partie 1 — L'IA générative : de quoi parle-t-on, et où en sommes-nous vraiment ?  *(50 min)*

Sondage d'ouverture : quel spécialiste vous manque ? Définition de l'IA et distinction IA étroite vs IA générale. Repères historiques : 70 ans en 5 minutes — du test de Turing (1950) aux systèmes agentiques (2024+), en passant par les deux hivers de l'IA et les leçons qu'ils portent pour les gestionnaires. Trois paradigmes successifs : règles → ML supervisé → IA générative, avec à chaque fois un élargissement du cercle d'utilisateurs. Définition concrète de l'IA générative (LLM, tokens, pré-entraînement, fine-tuning, prompt engineering). Vocabulaire du gestionnaire : 9 termes clés du trimestre. Pourquoi maintenant : les 3 conditions réunies (calcul, données, interface en langage naturel). De l'automatisation classique (RPA) à l'orchestration agentique. Démonstration live : même tâche, trois outils. Introduction du cas Klarna.

### Partie 2 — Trois agents, trois rôles spécialisés — le même paradigme  *(50 min)*

Analyse des trois cas en séquence, chacun présenté selon la même structure : (1) le problème d'affaires avant l'agent, (2) le rôle spécialisé que l'agent orchestre, (3) la valeur créée mesurée, (4) ce que le gestionnaire fait maintenant que l'agent fait le travail spécialisé. Klarna : 700 agents de service client → le gestionnaire orchestre la capacité plutôt que de la recruter. GitHub Copilot Enterprise chez Accenture : 12 000 développeurs augmentés (67 % usage quotidien, 55 % plus rapide en tâches contrôlées) + gestionnaires non-techniques qui pilotent du code → la barrière idée/implémentation s'effondre. Morgan Stanley : des décennies de recherche accessibles en secondes → le conseiller pilote la stratégie client plutôt que de chercher. Discussion collective sur le schéma commun : dans les trois cas, qu'est-ce que le gestionnaire peut faire maintenant qu'il ne pouvait pas faire avant ?

### Partie 3 — Pause  *(10 min)*

Pause. Afficher l'énoncé de l'exercice à l'écran avant le retour.

### Partie 4 — Exercice : votre fiche d'opportunité agentique  *(40 min)*

Individuellement : choisir UN des trois cas (Klarna, GitHub Copilot Enterprise ou Morgan Stanley), remplir la fiche d'opportunité agentique (6 champs). Questions d'ancrage : quel rôle spécialisé l'agent orchestre-t-il ? Quelle décision le gestionnaire peut-il prendre maintenant qu'il ne pouvait pas prendre avant ? 4-5 étudiants présentent leur fiche en 2 minutes, vote de la classe sur la fiche la plus convaincante. Débrief collectif : quelles conditions rendent un déploiement agentique viable vs risqué ?

## Lab

**Objectif du lab :** Synthétiser les concepts de la séance en identifiant un rôle spécialisé pertinent pour votre futur contexte professionnel.

**Livrable :** 1 paragraphe (texte ou PDF, ½ page max)

**Fichiers à produire (`repo_artifacts`) :**

- `portfolio/L1_reflexion_role_specialise.pdf` — Fiche d'opportunité agentique complétée (6 champs), format PDF ou Markdown

## Remise

- **Échéance :** Mercredi 20 mai 2026, 8 h 30 (avant le début de S02)
- **Artefacts requis :**
  - `portfolio/L1_reflexion_role_specialise.pdf`
  - `ai-usage.md`
- **Rubrique de notation :**
  - **role_specialise** (25 %) — Le rôle spécialisé orchestré est nommé précisément (pas juste « un agent IA »). L'étudiant identifie quel expert humain l'agent remplace ou augmente.
  - **probleme_affaires** (25 %) — Le problème d'affaires est formulé en langage exécutif, pas technique. Le problème est réel et spécifique au contexte choisi.
  - **valeur_creee** (20 %) — La valeur créée est exprimée de manière mesurable ou vérifiable, quantifiée avec des données publiques. L'étudiant fait le lien entre le rôle orchestré et l'impact concret.
  - **risque_mitigation** (15 %) — Le risque principal est identifié clairement et la mitigation proposée est concrète, réaliste et actionnable (pas un voeu pieux).
  - **condition_succes** (10 %) — La condition de succès est formulée pour l'organisation de l'étudiant, pas en termes génériques. Elle est observable et vérifiable.
  - **ai_disclosure** (5 %) — ai-usage.md présent et rempli, même si aucun outil IA n'a été utilisé.

## Lectures

- [Klarna AI — Press Release (2024)](https://www.klarna.com/international/press/klarna-ai-assistant-handles-two-thirds-of-customer-service-chats-in-its-first-month/) — Données officielles sur le déploiement de l'agent de service client Klarna — chiffres utilisés en classe.
- [GitHub — Accenture Copilot Enterprise Case Study](https://github.com/customer-stories/accenture) — Déploiement de GitHub Copilot Enterprise à 50 000 développeurs chez Accenture — productivité et nouveaux usages.
- [McKinsey — The State of AI (2024)](https://www.mckinsey.com/capabilities/quantumblack/our-insights/the-state-of-ai) — Rapport annuel sur l'adoption de l'IA en entreprise — données de benchmark sectorielles.
- [Commission européenne — Loi sur l'IA (résumé exécutif)](https://digital-strategy.ec.europa.eu/en/policies/european-approach-artificial-intelligence) — Cadre réglementaire européen sur l'IA — pertinent pour les déploiements agentiques à risque élevé.

---

*Généré automatiquement à partir de `content/sessions/GTA651-01.yaml`. Pour corriger une coquille, modifiez le YAML source et poussez sur `master` — la CI régénère PDF + Markdown.*
