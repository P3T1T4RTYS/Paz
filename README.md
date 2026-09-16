# Paz — Base publique de raisonnement collectif

Paz est un prototype de **base publique de raisonnements auditables**. Son objectif n'est pas de décider automatiquement ce qui est vrai ou moral, mais de permettre à des humains et à des systèmes d'IA de proposer, vérifier, contester et améliorer des raisonnements de façon transparente.

## Principe central

> Une affirmation gagne en crédibilité par la qualité de ses preuves et de son raisonnement, jamais par le statut, la richesse, la popularité, l'identité politique ou l'autorité de son auteur.

## Cycle d'un raisonnement

1. **Question** — une question clairement définie.
2. **Proposition indépendante** — une ou plusieurs réponses argumentées.
3. **Prémisses** — ce qui doit être accepté pour que l'argument fonctionne.
4. **Sources** — données permettant de vérifier les affirmations factuelles.
5. **Vérification factuelle** — vérification indépendante des faits et des sources.
6. **Vérification logique** — recherche de contradictions, erreurs d'inférence et contre-exemples.
7. **Contestation** — objections précises et réfutables.
8. **Révision** — nouvelle version conservant l'historique des changements.
9. **Contre-vérification** — examen indépendant de la version révisée.
10. **État** — hypothèse, preuves insuffisantes, contesté, partiellement étayé, fortement étayé ou réfuté.

## Règles de base

- Un consensus n'est pas une preuve.
- Une IA n'est pas une source primaire simplement parce qu'elle affirme quelque chose.
- Les affirmations factuelles importantes doivent renvoyer à des sources vérifiables.
- Les faits, inférences et jugements de valeur doivent être distingués.
- Les meilleures objections doivent rester visibles.
- Une conclusion doit indiquer ce qui pourrait la réfuter.
- Les anciennes versions ne sont pas effacées.
- Reconnaître et corriger une erreur est une contribution positive.
- Une personne puissante et une personne inconnue sont soumises au même standard de preuve.
- Les renseignements personnels inutiles, le harcèlement et les accusations nominatives non étayées n'ont pas leur place dans le corpus.

## Deux rôles distincts

### Contributeur
Propose une question, un raisonnement, une source, une objection ou une révision.

### Vérificateur
Examine indépendamment les faits, les sources et/ou la logique. Lorsque possible, plusieurs vérifications sont réalisées indépendamment avant que les vérificateurs voient les conclusions des autres.

## Objectif à long terme

Créer un corpus ouvert et exploitable par les humains comme par différents systèmes d'IA : non seulement **ce que la communauté pense**, mais **pourquoi elle le pense, quelles objections subsistent et quelles preuves pourraient faire changer la conclusion**.

## Structure du dépôt

- `CONSTITUTION.md` — principes de gouvernance et d'intégrité.
- `SCHEMA.md` — structure standard d'un raisonnement.
- `CONTRIBUTING.md` — protocole de contribution et de vérification.
- `reasonings/` — raisonnements versionnés.

Ce dépôt constitue une V0 expérimentale. Les règles elles-mêmes doivent pouvoir être critiquées et améliorées publiquement.