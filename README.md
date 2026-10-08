# Christopher Crahay

### AI Builder — Intégrateur de systèmes IA

Je conçois et assemble des systèmes qui relient **IA, logiciels, données, automatisation et monde physique**.

Mon parcours vient du terrain : artisan du bâtiment, électricité, plomberie, rénovation et gestion de ma propre entreprise. Cette culture technique influence directement ma façon de construire du logiciel : partir du problème réel, comprendre les contraintes, choisir les briques utiles, tester, puis aller jusqu'à un système utilisable.

Je ne cherche pas à empiler des démonstrations d'IA. Je construis des outils.

**[Portfolio en ligne — démonstrations, captures et preuves techniques](https://christopher-crahay.vercel.app/)** · [CV](https://christopher-crahay.vercel.app/cv)

## Démonstrations et preuves publiques — à consulter en premier

Ces liens mènent à des **réalisations observables** : vidéos du produit et du robot, captures de code authentique, consoles de tests et images d'une simulation Godot. Les dépôts publics sont des **vitrines documentaires**, pas les sources de production.

### PROOF-01 — Comment neuf tests peuvent-ils réussir alors qu'un vérificateur accepte 42 pour « 5 + 6 » ?

Une [miniature Python publiquement exécutable](https://github.com/christophercrahay-cmyk/local-agents-neurobase-showcase/blob/main/proof_01.py) reproduit **volontairement** un faux accord : un outil calcule `6 × 7` et une règle défectueuse accepte `42`, alors que la demande est `5 + 6`. Une règle illustrative renforcée refuse ce résultat. **[Voir les 9 tests exécutés sur GitHub Actions](https://github.com/christophercrahay-cmyk/local-agents-neurobase-showcase/actions/runs/37807802556)** · [Lire l'explication et les limites](https://github.com/christophercrahay-cmyk/local-agents-neurobase-showcase/blob/main/PROOF_01.md).

**À ne pas confondre :** cette reproduction indépendante a été écrite pour la vitrine ; elle **n'exécute pas le code privé de LOCAL_AGENTS** et ne démontre pas à elle seule la correction de son vérificateur réel.


| Projet | Preuves accessibles | Ce que l'on peut réellement vérifier |
| --- | --- | --- |
| **ArtisanFlow** | **[Voir la vidéo de l'application](https://christopher-crahay.vercel.app/work/artisanflow)** | Parcours devis → lien de signature → signature client → statut signé. **Distribution Google Play en test privé**, réservée aux testeurs, **pas une publication publique**. Le film ne prouve pas la synchronisation hors ligne. |
| **SYM** | **[Voir le robot en vidéo](https://christopher-crahay.vercel.app/work/sym)** · **[TikTok @symrobot](https://www.tiktok.com/@symrobot)** | Réponse vocale d'un prototype physique, animation de la mâchoire et autres vidéos du projet. Pas de banc de tests matériels reproductible publié. |
| **LOCAL_AGENTS + Neurobase** | **[Voir le code réel et les résultats de tests](https://christopher-crahay.vercel.app/work/local-agents)** | Quatre captures de code authentique ; consoles de **266 tests LOCAL_AGENTS réussis** sur l'arbre commité `136db6c` et **105 tests NEUROBASE réussis** sur `1f515df`. Ces résultats ne couvrent pas l'arbre courant et les suites exécutables restent privées. |
| **AFTER** | **[Voir les captures du jeu et des tests](https://christopher-crahay.vercel.app/work/after)** | Six captures d'une vraie scène Godot, plus un relevé de deux suites isolées (30/0 et 14/0). Les entrées de jeu étaient injectées par script ; ce n'est ni une session jouée à la main ni une revalidation complète. |

**Périmètre :** les vidéos et captures montrent des éléments concrets, mais ne remplacent ni une revue de code confidentielle ni une exécution indépendante des tests. Le [parcours d'examen technique](AUDIT.md) explicite cette distinction.

## Projets sélectionnés

### [ArtisanFlow](https://github.com/christophercrahay-cmyk/artisanflow-showcase)
Application métier mobile pensée à partir des contraintes réelles d'un artisan : clients, chantiers, saisie vocale, données métier, devis et facturation.

**React Native · Expo · Supabase · transcription vocale · IA · données métier**

**Distribution Android : Google Play, canal de test privé (accès réservé aux testeurs ; application non publiée publiquement).**

[Démo et étude de cas ArtisanFlow](https://christopher-crahay.vercel.app/work/artisanflow)

### [SYM](https://github.com/christophercrahay-cmyk/Sym-showcase)
Prototype d'IA incarnée reliant voix, vision, agents logiciels, électronique embarquée et robotique.

**Agents IA · vision · STT/TTS · ESP32 · InMoov · impression 3D**

[Démo vidéo SYM](https://christopher-crahay.vercel.app/work/sym) · [TikTok du projet SYM (@symrobot)](https://www.tiktok.com/@symrobot)

### [LOCAL_AGENTS + Neurobase](https://github.com/christophercrahay-cmyk/local-agents-neurobase-showcase)
Expérimentation autour de l'orchestration d'agents, de l'inférence locale, de la mémoire externe et de la recherche hybride.

**Python · FastAPI · Ollama · Pydantic · SQLite · FTS5 · embeddings · RAG**

[Code réel et tests datés LOCAL_AGENTS / Neurobase](https://christopher-crahay.vercel.app/work/local-agents)

### [AFTER](https://github.com/christophercrahay-cmyk/after-showcase)
Simulation systémique sous Godot autour de la récupération, de la fabrication, de la robotique et de l'automatisation.

**Godot · simulation · agents · navigation · crafting · pipeline 3D · tests**

[Captures du jeu et tests AFTER](https://christopher-crahay.vercel.app/work/after)

## Technical review — vérification des preuves

Les démonstrations et captures liées ci-dessus donnent accès à des **observations publiques**, pas au code complet des projets privés. Une [carte de vérification](AUDIT.md) permet d'examiner les frontières techniques, les limites et le niveau réel de preuve, sans confondre documentaire, tests datés et validation reproductible.

## Ma façon de travailler

```text
problème concret
      ↓
contraintes réelles
      ↓
architecture minimale
      ↓
prototype
      ↓
tests / observation
      ↓
itération
      ↓
outil utilisable
```

Je travaille particulièrement sur les zones où plusieurs disciplines doivent coopérer : modèle IA + API + données + interface + matériel + contraintes métier.

## Compétences mobilisées

**IA & agents** — intégration LLM, orchestration, RAG, embeddings, évaluation, modèles locaux et cloud  
**Applications** — APIs, bases de données, applications mobiles et interfaces web  
**Systèmes** — architecture, automatisation, persistance, tests et intégration  
**Maker** — électronique embarquée, robotique, impression 3D et prototypage physique  
**Terrain** — compréhension des processus métier et recherche de solutions pragmatiques

## Ce que je cherche

Des problèmes concrets où l'IA doit sortir du prototype pour devenir un **système réellement utile** : intégration IA, automatisation, outils métier, agents, prototypes ou projets mêlant logiciel et monde physique.

---


<sub>Les dépôts publics présentés ici sont des vitrines techniques. Les sources de production, données privées, secrets, prompts internes et implémentations propriétaires restent volontairement privés.</sub>
