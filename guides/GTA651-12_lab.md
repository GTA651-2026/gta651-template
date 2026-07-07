# GTA651 — Séance 12 / 15 — Éthique de l'IA : biais, transparence et gouvernance

> Guide de studio (version Markdown). PDF équivalent : `docs/lab-guides/GTA651-12_lab.pdf`.

## En bref

- **Date :** 8 juillet 2026
- **Horaire :** 8 h 30 – 11 h 30
- **Lieu :** Sherbrooke
- **Mode :** Studio
- **Temps estimé :** 150 min (~2.5 h)

## Objectif

Analyser les enjeux éthiques réels de l'IA en entreprise à partir des cas étudiés. Goldman Sachs, Citibank et Pfizer opèrent tous dans des secteurs réglementés — comment construisent-ils la confiance ? Produire un audit éthique simplifié.

## Résultats d'apprentissage

- Identifier les sources de biais dans les systèmes IA réels (données de Goldman Sachs biaisées vers certains marchés, données historiques de Citibank excluant les crises inédites).
- Évaluer l'impact des biais IA sur les parties prenantes en contexte financier et pharmaceutique.
- Concevoir un cadre de gouvernance IA incluant transparence, équité et responsabilité, inspiré des pratiques de Pfizer.
- Produire un audit éthique simplifié d'un système IA réel.

## Points clés

- Goldman Sachs Apple Card : l'agent reproduit et amplifie les inégalités historiques des données — sans intention.
- Pfizer Charlie : la gouvernance 'by design' coûte moins cher à long terme que la correction après scandale.
- Le biais IA n'est pas un bug — c'est un miroir des inégalités sociétales codées dans les données.
- Pour certains systèmes, la Loi 25 (Québec) et l'AI Act (UE) imposent transparence, révisabilité et surveillance humaine proportionnelle au risque.
- Un cadre de gouvernance efficace : audit régulier, comité d'éthique, métriques d'équité, recours, formation continue.
- Conformité = plancher. La gouvernance éthique va au-delà de ce qui est légalement requis.

## Idées reçues à déjouer

- **Mythe :** Le biais IA est causé par des développeurs malveillants
  **Réalité :** La plupart des biais IA émergent involontairement, encodés dans les données historiques qui reflètent des inégalités sociales passées. Personne chez Goldman n'a programmé la discrimination de genre — l'agent l'a apprise des données. C'est précisément ce qui rend la prévention difficile : il faut auditer les données et les sorties, pas seulement le code.
- **Mythe :** Une IA transparente = une IA explicable techniquement
  **Réalité :** La transparence agentique a deux niveaux : technique (comment le modèle décide) et opérationnelle (qui peut auditer, qui est responsable, comment recourir). Pour les régulateurs et le public, la transparence opérationnelle compte plus que la transparence technique. Goldman a échoué sur les deux niveaux.
- **Mythe :** Conformité réglementaire = comportement éthique
  **Réalité :** La conformité est un plancher, pas un plafond. Un système conforme à la Loi 25 peut encore être éthiquement problématique (par exemple discrimination indirecte non mesurée). La gouvernance éthique va au-delà de la conformité : audits proactifs, comité d'éthique, dialogue avec les parties prenantes affectées.

## Déroulé

### Partie 0 — Vignettes d'ouverture : la gouvernance à l'échelle individuelle  *(10 min)*

Lecture rapide des deux vignettes (Farid : surveillance vibratoire ; Aminata : calcul structurel). Sondage Moodle instantané : 'Qui est responsable de la panne de Farid ?' (stagiaire / outil IA / organisation). Révélation et transition : 'Même mécanique, même cause fondamentale que Goldman Sachs — absence d'une porte de gouvernance. C'est le fil conducteur de cette séance.'

### Partie 1 — Apple Card : allégations, enquête NY-DFS et leçons de gouvernance  *(40 min)*

Chronologie des allégations Apple Card 2019–2021 (tweets Steve Wozniak, enquête NY-DFS, conclusion mars 2021). Décortiquer l'anatomie du biais : source probable (données historiques), variable proxy (historique de crédit conjoint), amplification par l'agent. Taxonomie des biais agentiques : biais des données, biais de conception, biais de déploiement, biais d'interprétation. Coûts réputationnels malgré absence de sanction légale. Lien explicite avec Farid : 'même mécanique, autre échelle.'

### Partie 2 — Pfizer : gouvernance by design  *(50 min)*

Comment Charlie intègre l'éthique dès la conception : catégorisation par risque, revue humaine obligatoire à seuil, audit trail, comité d'éthique IA. Cadres réglementaires pertinents : Loi 25 (Québec, transparence et révisabilité pour décisions exclusivement automatisées), AI Act (UE, surveillance humaine proportionnelle au risque), Principes OCDE. Contraste Goldman vs Pfizer : prévention coûteuse vs réaction très coûteuse.

### Partie 3 — Pause  *(10 min)*

Pause. Distribuer la grille d'audit éthique pour préparer l'exercice.

### Partie 4 — Exercice : audit éthique  *(40 min)*

Individuel : remplir la grille d'audit pour Goldman, Pfizer, Farid, Aminata, ou un agent du milestone personnel. Le template est disponible sur Moodle. Partage en paires (5 min chacun) avec critique sur : sources de biais plausibles ? Cadre de gouvernance opérationnel ? Référence réglementaire correcte ? 2-3 partages au groupe.

## Lab

**Objectif du lab :** Produire un audit éthique simplifié d'un agent (Goldman, Pfizer, ou agent personnel) avec sources de biais, parties prenantes, gouvernance recommandée et référence réglementaire opérationnelle.

**Livrable :** Grille d'audit éthique (1.5 page)

## Remise

- **Échéance :** Avant la séance 10 (15 juillet 2026, 8 h 00)
- **Artefacts requis :**
  - `GTA651_S09_audit-ethique_CIP.pdf (déposé sur Moodle)`
  - `GTA651_S09_ai-usage_CIP.md (déposé sur Moodle)`
- **Rubrique de notation :**
  - **sources_biais_identifiees** (25 %) — Sources plausibles dans les données, le modèle ou le déploiement.
  - **parties_prenantes_cartographiees** (15 %) — Impact différentiel sur chaque partie prenante explicité.
  - **gouvernance_operationnelle** (25 %) — 5 points opérationnels (pas de vœux pieux).
  - **reference_reglementaire** (15 %) — Au moins 1 cadre réglementaire correctement référencé.
  - **distinction_ex_ante_ex_post** (10 %) — Distinction entre biais ex ante (données) et ex post (déploiement).
  - **lisibilite** (5 %) — Grille lisible, pas un mur de texte.
  - **ai_disclosure** (5 %) — ai-usage.md présent.

## Lectures

- [NY-DFS Report on Apple Card Investigation (2021)](https://www.dfs.ny.gov/) — Le rapport officiel sur l'enquête Apple Card.
- [EU AI Act — Final Text (2024)](https://artificialintelligenceact.eu/) — Le texte de référence sur la régulation européenne IA.
- [Loi 25 Québec — Décisions automatisées](https://www.cai.gouv.qc.ca/) — Encadrement québécois des décisions automatisées.
- [OECD Principles on AI](https://oecd.ai/en/ai-principles) — Cadre international de référence sur l'IA responsable.

---

*Généré automatiquement à partir de `content/sessions/GTA651-12.yaml`. Pour corriger une coquille, modifiez le YAML source et poussez sur `master` — la CI régénère PDF + Markdown.*
