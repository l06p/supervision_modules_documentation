# Descriptifs des scripts M2MSoft/s5000

## Nommage
Le nommage des scripts est de la forme suivante : **m2msoft_s5000_**<*nom_du_script*\>**_[v2c/v3]**.

## Exemples
```bash
user@host:$ ###  get_mtp_saturation_percentage_v2c.py -c public -h 127.0.0.1 -p 1161 -n mtp0                       
OK: MTP 'mtp0' Saturation is 40% |
```

```bash
user@host:$ ###  get_call_total_number_v3.py -u test -a MD5 -A testkey123 -x DES -X testkey123 -h 127.0.0.1 -p 1161 
OK: There are currently 9 Calls |
```

## Section General

###  get_general_mode
  * <u>Description :</u> Retourne le mode de fonctionnement du S5000
  * <u>Versions SNMP :</u> ![SNMPv2c](https://custom-icon-badges.demolab.com/badge/SNMPv2c-royalblue.svg?logo=activity&logoSource=feather) ![SNMPv3](https://custom-icon-badges.demolab.com/badge/SNMPv3-olivedrab.svg?logo=activity&logoSource=feather)
  * <u>Paramètres Spécifiques :</u> ![N/A](https://custom-icon-badges.demolab.com/badge/N/A-green.svg)

###  get_general_name
  * <u>Description :</u> Retourne le nom du S5000
  * <u>Versions SNMP :</u> ![SNMPv2c](https://custom-icon-badges.demolab.com/badge/SNMPv2c-royalblue.svg?logo=activity&logoSource=feather) ![SNMPv3](https://custom-icon-badges.demolab.com/badge/SNMPv3-olivedrab.svg?logo=activity&logoSource=feather)
  * <u>Paramètres Spécifiques :</u> ![N/A](https://custom-icon-badges.demolab.com/badge/N/A-green.svg)

###  get_general_last_save
  * <u>Description :</u> Retourne le date de sauvegarde de la configuration actuelle du S5000
  * <u>Versions SNMP :</u> ![SNMPv2c](https://custom-icon-badges.demolab.com/badge/SNMPv2c-royalblue.svg?logo=activity&logoSource=feather) ![SNMPv3](https://custom-icon-badges.demolab.com/badge/SNMPv3-olivedrab.svg?logo=activity&logoSource=feather)
  * <u>Paramètres Spécifiques :</u> ![N/A](https://custom-icon-badges.demolab.com/badge/N/A-green.svg)


## Section Endpoint

###  get_endpoint_total_number
  * <u>Description :</u> Retourne le nombre total d'endpoints
  * <u>Versions SNMP :</u> ![SNMPv2c](https://custom-icon-badges.demolab.com/badge/SNMPv2c-royalblue.svg?logo=activity&logoSource=feather) ![SNMPv3](https://custom-icon-badges.demolab.com/badge/SNMPv3-olivedrab.svg?logo=activity&logoSource=feather)
  * <u>Paramètres Spécifiques :</u> ![N/A](https://custom-icon-badges.demolab.com/badge/N/A-green.svg)

###  get_endpoint_index
  * <u>Description :</u> Retourne l'index dans la MIB de l'endpoint précisé en paramètre
  * <u>Versions SNMP :</u> ![SNMPv2c](https://custom-icon-badges.demolab.com/badge/SNMPv2c-royalblue.svg?logo=activity&logoSource=feather) ![SNMPv3](https://custom-icon-badges.demolab.com/badge/SNMPv3-olivedrab.svg?logo=activity&logoSource=feather)
  * <u>Paramètres Spécifiques :</u> ![ENDPOINT_NAME](https://custom-icon-badges.demolab.com/badge/--n/----name-ENDPOINT__NAME-violet.svg) L'alias ou le numéro de l'endpoint

###  get_endpoint_type
  * <u>Description :</u> Retourne le type de l'endpoint précisé en paramètre
  * <u>Versions SNMP :</u> ![SNMPv2c](https://custom-icon-badges.demolab.com/badge/SNMPv2c-royalblue.svg?logo=activity&logoSource=feather) ![SNMPv3](https://custom-icon-badges.demolab.com/badge/SNMPv3-olivedrab.svg?logo=activity&logoSource=feather)
  * <u>Paramètres Spécifiques :</u> ![ENDPOINT_NAME](https://custom-icon-badges.demolab.com/badge/--n/----name-ENDPOINT__NAME-violet.svg) L'alias ou le numéro de l'endpoint

###  get_endpoint_total_number_media_entity
  * <u>Description :</u> Retourne le nombre total d'endpoints de type Media Entity
  * <u>Versions SNMP :</u> ![SNMPv2c](https://custom-icon-badges.demolab.com/badge/SNMPv2c-royalblue.svg?logo=activity&logoSource=feather) ![SNMPv3](https://custom-icon-badges.demolab.com/badge/SNMPv3-olivedrab.svg?logo=activity&logoSource=feather)
  * <u>Paramètres Spécifiques :</u> ![N/A](https://custom-icon-badges.demolab.com/badge/N/A-green.svg)

###  get_endpoint_total_number_registered
  * <u>Description :</u> Retourne le nombre total d'endpoints de type Registered
  * <u>Versions SNMP :</u> ![SNMPv2c](https://custom-icon-badges.demolab.com/badge/SNMPv2c-royalblue.svg?logo=activity&logoSource=feather) ![SNMPv3](https://custom-icon-badges.demolab.com/badge/SNMPv3-olivedrab.svg?logo=activity&logoSource=feather)
  * <u>Paramètres Spécifiques :</u> ![N/A](https://custom-icon-badges.demolab.com/badge/N/A-green.svg)

###  get_endpoint_total_number_static_in
  * <u>Description :</u> Retourne le nombre total d'endpoints de type Static Entity IN
  * <u>Versions SNMP :</u> ![SNMPv2c](https://custom-icon-badges.demolab.com/badge/SNMPv2c-royalblue.svg?logo=activity&logoSource=feather) ![SNMPv3](https://custom-icon-badges.demolab.com/badge/SNMPv3-olivedrab.svg?logo=activity&logoSource=feather)
  * <u>Paramètres Spécifiques :</u> ![N/A](https://custom-icon-badges.demolab.com/badge/N/A-green.svg)

###  get_endpoint_total_number_static_out
  * <u>Description :</u> Retourne le nombre total d'endpoints de type Static Entity OUT
  * <u>Versions SNMP :</u> ![SNMPv2c](https://custom-icon-badges.demolab.com/badge/SNMPv2c-royalblue.svg?logo=activity&logoSource=feather) ![SNMPv3](https://custom-icon-badges.demolab.com/badge/SNMPv3-olivedrab.svg?logo=activity&logoSource=feather)
  * <u>Paramètres Spécifiques :</u> ![N/A](https://custom-icon-badges.demolab.com/badge/N/A-green.svg)

###  get_endpoint_protocol
  * <u>Description :</u> Retourne le protocole de signalisation de l'endpoint précisé en paramètre
  * <u>Versions SNMP :</u> ![SNMPv2c](https://custom-icon-badges.demolab.com/badge/SNMPv2c-royalblue.svg?logo=activity&logoSource=feather) ![SNMPv3](https://custom-icon-badges.demolab.com/badge/SNMPv3-olivedrab.svg?logo=activity&logoSource=feather)
  * <u>Paramètres Spécifiques :</u> ![ENDPOINT_NAME](https://custom-icon-badges.demolab.com/badge/--n/----name-ENDPOINT__NAME-violet.svg) L'alias ou le numéro de l'endpoint

###  get_endpoint_total_number_h323
  * <u>Description :</u> Retourne le nombre total d'endpoints dont le protocole de signalisation est H323
  * <u>Versions SNMP :</u> ![SNMPv2c](https://custom-icon-badges.demolab.com/badge/SNMPv2c-royalblue.svg?logo=activity&logoSource=feather) ![SNMPv3](https://custom-icon-badges.demolab.com/badge/SNMPv3-olivedrab.svg?logo=activity&logoSource=feather)
  * <u>Paramètres Spécifiques :</u> ![N/A](https://custom-icon-badges.demolab.com/badge/N/A-green.svg)

###  get_endpoint_total_number_sip_tcp
  * <u>Description :</u> Retourne le nombre total d'endpoints dont le protocole de signalisation est SIP/TCP
  * <u>Versions SNMP :</u> ![SNMPv2c](https://custom-icon-badges.demolab.com/badge/SNMPv2c-royalblue.svg?logo=activity&logoSource=feather) ![SNMPv3](https://custom-icon-badges.demolab.com/badge/SNMPv3-olivedrab.svg?logo=activity&logoSource=feather)
  * <u>Paramètres Spécifiques :</u> ![N/A](https://custom-icon-badges.demolab.com/badge/N/A-green.svg)

###  get_endpoint_total_number_sip_tls
  * <u>Description :</u> Retourne le nombre total d'endpoints dont le protocole de signalisation est SIP/TLS
  * <u>Versions SNMP :</u> ![SNMPv2c](https://custom-icon-badges.demolab.com/badge/SNMPv2c-royalblue.svg?logo=activity&logoSource=feather) ![SNMPv3](https://custom-icon-badges.demolab.com/badge/SNMPv3-olivedrab.svg?logo=activity&logoSource=feather)
  * <u>Paramètres Spécifiques :</u> ![N/A](https://custom-icon-badges.demolab.com/badge/N/A-green.svg)

###  get_endpoint_total_number_sip_udp
  * <u>Description :</u> Retourne le nombre total d'endpoints dont le protocole de signalisation est SIP/UDP
  * <u>Versions SNMP :</u> ![SNMPv2c](https://custom-icon-badges.demolab.com/badge/SNMPv2c-royalblue.svg?logo=activity&logoSource=feather) ![SNMPv3](https://custom-icon-badges.demolab.com/badge/SNMPv3-olivedrab.svg?logo=activity&logoSource=feather)
  * <u>Paramètres Spécifiques :</u> ![N/A](https://custom-icon-badges.demolab.com/badge/N/A-green.svg)

###  get_endpoint_existence
  * <u>Description :</u> Retourne l'existance ou non de l'endpoint précisé en paramètre
  * <u>Versions SNMP :</u> ![SNMPv2c](https://custom-icon-badges.demolab.com/badge/SNMPv2c-royalblue.svg?logo=activity&logoSource=feather) ![SNMPv3](https://custom-icon-badges.demolab.com/badge/SNMPv3-olivedrab.svg?logo=activity&logoSource=feather)
  * <u>Paramètres Spécifiques :</u> ![ENDPOINT_NAME](https://custom-icon-badges.demolab.com/badge/--n/----name-ENDPOINT__NAME-violet.svg) L'alias ou le numéro de l'endpoint

###  get_endpoint_ttl
  * <u>Description :</u> Retourne le TTL en secondes de l'endpoint précisé en paramètre
  * <u>Versions SNMP :</u> ![SNMPv2c](https://custom-icon-badges.demolab.com/badge/SNMPv2c-royalblue.svg?logo=activity&logoSource=feather) ![SNMPv3](https://custom-icon-badges.demolab.com/badge/SNMPv3-olivedrab.svg?logo=activity&logoSource=feather)
  * <u>Paramètres Spécifiques :</u> ![ENDPOINT_NAME](https://custom-icon-badges.demolab.com/badge/--n/----name-ENDPOINT__NAME-violet.svg) L'alias ou le numéro de l'endpoint

###  get_endpoint_remote_ip
  * <u>Description :</u> Retourne l'adresse IP de l'endpoint précisé en paramètre
  * <u>Versions SNMP :</u> ![SNMPv2c](https://custom-icon-badges.demolab.com/badge/SNMPv2c-royalblue.svg?logo=activity&logoSource=feather) ![SNMPv3](https://custom-icon-badges.demolab.com/badge/SNMPv3-olivedrab.svg?logo=activity&logoSource=feather)
  * <u>Paramètres Spécifiques :</u> ![ENDPOINT_NAME](https://custom-icon-badges.demolab.com/badge/--n/----name-ENDPOINT__NAME-violet.svg) L'alias ou le numéro de l'endpoint

###  get_endpoint_remote_port
  * <u>Description :</u> Retourne le numéro de port de l'endpoint précisé en paramètre
  * <u>Versions SNMP :</u> ![SNMPv2c](https://custom-icon-badges.demolab.com/badge/SNMPv2c-royalblue.svg?logo=activity&logoSource=feather) ![SNMPv3](https://custom-icon-badges.demolab.com/badge/SNMPv3-olivedrab.svg?logo=activity&logoSource=feather)
  * <u>Paramètres Spécifiques :</u> ![ENDPOINT_NAME](https://custom-icon-badges.demolab.com/badge/--n/----name-ENDPOINT__NAME-violet.svg) L'alias ou le numéro de l'endpoint

###  get_endpoint_local_ip
  * <u>Description :</u> Retourne l'adresse IP du S5000 dialoguant avec de l'endpoint précisé en paramètre
  * <u>Versions SNMP :</u> ![SNMPv2c](https://custom-icon-badges.demolab.com/badge/SNMPv2c-royalblue.svg?logo=activity&logoSource=feather) ![SNMPv3](https://custom-icon-badges.demolab.com/badge/SNMPv3-olivedrab.svg?logo=activity&logoSource=feather)
  * <u>Paramètres Spécifiques :</u> ![ENDPOINT_NAME](https://custom-icon-badges.demolab.com/badge/--n/----name-ENDPOINT__NAME-violet.svg) L'alias ou le numéro de l'endpoint

###  get_endpoint_local_port
  * <u>Description :</u> Retourne le numéro de port du S5000 dialoguant avec de l'endpoint précisé en paramètre
  * <u>Versions SNMP :</u> ![SNMPv2c](https://custom-icon-badges.demolab.com/badge/SNMPv2c-royalblue.svg?logo=activity&logoSource=feather) ![SNMPv3](https://custom-icon-badges.demolab.com/badge/SNMPv3-olivedrab.svg?logo=activity&logoSource=feather)
  * <u>Paramètres Spécifiques :</u> ![ENDPOINT_NAME](https://custom-icon-badges.demolab.com/badge/--n/----name-ENDPOINT__NAME-violet.svg) L'alias ou le numéro de l'endpoint

###  get_endpoint_product_id
  * <u>Description :</u> Retourne l'identifiant et le numéro de version de l'endpoint précisé en paramètre
  * <u>Versions SNMP :</u> ![SNMPv2c](https://custom-icon-badges.demolab.com/badge/SNMPv2c-royalblue.svg?logo=activity&logoSource=feather) ![SNMPv3](https://custom-icon-badges.demolab.com/badge/SNMPv3-olivedrab.svg?logo=activity&logoSource=feather)
  * <u>Paramètres Spécifiques :</u> ![ENDPOINT_NAME](https://custom-icon-badges.demolab.com/badge/--n/----name-ENDPOINT__NAME-violet.svg) L'alias ou le numéro de l'endpoint

###  get_endpoint_registrar_mode
  * <u>Description :</u> Retourne le mode d'enregistrement de l'endpoint précisé en paramètre
  * <u>Versions SNMP :</u> ![SNMPv2c](https://custom-icon-badges.demolab.com/badge/SNMPv2c-royalblue.svg?logo=activity&logoSource=feather) ![SNMPv3](https://custom-icon-badges.demolab.com/badge/SNMPv3-olivedrab.svg?logo=activity&logoSource=feather)
  * <u>Paramètres Spécifiques :</u> ![ENDPOINT_NAME](https://custom-icon-badges.demolab.com/badge/--n/----name-ENDPOINT__NAME-violet.svg) L'alias ou le numéro de l'endpoint

###  get_endpoint_total_not_registrar_mode
  * <u>Description :</u> Retourne le nombre total d'endpoints étant dont le mode d'enregistrement est Non Enregistré
  * <u>Versions SNMP :</u> ![SNMPv2c](https://custom-icon-badges.demolab.com/badge/SNMPv2c-royalblue.svg?logo=activity&logoSource=feather) ![SNMPv3](https://custom-icon-badges.demolab.com/badge/SNMPv3-olivedrab.svg?logo=activity&logoSource=feather)
  * <u>Paramètres Spécifiques :</u> ![N/A](https://custom-icon-badges.demolab.com/badge/N/A-green.svg)

###  get_endpoint_total_registrar_mode
  * <u>Description :</u> Retourne le nombre total d'endpoints étant dont le mode d'enregistrement est Enregistré
  * <u>Versions SNMP :</u> ![SNMPv2c](https://custom-icon-badges.demolab.com/badge/SNMPv2c-royalblue.svg?logo=activity&logoSource=feather) ![SNMPv3](https://custom-icon-badges.demolab.com/badge/SNMPv3-olivedrab.svg?logo=activity&logoSource=feather)
  * <u>Paramètres Spécifiques :</u> ![N/A](https://custom-icon-badges.demolab.com/badge/N/A-green.svg)

###  get_endpoint_registrar_status
  * <u>Description :</u> Retourne l'état d'enregistrement de l'endpoint précisé en paramètre
  * <u>Versions SNMP :</u> ![SNMPv2c](https://custom-icon-badges.demolab.com/badge/SNMPv2c-royalblue.svg?logo=activity&logoSource=feather) ![SNMPv3](https://custom-icon-badges.demolab.com/badge/SNMPv3-olivedrab.svg?logo=activity&logoSource=feather)
  * <u>Paramètres Spécifiques :</u> ![ENDPOINT_NAME](https://custom-icon-badges.demolab.com/badge/--n/----name-ENDPOINT__NAME-violet.svg) L'alias ou le numéro de l'endpoint

###  get_endpoint_total_status_not_registered
  * <u>Description :</u> Retourne le nombre total d'endpoints dont l'état d'enregistrement est Non Enregistré
  * <u>Versions SNMP :</u> ![SNMPv2c](https://custom-icon-badges.demolab.com/badge/SNMPv2c-royalblue.svg?logo=activity&logoSource=feather) ![SNMPv3](https://custom-icon-badges.demolab.com/badge/SNMPv3-olivedrab.svg?logo=activity&logoSource=feather)
  * <u>Paramètres Spécifiques :</u> ![N/A](https://custom-icon-badges.demolab.com/badge/N/A-green.svg)

###  get_endpoint_total_status_registered
  * <u>Description :</u> Retourne le nombre total d'endpoints dont l'état est d'enregistrement est Enregistré
  * <u>Versions SNMP :</u> ![SNMPv2c](https://custom-icon-badges.demolab.com/badge/SNMPv2c-royalblue.svg?logo=activity&logoSource=feather) ![SNMPv3](https://custom-icon-badges.demolab.com/badge/SNMPv3-olivedrab.svg?logo=activity&logoSource=feather)
  * <u>Paramètres Spécifiques :</u> ![N/A](https://custom-icon-badges.demolab.com/badge/N/A-green.svg)

###  get_endpoint_supervision_status
  * <u>Description :</u> Retourne l'état de supervision de l'endpoint précisé en paramètre
  * <u>Versions SNMP :</u> ![SNMPv2c](https://custom-icon-badges.demolab.com/badge/SNMPv2c-royalblue.svg?logo=activity&logoSource=feather) ![SNMPv3](https://custom-icon-badges.demolab.com/badge/SNMPv3-olivedrab.svg?logo=activity&logoSource=feather)
  * <u>Paramètres Spécifiques :</u> ![ENDPOINT_NAME](https://custom-icon-badges.demolab.com/badge/--n/----name-ENDPOINT__NAME-violet.svg) L'alias ou le numéro de l'endpoint

###  get_endpoint_total_number_not_supervised
  * <u>Description :</u> Retourne le nombre total d'endpoints dont l'état de supervision est Non Supervisé
  * <u>Versions SNMP :</u> ![SNMPv2c](https://custom-icon-badges.demolab.com/badge/SNMPv2c-royalblue.svg?logo=activity&logoSource=feather) ![SNMPv3](https://custom-icon-badges.demolab.com/badge/SNMPv3-olivedrab.svg?logo=activity&logoSource=feather)
  * <u>Paramètres Spécifiques :</u> ![N/A](https://custom-icon-badges.demolab.com/badge/N/A-green.svg)

###  get_endpoint_total_number_down
  * <u>Description :</u> Retourne le nombre total d'endpoints dont l'état de supervision est Down
  * <u>Versions SNMP :</u> ![SNMPv2c](https://custom-icon-badges.demolab.com/badge/SNMPv2c-royalblue.svg?logo=activity&logoSource=feather) ![SNMPv3](https://custom-icon-badges.demolab.com/badge/SNMPv3-olivedrab.svg?logo=activity&logoSource=feather)
  * <u>Paramètres Spécifiques :</u> ![N/A](https://custom-icon-badges.demolab.com/badge/N/A-green.svg)

###  get_endpoint_total_number_up
  * <u>Description :</u> Retourne le nombre total d'endpoints dont l'état de supervision est Up
  * <u>Versions SNMP :</u> ![SNMPv2c](https://custom-icon-badges.demolab.com/badge/SNMPv2c-royalblue.svg?logo=activity&logoSource=feather) ![SNMPv3](https://custom-icon-badges.demolab.com/badge/SNMPv3-olivedrab.svg?logo=activity&logoSource=feather)
  * <u>Paramètres Spécifiques :</u> ![N/A](https://custom-icon-badges.demolab.com/badge/N/A-green.svg)


## Section Calls

###  get_call_total_number
  * <u>Description :</u> Retourne le nombre total d'appels en cours
  * <u>Versions SNMP :</u> ![SNMPv2c](https://custom-icon-badges.demolab.com/badge/SNMPv2c-royalblue.svg?logo=activity&logoSource=feather) ![SNMPv3](https://custom-icon-badges.demolab.com/badge/SNMPv3-olivedrab.svg?logo=activity&logoSource=feather)
  * <u>Paramètres Spécifiques :</u> ![N/A](https://custom-icon-badges.demolab.com/badge/N/A-green.svg)

###  get_call_total_number_g711a_legs
  * <u>Description :</u> Retourne le nombre total de call legs dont le codec est g711 codé en PCM-A
  * <u>Versions SNMP :</u> ![SNMPv2c](https://custom-icon-badges.demolab.com/badge/SNMPv2c-royalblue.svg?logo=activity&logoSource=feather) ![SNMPv3](https://custom-icon-badges.demolab.com/badge/SNMPv3-olivedrab.svg?logo=activity&logoSource=feather)
  * <u>Paramètres Spécifiques :</u> ![N/A](https://custom-icon-badges.demolab.com/badge/N/A-green.svg)

###  get_call_total_number_g711u_legs
  * <u>Description :</u> Retourne le nombre total de call legs dont le codec est g711 codé en PCM-U
  * <u>Versions SNMP :</u> ![SNMPv2c](https://custom-icon-badges.demolab.com/badge/SNMPv2c-royalblue.svg?logo=activity&logoSource=feather) ![SNMPv3](https://custom-icon-badges.demolab.com/badge/SNMPv3-olivedrab.svg?logo=activity&logoSource=feather)
  * <u>Paramètres Spécifiques :</u> ![N/A](https://custom-icon-badges.demolab.com/badge/N/A-green.svg)

###  get_call_total_number_g722_legs
  * <u>Description :</u> Retourne le nombre total de call legs dont le codec est g722
  * <u>Versions SNMP :</u> ![SNMPv2c](https://custom-icon-badges.demolab.com/badge/SNMPv2c-royalblue.svg?logo=activity&logoSource=feather) ![SNMPv3](https://custom-icon-badges.demolab.com/badge/SNMPv3-olivedrab.svg?logo=activity&logoSource=feather)
  * <u>Paramètres Spécifiques :</u> ![N/A](https://custom-icon-badges.demolab.com/badge/N/A-green.svg)

###  get_call_total_number_g729_legs
  * <u>Description :</u> Retourne le nombre total de call legs dont le codec est g729
  * <u>Versions SNMP :</u> ![SNMPv2c](https://custom-icon-badges.demolab.com/badge/SNMPv2c-royalblue.svg?logo=activity&logoSource=feather) ![SNMPv3](https://custom-icon-badges.demolab.com/badge/SNMPv3-olivedrab.svg?logo=activity&logoSource=feather)
  * <u>Paramètres Spécifiques :</u> ![N/A](https://custom-icon-badges.demolab.com/badge/N/A-green.svg)

###  get_call_total_number_ilbc_legs
  * <u>Description :</u> Retourne le nombre total de call legs dont le codec est iLBC
  * <u>Versions SNMP :</u> ![SNMPv2c](https://custom-icon-badges.demolab.com/badge/SNMPv2c-royalblue.svg?logo=activity&logoSource=feather) ![SNMPv3](https://custom-icon-badges.demolab.com/badge/SNMPv3-olivedrab.svg?logo=activity&logoSource=feather)
  * <u>Paramètres Spécifiques :</u> ![N/A](https://custom-icon-badges.demolab.com/badge/N/A-green.svg)

###  get_call_total_number_opus_legs
  * <u>Description :</u> Retourne le nombre total de call legs dont le codec est OPUS
  * <u>Versions SNMP :</u> ![SNMPv2c](https://custom-icon-badges.demolab.com/badge/SNMPv2c-royalblue.svg?logo=activity&logoSource=feather) ![SNMPv3](https://custom-icon-badges.demolab.com/badge/SNMPv3-olivedrab.svg?logo=activity&logoSource=feather)
  * <u>Paramètres Spécifiques :</u> ![N/A](https://custom-icon-badges.demolab.com/badge/N/A-green.svg)

###  get_call_total_number_raw_legs
  * <u>Description :</u> Retourne le nombre total de call legs dont le format est brut
  * <u>Versions SNMP :</u> ![SNMPv2c](https://custom-icon-badges.demolab.com/badge/SNMPv2c-royalblue.svg?logo=activity&logoSource=feather) ![SNMPv3](https://custom-icon-badges.demolab.com/badge/SNMPv3-olivedrab.svg?logo=activity&logoSource=feather)
  * <u>Paramètres Spécifiques :</u> ![N/A](https://custom-icon-badges.demolab.com/badge/N/A-green.svg)

###  get_call_total_number_not_srtp_legs
  * <u>Description :</u> Retourne le nombre total de call legs n'utilisant pas SRTP
  * <u>Versions SNMP :</u> ![SNMPv2c](https://custom-icon-badges.demolab.com/badge/SNMPv2c-royalblue.svg?logo=activity&logoSource=feather) ![SNMPv3](https://custom-icon-badges.demolab.com/badge/SNMPv3-olivedrab.svg?logo=activity&logoSource=feather)
  * <u>Paramètres Spécifiques :</u> ![N/A](https://custom-icon-badges.demolab.com/badge/N/A-green.svg)

###  get_call_total_number_srtp_legs
  * <u>Description :</u> Retourne le nombre total de call legs utilisant SRTP
  * <u>Versions SNMP :</u> ![SNMPv2c](https://custom-icon-badges.demolab.com/badge/SNMPv2c-royalblue.svg?logo=activity&logoSource=feather) ![SNMPv3](https://custom-icon-badges.demolab.com/badge/SNMPv3-olivedrab.svg?logo=activity&logoSource=feather)
  * <u>Paramètres Spécifiques :</u> ![N/A](https://custom-icon-badges.demolab.com/badge/N/A-green.svg)

###  get_call_total_number_status_alerting
  * <u>Description :</u> Retourne le nombre total d'appels dont le statut est Alerting
  * <u>Versions SNMP :</u> ![SNMPv2c](https://custom-icon-badges.demolab.com/badge/SNMPv2c-royalblue.svg?logo=activity&logoSource=feather) ![SNMPv3](https://custom-icon-badges.demolab.com/badge/SNMPv3-olivedrab.svg?logo=activity&logoSource=feather)
  * <u>Paramètres Spécifiques :</u> ![N/A](https://custom-icon-badges.demolab.com/badge/N/A-green.svg)

###  get_call_total_number_status_connected
  * <u>Description :</u> Retourne le nombre total d'appels dont le statut est Connected
  * <u>Versions SNMP :</u> ![SNMPv2c](https://custom-icon-badges.demolab.com/badge/SNMPv2c-royalblue.svg?logo=activity&logoSource=feather) ![SNMPv3](https://custom-icon-badges.demolab.com/badge/SNMPv3-olivedrab.svg?logo=activity&logoSource=feather)
  * <u>Paramètres Spécifiques :</u> ![N/A](https://custom-icon-badges.demolab.com/badge/N/A-green.svg)

###  get_call_total_number_status_disconnected
  * <u>Description :</u> Retourne le nombre total d'appels dont le statut est Disconnected
  * <u>Versions SNMP :</u> ![SNMPv2c](https://custom-icon-badges.demolab.com/badge/SNMPv2c-royalblue.svg?logo=activity&logoSource=feather) ![SNMPv3](https://custom-icon-badges.demolab.com/badge/SNMPv3-olivedrab.svg?logo=activity&logoSource=feather)
  * <u>Paramètres Spécifiques :</u> ![N/A](https://custom-icon-badges.demolab.com/badge/N/A-green.svg)

###  get_call_total_number_status_disconnecting
  * <u>Description :</u> Retourne le nombre total d'appels dont le statut est Disconnecting
  * <u>Versions SNMP :</u> ![SNMPv2c](https://custom-icon-badges.demolab.com/badge/SNMPv2c-royalblue.svg?logo=activity&logoSource=feather) ![SNMPv3](https://custom-icon-badges.demolab.com/badge/SNMPv3-olivedrab.svg?logo=activity&logoSource=feather)
  * <u>Paramètres Spécifiques :</u> ![N/A](https://custom-icon-badges.demolab.com/badge/N/A-green.svg)

###  get_call_total_number_status_establishing
  * <u>Description :</u> Retourne le nombre total d'appels dont le statut est Establishing
  * <u>Versions SNMP :</u> ![SNMPv2c](https://custom-icon-badges.demolab.com/badge/SNMPv2c-royalblue.svg?logo=activity&logoSource=feather) ![SNMPv3](https://custom-icon-badges.demolab.com/badge/SNMPv3-olivedrab.svg?logo=activity&logoSource=feather)
  * <u>Paramètres Spécifiques :</u> ![N/A](https://custom-icon-badges.demolab.com/badge/N/A-green.svg)

###  get_call_total_number_status_in_progress
  * <u>Description :</u> Retourne le nombre total d'appels dont le statut est In-Progress
  * <u>Versions SNMP :</u> ![SNMPv2c](https://custom-icon-badges.demolab.com/badge/SNMPv2c-royalblue.svg?logo=activity&logoSource=feather) ![SNMPv3](https://custom-icon-badges.demolab.com/badge/SNMPv3-olivedrab.svg?logo=activity&logoSource=feather)
  * <u>Paramètres Spécifiques :</u> ![N/A](https://custom-icon-badges.demolab.com/badge/N/A-green.svg)

###  get_call_total_number_not_via_mtp
  * <u>Description :</u> Retourne le nombre total d'appels n'utilisant pas de MTP
  * <u>Versions SNMP :</u> ![SNMPv2c](https://custom-icon-badges.demolab.com/badge/SNMPv2c-royalblue.svg?logo=activity&logoSource=feather) ![SNMPv3](https://custom-icon-badges.demolab.com/badge/SNMPv3-olivedrab.svg?logo=activity&logoSource=feather)
  * <u>Paramètres Spécifiques :</u> ![N/A](https://custom-icon-badges.demolab.com/badge/N/A-green.svg)

###  get_call_total_number_via_mtp
  * <u>Description :</u> Retourne le nombre total d'appels utilisant un MTP
  * <u>Versions SNMP :</u> ![SNMPv2c](https://custom-icon-badges.demolab.com/badge/SNMPv2c-royalblue.svg?logo=activity&logoSource=feather) ![SNMPv3](https://custom-icon-badges.demolab.com/badge/SNMPv3-olivedrab.svg?logo=activity&logoSource=feather)
  * <u>Paramètres Spécifiques :</u> ![N/A](https://custom-icon-badges.demolab.com/badge/N/A-green.svg)

###  get_call_total_number_joined
  * <u>Description :</u> Retourne le nombre total d'appels joints
  * <u>Versions SNMP :</u> ![SNMPv2c](https://custom-icon-badges.demolab.com/badge/SNMPv2c-royalblue.svg?logo=activity&logoSource=feather) ![SNMPv3](https://custom-icon-badges.demolab.com/badge/SNMPv3-olivedrab.svg?logo=activity&logoSource=feather)
  * <u>Paramètres Spécifiques :</u> ![N/A](https://custom-icon-badges.demolab.com/badge/N/A-green.svg)

###  get_call_total_number_single
  * <u>Description :</u> Retourne le nombre total d'appels simples
  * <u>Versions SNMP :</u> ![SNMPv2c](https://custom-icon-badges.demolab.com/badge/SNMPv2c-royalblue.svg?logo=activity&logoSource=feather) ![SNMPv3](https://custom-icon-badges.demolab.com/badge/SNMPv3-olivedrab.svg?logo=activity&logoSource=feather)
  * <u>Paramètres Spécifiques :</u> ![N/A](https://custom-icon-badges.demolab.com/badge/N/A-green.svg)


## Section MTP

###  get_mtp_total_number

###  get_mtp_index

###  get_mtp_existence

###  get_mtp_address

###  get_mtp_status

###  get_mtp_saturation

###  get_mtp_saturation_percentage

###  get_mtp_version


## Section Cluster

###  get_cluster_id

###  get_cluster_canal_number

###  get_cluster_polling_delay

###  get_cluster_total_number_members


## Section TrunkStat

###  get_trunk_total_number

###  get_trunk_index

###  get_trunk_existence

###  get_trunk_max_capacity

###  get_trunk_active_calls_number

###  get_trunk_saturation

###  get_trunk_saturation_percentage

###  get_trunk_concurrent_calls_max_number

###  get_trunk_total_number_calls
