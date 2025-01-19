# Usage des scripts SNMPv3

!!! tip "Préfixe v3"
    Les scripts intéragissant en SNMPv3 sont facilement identifiables par leur suffixe ***v3***.

Les scripts intéragissant en SNMPv3 peuvent être utilisés directement depuis un interpréteur de commande.

Etant automatiquement placés dans le répertoire `/usr/local/bin` lors de l'installation, leur appel depuis un interpréteur de commande bénéficie de l'autocomplétion.

## Arguments et paramètres communs

Des arguments et paramètres communs à tous les scripts intéragissant en SNMPv3 sont utilisés.

Ceux si sont les suivants : 

  * -u/--user : Le nom d'utilisateur [Obligatoire],
  * -a/--auth-protocol : Le protocole d'authentification [Obligatoire] {NONE/MD5/SHA/SHA_224/SHA_256/SHA_384/SHA_512'},
  * -A/--auth-key : La clé secrète d'authenfification [Obligatoire],
  * -x/--priv-protocol : Le protocole de chiffrement [Obligatoire] {NONE/DES/DES_3/AES_128/AES_192/AES_256},
  * -X/--priv-key : La clé secrète de chiffrement [Obligatoire],
  * -h/--host : L'adresse IP ou le FQDN de l'hôte interrogé en SNMPv2c [Obligatoire],
  * -p/--port : Le numéro de port de l'hôte interrogé en SNMPv2 [Obligatoire],
  * --usage : Permet d'afficher une aide textuelle relative à l'utilisation du script [Facultatif].

!!! example "noAuthNoPriv/authNoPriv/authPriv"
    Bien qu'obligatoires, les paramètres `--aut-protocol` et `--priv-protocol` permettent, lorsque positionnés à la valeur ***NONE***, de réaliser les combinaisons *noAuthNoPriv* et *authNoPriv*.
    Toute autro combinaison implique le mode *autPriv*.  
    Un paramètre `--auth-key` et/ou `--priv-key` disposant d'une valeur alors que le paramètre de protocole associé `--aut-protocol` et/ou `--priv-protocol` est à la valeur ***NONE*** implique la non prise en compte de la clé secrète spécifiée.

!!! tip "Utilisation du paramètre --usage"
    L'apparition du paramètre `--usage` dans la commande de lancement d'un script SNMPv2c affiche l'aide textuelle et termine l'exécution du script, quels que soient les arguments supplémentaires utilisés.

## Arguments et paramètres spécifiques

Des arguments et paramètres spécifiques peuvent être nécessaires en fonction du script utilisé.  
Ceux-ci sont précisés dans la documentation spécifique de chacun des scripts.