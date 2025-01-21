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

###  get_endpoint_index

###  get_endpoint_type

###  get_endpoint_total_number_media_entity

###  get_endpoint_total_number_registered

###  get_endpoint_total_number_static_in

###  get_endpoint_total_number_static_out

###  get_endpoint_protocol

###  get_endpoint_total_number_h323

###  get_endpoint_total_number_sip_tcp

###  get_endpoint_total_number_sip_tls

###  get_endpoint_total_number_sip_udp

###  get_endpoint_existence

###  get_endpoint_ttl

###  get_endpoint_remote_ip

###  get_endpoint_remote_port

###  get_endpoint_local_ip

###  get_endpoint_local_port

###  get_endpoint_product_id

###  get_endpoint_registrar_mode

###  get_endpoint_total_not_registrar_mode

###  get_endpoint_total_registrar_mode

###  get_endpoint_registrar_status

###  get_endpoint_total_status_not_registered

###  get_endpoint_total_status_registered

###  get_endpoint_supervision_status

###  get_endpoint_total_number_not_supervised

###  get_endpoint_total_number_down

###  get_endpoint_total_number_up


## Section Calls

###  get_call_total_number

###  get_call_total_number_g711a_legs

###  get_call_total_number_g711u_legs

###  get_call_total_number_g722_legs

###  get_call_total_number_g729_legs

###  get_call_total_number_ilbc_legs

###  get_call_total_number_opus_legs

###  get_call_total_number_raw_legs

###  get_call_total_number_not_srtp_legs

###  get_call_total_number_srtp_legs

###  get_call_total_number_status_alerting

###  get_call_total_number_status_connected

###  get_call_total_number_status_disconnected

###  get_call_total_number_status_disconnecting

###  get_call_total_number_status_establishing

###  get_call_total_number_status_in_progress

###  get_call_total_number_not_via_mtp

###  get_call_total_number_via_mtp

###  get_call_total_number_joined

###  get_call_total_number_single


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
