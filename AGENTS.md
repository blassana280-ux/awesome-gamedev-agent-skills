<!-- omnibrain-overlay:v2 -->

---

<!--
  Section locale du réseau blassana280-ux — ajoutée par OmniBrain.
  Les instructions upstream ci-dessus restent la seule autorité pour ce dépôt :
  cette section ajoute des règles de travail locales, elle n'en remplace aucune.
  Supprimez ce bloc avant toute contribution upstream si le dépôt ne l'accepte pas.
-->

# Couche locale — réseau OmniBrain

## Source de vérité de l'orchestrateur

> **blassana280-ux/omni-agents-framework** → `OMNIBRAIN.md`, `registry/`, `omni/orchestrator.py`, `tests/`

La référence historique `blassana280-ux/optimiser-mes-agents-IA` **n'a pas pu être vérifiée** (l'API GitHub
répond `403`, aucun accès en lecture) : elle ne doit plus être citée comme
existante.

## Règles de travail

1. **Classer avant d'agir** — simple → 1 agent ; moyenne → 1 à 3 ; complexe →
   escouade, dispatch dans une seule vague parallèle.
2. **Preuve fraîche obligatoire** — aucune affirmation sans sortie de commande,
   ligne de fichier ou réponse d'API. Verdict par défaut : « NEEDS WORK ».
3. **Réutiliser avant de créer** — chercher dans `registry/skills.json`
   (`python3 -m omni skills <termes>`) avant d'inventer un agent.
4. **Aucun secret dans le dépôt** — providers et tokens par variables
   d'environnement uniquement.
5. **Jamais d'écriture directe sur `main`** — branche + Pull Request.
6. **Respect de l'upstream** — `CONTRIBUTING.md` du dépôt prévaut, y compris
   pour la déclaration d'assistance IA.
