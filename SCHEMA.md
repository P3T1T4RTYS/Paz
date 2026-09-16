# Schéma d'un raisonnement Paz

Chaque raisonnement reçoit un identifiant permanent (`R-XXXXXX`) et conserve son historique.

```yaml
id: R-000001
titre: ""
question: ""
auteur: ""
date: ""
version: 1
statut: hypothese

proposition: ""

premisses:
  - id: P1
    texte: ""
    type: factuelle | normative | definitionnelle

raisonnement:
  - etape: 1
    texte: ""
    depend_de: [P1]

conclusion: ""

sources:
  - id: S1
    titre: ""
    url: ""
    type: primaire | secondaire
    soutient: [P1]

objections:
  - id: O1
    cible: P1 | etape-1 | conclusion
    texte: ""
    statut: ouverte

refutation_possible:
  - "Quel fait ou quelle observation ferait abandonner/modifier cette conclusion ?"

incertitudes:
  - ""

verifications: []
```

## Vérification

Une vérification est une contribution séparée :

```yaml
verification_id: V-000001
raisonnement_id: R-000001
version_verifiee: 1
verificateur: ""
type: factuelle | logique | sources | contre_argument
conclusion: valide | probleme_mineur | probleme_majeur | indetermine
constats:
  - cible: P1
    resultat: ""
    sources: [S1]
conflit_interets: "aucun connu"
```

Le statut collectif ne doit jamais être calculé uniquement à partir du nombre de votes. La qualité et l'indépendance des vérifications comptent davantage que la popularité.