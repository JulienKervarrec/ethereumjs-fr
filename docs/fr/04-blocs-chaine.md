# 4. Blocs, en-têtes et chaîne canonique

Le package block modélise les blocs, en-têtes, retraits et champs propres aux évolutions Ethereum. Blockchain conserve et valide la chaîne canonique.

La VM peut exécuter une transaction ou construire un bloc dans le contexte d’un état et d’un hardfork. Les règles d’en-tête relient l’exécution aux données historiques.

Un client doit vérifier le parent, le numéro, les racines et les paramètres de réseau.

Suite : [état et tries](05-etat-tries.md).
