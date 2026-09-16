# 7. Composition et usages

Pour rejouer un bloc ou exécuter une transaction, la VM assemble common, tx, util et state. Pour du bytecode seul, EVM suffit. Block et blockchain ajoutent les objets historiques, tandis que MPT et StateManager traitent l’état.

Cette composition réduit les dépendances inutiles et rend les tests ciblés. Elle impose en contrepartie de connaître la frontière de responsabilité de chaque package.

Les exemples et README de package servent de points d’entrée documentaires.

Suite : [limites](08-limites.md).
