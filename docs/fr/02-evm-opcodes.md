# 2. EVM, opcodes et précompiles

Le package EVM interprète le bytecode, gère la pile, la mémoire, le gas et les précompiles. Il constitue le moteur d’exécution de bas niveau.

Les règles d’exécution sont séparées de la VM qui ajoute la gestion de l’état, des transactions et des blocs. Cette séparation facilite les opcodes personnalisés et la recherche.

Une exécution correcte dépend du contexte de chaîne, du gas disponible et des données d’appel.

Suite : [transactions](03-transactions.md).
