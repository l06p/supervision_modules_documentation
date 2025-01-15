# Licensing

## Description

Le Licensing est traité de la manière suivante, par module : 
  
  1. Acquisition initiale des droits d'utilisation du module (incluant une année glissante de souscription valable pour une installation),
  2. (Facultatif) Souscription annuelle complémentaire d'utilisation du module pour chaque installation supplémentaire,
  3. Par la suite, souscription annuelle complémentaire d'utilisation du module pour chaque installation.

La souscription annuelle pour un module donné donne l'accès à :

  * L'utilisation du module pour une unique installation,
  * L'accès aux mises à jour du module,
  * L'accès au support pour la déclaration de problèmes de fonctionnement du module (problem report),
  * L'accès au support pour la déclaration de demandes d'évolution fonctionnelles du module (feature request).

L'absence de souscription annuelle complémentaire d'utilisation d'un module durant plus de 3 mois induit une perte totale des droits d'utilisation module.  
Ainsi, afin de régulariser la situation, deux options sont possibles : 
  * Nouvelle acquisition initiale des droits d'utilisation du module,
  * Régularisation des souscriptions annuelles complémentaires manquantes. *(un rabais de 20% HT sera automatiquement octroyé*)

**<u>Note :</u>** L'intégralité des demandes d'évolution fonctionnelles seront étudiées. Toutefois, leur prise en compte au titre du support ainsi que leur positionnement dans une version ultérieure est à la discrétion de **L06P Software**.

## Fonctionnement logiciel du Licensing

Le licensing est traité par machine, que celle-ci soit physique ou virtuelle, via un fichier de licence dédié à cette installation.

Celui-ci suit le processus suivant :
``` mermaid
graph LR
  A[Start] --> B[Installation du module commons];
  B --> C[Génération du fingerprint];
  C --> D[Passage de la commande incluant le fingerprint et les modules demandés];
  D --> E[Génération et fourniture du fichier de licence.lic];
  E --> F[Installation du fichier licence.lic];
  F --> G[End]
```