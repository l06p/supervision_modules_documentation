# Descriptifs des scripts M2MSoft/generic

## Nommage
Le nommage des scripts est de la forme suivante : **m2msoft_generic_**<*nom_du_script*\>**_[v2c/v3]**.

## Section Sytème

### get_system_uptime
  * <u>Description :</u> Retourne l'uptime en secondes du serveur
  * <u>Versions SNMP :</u> ![SNMPv2c](https://custom-icon-badges.demolab.com/badge/SNMPv2c-royalblue.svg?logo=activity&logoSource=feather) ![SNMPv3](https://custom-icon-badges.demolab.com/badge/SNMPv3-olivedrab.svg?logo=activity&logoSource=feather)
  * <u>Paramètres Spécifiques :</u> ![N/A](https://custom-icon-badges.demolab.com/badge/N/A-green.svg)

### get_system_agent_version
  * <u>Description :</u> Retourne la version de l'agent SNMP M2MSoft
  * <u>Versions SNMP :</u> ![SNMPv2c](https://custom-icon-badges.demolab.com/badge/SNMPv2c-royalblue.svg?logo=activity&logoSource=feather) ![SNMPv3](https://custom-icon-badges.demolab.com/badge/SNMPv3-olivedrab.svg?logo=activity&logoSource=feather)
  * <u>Paramètres Spécifiques :</u> ![N/A](https://custom-icon-badges.demolab.com/badge/N/A-green.svg)

### get_system_hostname
  * <u>Description :</u> Retourne le nom d'hôte du serveur
  * <u>Versions SNMP :</u> ![SNMPv2c](https://custom-icon-badges.demolab.com/badge/SNMPv2c-royalblue.svg?logo=activity&logoSource=feather) ![SNMPv3](https://custom-icon-badges.demolab.com/badge/SNMPv3-olivedrab.svg?logo=activity&logoSource=feather)
  * <u>Paramètres Spécifiques :</u> ![N/A](https://custom-icon-badges.demolab.com/badge/N/A-green.svg)

### get_system_location
  * <u>Description :</u> Retourne la localisation du serveur
  * <u>Versions SNMP :</u> ![SNMPv2c](https://custom-icon-badges.demolab.com/badge/SNMPv2c-royalblue.svg?logo=activity&logoSource=feather) ![SNMPv3](https://custom-icon-badges.demolab.com/badge/SNMPv3-olivedrab.svg?logo=activity&logoSource=feather)
  * <u>Paramètres Spécifiques :</u> ![N/A](https://custom-icon-badges.demolab.com/badge/N/A-green.svg)

### get_system_os_description
  * <u>Description :</u> Retourne la description du système d'exploitation du serveur
  * <u>Versions SNMP :</u> ![SNMPv2c](https://custom-icon-badges.demolab.com/badge/SNMPv2c-royalblue.svg?logo=activity&logoSource=feather) ![SNMPv3](https://custom-icon-badges.demolab.com/badge/SNMPv3-olivedrab.svg?logo=activity&logoSource=feather)
  * <u>Paramètres Spécifiques :</u> ![N/A](https://custom-icon-badges.demolab.com/badge/N/A-green.svg)

### get_system_jvm_description
  * <u>Description :</u> Retourne le nom et la version de la JVM embarquée par le serveur
  * <u>Versions SNMP :</u> ![SNMPv2c](https://custom-icon-badges.demolab.com/badge/SNMPv2c-royalblue.svg?logo=activity&logoSource=feather) ![SNMPv3](https://custom-icon-badges.demolab.com/badge/SNMPv3-olivedrab.svg?logo=activity&logoSource=feather)
  * <u>Paramètres Spécifiques :</u> ![N/A](https://custom-icon-badges.demolab.com/badge/N/A-green.svg)

### get_system_vendor
  * <u>Description :</u> Retourne l'identification de l'éditeur de l'agent SNMP
  * <u>Versions SNMP :</u> ![SNMPv2c](https://custom-icon-badges.demolab.com/badge/SNMPv2c-royalblue.svg?logo=activity&logoSource=feather) ![SNMPv3](https://custom-icon-badges.demolab.com/badge/SNMPv3-olivedrab.svg?logo=activity&logoSource=feather)
  * <u>Paramètres Spécifiques :</u> ![N/A](https://custom-icon-badges.demolab.com/badge/N/A-green.svg)

## Section Interfaces

### get_interface_total_number
  * <u>Description :</u> Retourne le nombre total d'interfaces réseau du serveur
  * <u>Versions SNMP :</u> ![SNMPv2c](https://custom-icon-badges.demolab.com/badge/SNMPv2c-royalblue.svg?logo=activity&logoSource=feather) ![SNMPv3](https://custom-icon-badges.demolab.com/badge/SNMPv3-olivedrab.svg?logo=activity&logoSource=feather)
  * <u>Paramètres Spécifiques :</u> ![N/A](https://custom-icon-badges.demolab.com/badge/N/A-green.svg)

### get_interface_index
  * <u>Description :</u> Retourne l'index dans la MIB de l'interface réseau précisée en paramètre
  * <u>Versions SNMP :</u> ![SNMPv2c](https://custom-icon-badges.demolab.com/badge/SNMPv2c-royalblue.svg?logo=activity&logoSource=feather) ![SNMPv3](https://custom-icon-badges.demolab.com/badge/SNMPv3-olivedrab.svg?logo=activity&logoSource=feather)
  * <u>Paramètres Spécifiques :</u> ![INTERFACE_NAME](https://custom-icon-badges.demolab.com/badge/--n/----name-INTERFACE__NAME-violet.svg) Le nom de l'interface réseau

### get_interface_existence
  * <u>Description :</u> Retourne l'existance ou non de l'interface réseau précisée en paramètre
  * <u>Versions SNMP :</u> ![SNMPv2c](https://custom-icon-badges.demolab.com/badge/SNMPv2c-royalblue.svg?logo=activity&logoSource=feather) ![SNMPv3](https://custom-icon-badges.demolab.com/badge/SNMPv3-olivedrab.svg?logo=activity&logoSource=feather)
  * <u>Paramètres Spécifiques :</u> ![INTERFACE_NAME](https://custom-icon-badges.demolab.com/badge/--n/----name-INTERFACE__NAME-violet.svg) Le nom de l'interface réseau

### get_interface_mac_address
  * <u>Description :</u> Retourne l'adresse MAC de l'interface réseau précisée en paramètre
  * <u>Versions SNMP :</u> ![SNMPv2c](https://custom-icon-badges.demolab.com/badge/SNMPv2c-royalblue.svg?logo=activity&logoSource=feather) ![SNMPv3](https://custom-icon-badges.demolab.com/badge/SNMPv3-olivedrab.svg?logo=activity&logoSource=feather)
  * <u>Paramètres Spécifiques :</u> ![INTERFACE_NAME](https://custom-icon-badges.demolab.com/badge/--n/----name-INTERFACE__NAME-violet.svg) Le nom de l'interface réseau

### get_interface_ip_address
  * <u>Description :</u> Retourne l'adresse IP de l'interface réseau précisée en paramètre
  * <u>Versions SNMP :</u> ![SNMPv2c](https://custom-icon-badges.demolab.com/badge/SNMPv2c-royalblue.svg?logo=activity&logoSource=feather) ![SNMPv3](https://custom-icon-badges.demolab.com/badge/SNMPv3-olivedrab.svg?logo=activity&logoSource=feather)
  * <u>Paramètres Spécifiques :</u> ![INTERFACE_NAME](https://custom-icon-badges.demolab.com/badge/--n/----name-INTERFACE__NAME-violet.svg) Le nom de l'interface réseau

### get_interface_netmask
  * <u>Description :</u> Retourne le masque de sous-réseau de l'interface réseau précisée en paramètre
  * <u>Versions SNMP :</u> ![SNMPv2c](https://custom-icon-badges.demolab.com/badge/SNMPv2c-royalblue.svg?logo=activity&logoSource=feather) ![SNMPv3](https://custom-icon-badges.demolab.com/badge/SNMPv3-olivedrab.svg?logo=activity&logoSource=feather)
  * <u>Paramètres Spécifiques :</u> ![INTERFACE_NAME](https://custom-icon-badges.demolab.com/badge/--n/----name-INTERFACE__NAME-violet.svg) Le nom de l'interface réseau

### get_interface_speed
  * <u>Description :</u> Retourne la vitesse de l'interface réseau précisée en paramètre
  * <u>Versions SNMP :</u> ![SNMPv2c](https://custom-icon-badges.demolab.com/badge/SNMPv2c-royalblue.svg?logo=activity&logoSource=feather) ![SNMPv3](https://custom-icon-badges.demolab.com/badge/SNMPv3-olivedrab.svg?logo=activity&logoSource=feather)
  * <u>Paramètres Spécifiques :</u> ![INTERFACE_NAME](https://custom-icon-badges.demolab.com/badge/--n/----name-INTERFACE__NAME-violet.svg) Le nom de l'interface réseau

### get_interface_status
  * <u>Description :</u> Retourne le statut de l'interface réseau précisée en paramètre
  * <u>Versions SNMP :</u> ![SNMPv2c](https://custom-icon-badges.demolab.com/badge/SNMPv2c-royalblue.svg?logo=activity&logoSource=feather) ![SNMPv3](https://custom-icon-badges.demolab.com/badge/SNMPv3-olivedrab.svg?logo=activity&logoSource=feather)
  * <u>Paramètres Spécifiques :</u> ![INTERFACE_NAME](https://custom-icon-badges.demolab.com/badge/--n/----name-INTERFACE__NAME-violet.svg) Le nom de l'interface réseau

## Section CPU

### get_cpu_core_total_number
  * <u>Description :</u> Retourne le nombre total de coeurs dont dispose le processeur
  * <u>Versions SNMP :</u> ![SNMPv2c](https://custom-icon-badges.demolab.com/badge/SNMPv2c-royalblue.svg?logo=activity&logoSource=feather) ![SNMPv3](https://custom-icon-badges.demolab.com/badge/SNMPv3-olivedrab.svg?logo=activity&logoSource=feather)
  * <u>Paramètres Spécifiques :</u> ![N/A](https://custom-icon-badges.demolab.com/badge/N/A-green.svg)

### get_cpu_load_1_minute
  * <u>Description :</u> Retourne la moyenne de charge processeur sur 1 minute
  * <u>Versions SNMP :</u> ![SNMPv2c](https://custom-icon-badges.demolab.com/badge/SNMPv2c-royalblue.svg?logo=activity&logoSource=feather) ![SNMPv3](https://custom-icon-badges.demolab.com/badge/SNMPv3-olivedrab.svg?logo=activity&logoSource=feather)
  * <u>Paramètres Spécifiques :</u> ![N/A](https://custom-icon-badges.demolab.com/badge/N/A-green.svg)

### get_cpu_load_5_minutes
  * <u>Description :</u> Retourne la moyenne de charge processeur sur 5 minutes
  * <u>Versions SNMP :</u> ![SNMPv2c](https://custom-icon-badges.demolab.com/badge/SNMPv2c-royalblue.svg?logo=activity&logoSource=feather) ![SNMPv3](https://custom-icon-badges.demolab.com/badge/SNMPv3-olivedrab.svg?logo=activity&logoSource=feather)
  * <u>Paramètres Spécifiques :</u> ![N/A](https://custom-icon-badges.demolab.com/badge/N/A-green.svg)

### get_cpu_load_15_minutes
  * <u>Description :</u> Retourne la moyenne de charge processeur sur 15 minutes
  * <u>Versions SNMP :</u> ![SNMPv2c](https://custom-icon-badges.demolab.com/badge/SNMPv2c-royalblue.svg?logo=activity&logoSource=feather) ![SNMPv3](https://custom-icon-badges.demolab.com/badge/SNMPv3-olivedrab.svg?logo=activity&logoSource=feather)
  * <u>Paramètres Spécifiques :</u> ![N/A](https://custom-icon-badges.demolab.com/badge/N/A-green.svg)

### get_cpu_usage
  * <u>Description :</u> Retourne le pourcentage d'utilisation instantannée des CPU
  * <u>Versions SNMP :</u> ![SNMPv2c](https://custom-icon-badges.demolab.com/badge/SNMPv2c-royalblue.svg?logo=activity&logoSource=feather) ![SNMPv3](https://custom-icon-badges.demolab.com/badge/SNMPv3-olivedrab.svg?logo=activity&logoSource=feather)
  * <u>Paramètres Spécifiques :</u> ![N/A](https://custom-icon-badges.demolab.com/badge/N/A-green.svg)

### get_cpu_usage_10_minutes
  * <u>Description :</u> Retourne la moyenne du pourcentage d'utilisation des CPU sur 10 minutes
  * <u>Versions SNMP :</u> ![SNMPv2c](https://custom-icon-badges.demolab.com/badge/SNMPv2c-royalblue.svg?logo=activity&logoSource=feather) ![SNMPv3](https://custom-icon-badges.demolab.com/badge/SNMPv3-olivedrab.svg?logo=activity&logoSource=feather)
  * <u>Paramètres Spécifiques :</u> ![N/A](https://custom-icon-badges.demolab.com/badge/N/A-green.svg)

### get_cpu_user_usage
  * <u>Description :</u> Retourne le pourcentage d'utilisation des CPU par les processus utilisateur
  * <u>Versions SNMP :</u> ![SNMPv2c](https://custom-icon-badges.demolab.com/badge/SNMPv2c-royalblue.svg?logo=activity&logoSource=feather) ![SNMPv3](https://custom-icon-badges.demolab.com/badge/SNMPv3-olivedrab.svg?logo=activity&logoSource=feather)
  * <u>Paramètres Spécifiques :</u> ![N/A](https://custom-icon-badges.demolab.com/badge/N/A-green.svg)

### get_cpu_system_usage
  * <u>Description :</u> Retourne le pourcentage d'utilisation des CPU par les processus système
  * <u>Versions SNMP :</u> ![SNMPv2c](https://custom-icon-badges.demolab.com/badge/SNMPv2c-royalblue.svg?logo=activity&logoSource=feather) ![SNMPv3](https://custom-icon-badges.demolab.com/badge/SNMPv3-olivedrab.svg?logo=activity&logoSource=feather)
  * <u>Paramètres Spécifiques :</u> ![N/A](https://custom-icon-badges.demolab.com/badge/N/A-green.svg)

### get_cpu_idle
  * <u>Description :</u> Retourne le pourcentage de temps passé en attente par les CPU
  * <u>Versions SNMP :</u> ![SNMPv2c](https://custom-icon-badges.demolab.com/badge/SNMPv2c-royalblue.svg?logo=activity&logoSource=feather) ![SNMPv3](https://custom-icon-badges.demolab.com/badge/SNMPv3-olivedrab.svg?logo=activity&logoSource=feather)
  * <u>Paramètres Spécifiques :</u> ![N/A](https://custom-icon-badges.demolab.com/badge/N/A-green.svg)


## Section Mémoire

### get_memory_total_ram
  * <u>Description :</u> Retourne la taille totale en Octets de RAM
  * <u>Versions SNMP :</u> ![SNMPv2c](https://custom-icon-badges.demolab.com/badge/SNMPv2c-royalblue.svg?logo=activity&logoSource=feather) ![SNMPv3](https://custom-icon-badges.demolab.com/badge/SNMPv3-olivedrab.svg?logo=activity&logoSource=feather)
  * <u>Paramètres Spécifiques :</u> ![N/A](https://custom-icon-badges.demolab.com/badge/N/A-green.svg)

### get_memory_free_ram
  * <u>Description :</u> Retourne la taille totale en Octets de RAM non utilisée
  * <u>Versions SNMP :</u> ![SNMPv2c](https://custom-icon-badges.demolab.com/badge/SNMPv2c-royalblue.svg?logo=activity&logoSource=feather) ![SNMPv3](https://custom-icon-badges.demolab.com/badge/SNMPv3-olivedrab.svg?logo=activity&logoSource=feather)
  * <u>Paramètres Spécifiques :</u> ![N/A](https://custom-icon-badges.demolab.com/badge/N/A-green.svg)

### get_memory_ram_saturation_percentage
  * <u>Description :</u> Retourne le pourcentage de saturation de la RAM
  * <u>Versions SNMP :</u> ![SNMPv2c](https://custom-icon-badges.demolab.com/badge/SNMPv2c-royalblue.svg?logo=activity&logoSource=feather) ![SNMPv3](https://custom-icon-badges.demolab.com/badge/SNMPv3-olivedrab.svg?logo=activity&logoSource=feather)
  * <u>Paramètres Spécifiques :</u> ![N/A](https://custom-icon-badges.demolab.com/badge/N/A-green.svg)

### get_memory_total_swap
  * <u>Description :</u> Retourne la taille totale en Octets du SWAP
  * <u>Versions SNMP :</u> ![SNMPv2c](https://custom-icon-badges.demolab.com/badge/SNMPv2c-royalblue.svg?logo=activity&logoSource=feather) ![SNMPv3](https://custom-icon-badges.demolab.com/badge/SNMPv3-olivedrab.svg?logo=activity&logoSource=feather)
  * <u>Paramètres Spécifiques :</u> ![N/A](https://custom-icon-badges.demolab.com/badge/N/A-green.svg)

### get_memory_free_swap
  * <u>Description :</u> Retourne la taille totale en Octets de SWAP non utilisée
  * <u>Versions SNMP :</u> ![SNMPv2c](https://custom-icon-badges.demolab.com/badge/SNMPv2c-royalblue.svg?logo=activity&logoSource=feather) ![SNMPv3](https://custom-icon-badges.demolab.com/badge/SNMPv3-olivedrab.svg?logo=activity&logoSource=feather)
  * <u>Paramètres Spécifiques :</u> ![N/A](https://custom-icon-badges.demolab.com/badge/N/A-green.svg)

### get_memory_swap_saturation_percentage
  * <u>Description :</u> Retourne le pourcentage de saturation du SWAP
  * <u>Versions SNMP :</u> ![SNMPv2c](https://custom-icon-badges.demolab.com/badge/SNMPv2c-royalblue.svg?logo=activity&logoSource=feather) ![SNMPv3](https://custom-icon-badges.demolab.com/badge/SNMPv3-olivedrab.svg?logo=activity&logoSource=feather)
  * <u>Paramètres Spécifiques :</u> ![N/A](https://custom-icon-badges.demolab.com/badge/N/A-green.svg)


# Section Partitions

### get_partition_total_number
  * <u>Description :</u> Retourne le nombre total de partitions du serveur
  * <u>Versions SNMP :</u> ![SNMPv2c](https://custom-icon-badges.demolab.com/badge/SNMPv2c-royalblue.svg?logo=activity&logoSource=feather) ![SNMPv3](https://custom-icon-badges.demolab.com/badge/SNMPv3-olivedrab.svg?logo=activity&logoSource=feather)
  * <u>Paramètres Spécifiques :</u> ![N/A](https://custom-icon-badges.demolab.com/badge/N/A-green.svg)

### get_partition_index
  * <u>Description :</u> Retourne l'index dans la MIB de la partition précisée en paramètre
  * <u>Versions SNMP :</u> ![SNMPv2c](https://custom-icon-badges.demolab.com/badge/SNMPv2c-royalblue.svg?logo=activity&logoSource=feather) ![SNMPv3](https://custom-icon-badges.demolab.com/badge/SNMPv3-olivedrab.svg?logo=activity&logoSource=feather)
  * <u>Paramètres Spécifiques :</u> ![PARTITION_NAME](https://custom-icon-badges.demolab.com/badge/--n/----name-PARTITION__NAME-violet.svg) Le nom de la partition

### get_partition_existence
  * <u>Description :</u> Retourne l'existance ou non de la partition précisée en paramètre
  * <u>Versions SNMP :</u> ![SNMPv2c](https://custom-icon-badges.demolab.com/badge/SNMPv2c-royalblue.svg?logo=activity&logoSource=feather) ![SNMPv3](https://custom-icon-badges.demolab.com/badge/SNMPv3-olivedrab.svg?logo=activity&logoSource=feather)
  * <u>Paramètres Spécifiques :</u> ![PARTITION_NAME](https://custom-icon-badges.demolab.com/badge/--n/----name-PARTITION__NAME-violet.svg) Le nom de la partition

### get_partition_size
  * <u>Description :</u> Retourne la taille en Octets de la partition précisée en paramètre
  * <u>Versions SNMP :</u> ![SNMPv2c](https://custom-icon-badges.demolab.com/badge/SNMPv2c-royalblue.svg?logo=activity&logoSource=feather) ![SNMPv3](https://custom-icon-badges.demolab.com/badge/SNMPv3-olivedrab.svg?logo=activity&logoSource=feather)
  * <u>Paramètres Spécifiques :</u> ![PARTITION_NAME](https://custom-icon-badges.demolab.com/badge/--n/----name-PARTITION__NAME-violet.svg) Le nom de la partition

### get_partition_saturation_percentage
  * <u>Description :</u> Retourne le pourcentage de saturation de la partition précisée en paramètre
  * <u>Versions SNMP :</u> ![SNMPv2c](https://custom-icon-badges.demolab.com/badge/SNMPv2c-royalblue.svg?logo=activity&logoSource=feather) ![SNMPv3](https://custom-icon-badges.demolab.com/badge/SNMPv3-olivedrab.svg?logo=activity&logoSource=feather)
  * <u>Paramètres Spécifiques :</u> ![PARTITION_NAME](https://custom-icon-badges.demolab.com/badge/--n/----name-PARTITION__NAME-violet.svg) Le nom de la partition