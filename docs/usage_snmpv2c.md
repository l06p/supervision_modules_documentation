# Usage des scripts SNMPv2c

!!! tip "Préfixe v2c"
    Les scripts intéragissant en SNMPv2c sont facilement identifiables par leur suffixe ***v2c***.

Les scripts intéragissant en SNMPv2c peuvent être utilisés directement depuis un interpréteur de commande.

Etant automatiquement placés dans le répertoire `/usr/local/bin` lors de l'installation, leur appel depuis un interpréteur de commande bénéficie de l'autocomplétion.

## Arguments et paramètres communs

Des arguments et paramètres communs à tous les scripts intéragissant en SNMPv2c sont utilisés.

Ceux si sont les suivants : 

  * -c/--community_name : Le nom de la communauté SNMPv2c [Obligatoire],
  * -h/--host : L'adresse IP ou le FQDN de l'hôte interrogé en SNMPv2c [Obligatoire],
  * -p/--port : Le numéro de port de l'hôte interrogé en SNMPv2 [Obligatoire],
  * --usage : Permet d'afficher une aide textuelle relative à l'utilisation du script [Facultatif].

!!! tip "Utilisation du paramètre --usage"
    L'apparition du paramètre `--usage` dans la commande de lancement d'un script SNMPv2c affiche l'aide textuelle et termine l'exécution du script, quels que soient les arguments supplémentaires utilisés.

## Arguments et paramètres spécifiques

Des arguments et paramètres spécifiques peuvent être nécessaires en fonction du script utilisé.  
Ceux-ci sont précisés dans la documentation spécifique de chacun des scripts.