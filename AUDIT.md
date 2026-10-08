# Audit des preuves publiques

Ce profil distingue trois niveaux : **description**, **élément observable** et **preuve reproductible**. Une vitrine architecturale ne remplace pas un test exécutable.

Un lecteur qui souhaite examiner la cohérence des choix techniques peut suivre trois frontières de système, dans cet ordre :

1. **Perception → action** : commencer par [SYM](https://github.com/christophercrahay-cmyk/Sym-showcase/blob/main/AUDIT.md). Quelles informations entrent dans le système, et qu'est-ce qui permet de les considérer comme fiables ?
2. **Génération → validation** : poursuivre avec LOCAL_AGENTS + Neurobase. Qu'est-ce qui empêche une sortie de modèle de devenir automatiquement une donnée de confiance ?
3. **Simulation → présentation** : terminer avec AFTER. Que reste-t-il vérifiable quand l'interface graphique est retirée ?

Ce parcours examine la cohérence des responsabilités et des limites publiées. **Il ne prouve pas que les implémentations privées fonctionnent**. Pour cela, une démonstration et des tests restent nécessaires.

Indice de lecture : les trois fiches d'audit contiennent chacune une référence vers la suivante.
