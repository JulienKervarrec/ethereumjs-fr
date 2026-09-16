# 5. État, MPT et preuves

MPT fournit les arbres Patricia Merkle et les preuves. StateManager ajoute des backends mémoire, RPC ou arbre binaire pour stocker comptes et emplacements.

Les racines de trie résument l’état sans contenir toutes les données dans chaque bloc. Une preuve permet de vérifier une valeur par rapport à une racine connue.

Les formats d’adresse, d’octets et de RLP sont centralisés dans les primitives utilitaires.

Suite : [configuration et hardforks](06-hardforks.md).
