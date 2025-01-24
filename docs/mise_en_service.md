# Mise en service

!!! warning "Sudo or not Sudo!"
    Il est important d'installer les modules en réalisant une élévation de privilèges lors de l'utilisation de la commande `pip install`.  
    Sans ceci, les scripts seront installés dans le répertoire `~/.local/bin` de l'utilisateur courant, pouvant provoquer une inaccessibilité par les processus fils de l'application de supervision.  
    L'utilisation des droits Root via la commande `sudo pip install` permet une installation des scripts dans le répertoire `/usr/local/bin` accessible de tous.

## Phase 1 - Récupération des modules

Les modules sont accessibles sur le dépôt Github [l06p/supervision_modules](https://github.com/l06p/ "Dépôt L06P Supervision Modules")

Pour les télécharger, plusieurs options sont possibles : 

  * Directement depuis le navigateur Web,
  * En clonant le dépôt via les commandes suivantes : 
  ```bash 
  git clone https://github.com/l06p/supervision_modules.git
  ```

## Phase 2 - Installation du module Commons

Le module outil ***Commons*** permet le fonctionnement des modules opérationnels ainsi que la gestion du Licensing.  
Celui-ci est à installer sur chaque machine nécessitant l'utilisation des modules de supervision édités par ***L06P Software***.

### Environnement ayant accès à Pypi

Entrer les commandes suivantes :
```bash
sudo pip install --force-reinstall /tmp/l06p_supervision_modules_commons-*.whl
```

### Environnement ayant accès à un dépôt privé

Entrer les commandes suivantes :
```bash
sudo pip install --force-reinstall --extra-index-url /tmp/l06p_supervision_modules_commons-*.whl
```

### Environnement complètement déconnecté

  1. Depuis un poste ayant accès à Pypi, à l'aide du fichier requirements.txt fournis, entrer les commandes suivantes :
```bash
pip download -r requirements.txt
```
<u>Note :</u> Une attention particulière est à porter sur la différence entre la plateforme depuis laquelle seront téléchargées les dépendances et celle qui recevra l'installation du module ***Commons***.  
Les options --platform, --python-version, --implementation, et --abi peuvent être à utiliser en fonction des cas.

  2. Copier les dépendances téléchargées et le module ***Commons*** sur la machine qui recevra l'installation du module ***Commons*** et entrer les commandes suivantes :
```bash
sudo pip install --force-reinstall --no-index --find-links=/tmp /tmp/l06p_supervision_modules_commons-*.whl
```

## Phase 3 - Génération du Fingerprint

Sur chacune des machines nécessitant l'utilisation de modules de supervision édités par ***L06P Software***, entrer les commandes suivantes :
```bash
l06p_get_fingerprint > /tmp/fingerprint.txt
```

## Phase 4 - Commande

Joindre à la commande de souscription les éléments suivants : 
  
  * le fichier *fingerprint.txt* ou son contenu,
  * la liste des modules à activer.

<u>Note :</u> En cas de commande groupée pour plusieurs machines, fournir le Fingerprint de chaque machine ainsi que la liste des modules à activer pour chacune des machines.

En retour, ***L06P Software*** transmet un fichier *l06p_licence.lic* par machine.

## Phase 5 - Installation de la Licence

Copier le fichier *l06p_licence.lic* fournit par ***L06P Software*** dans le répertoire */tmp* de la machine à laquelle celui-ci est destiné, puis entrer les commandes suivantes :
```bash
sudo mkdir -m 777 /usr/local/etc/l06p
install -m 644 /tmp/l06p_licence.lic /usr/local/etc/l06p/l06p_licence.lic
```

## Phase 6 - Installation des modules

Pour faciliter l'utilisation, les dépendances externes de l'intégralité des modules opérationnels sont reportées en tant que dépendances du module ***Commons***.  
Ainsi, pour les modules opérationnels, l'installation des dépendances externes n'est pas nécessaire du fait que celles-ci ont déjà été installées lors de l'installation du module ***Commons***.  

Les méthodes d'installation décrites dans la Phase 2 peuvent être utilisées pour l'installation des modules opérationnels, en modifiant :

  * l06p_supervision_modules_commons-\*.whl par l06p_supervision_modules_\*.whl pour l'installation des tous les modules opérationnels,
  * l06p_supervision_modules_commons-\*.whl par le fichier du module pour l'installation unitaire d'un module.