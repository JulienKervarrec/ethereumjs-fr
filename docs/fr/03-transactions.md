# 3. Transactions et signatures

Le package tx prend en charge les transactions legacy et les formats issus des EIP modernes, dont 1559, 2930, 4844 et 7702. Il encode, décode et signe les messages.

Les champs de type, nonce, gas, frais, destination et valeur alimentent ensuite l’exécution. Une signature valide ne garantit pas que la transaction soit admissible sur la chaîne ciblée.

Le package common fournit les paramètres de hardfork nécessaires à l’interprétation.

Suite : [blocs et chaîne](04-blocs-chaine.md).
