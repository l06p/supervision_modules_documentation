# Mise en service

## Phase 1 - Installation du module Commons

Le module outil ***Commons*** permet le fonctionnement des modules opérationnels ainsi que la gestion du Licensing.  
Celui-ci est à installer sur chaque machine nécessitant l'utilisation des modules de supervision édités par ***L06P Software***.

### Environnement ayant accès à Pypi

Entrer les commandes suivantes :
```bash
pip install --force-reinstall /tmp/l06p_supervision_modules_commons-*.whl
```

### Environnement ayant accès à un dépôt privé

Entrer les commandes suivantes :
```bash
pip install --force-reinstall --extra-index-url /tmp/l06p_supervision_modules_commons-*.whl
```

### Environnement complètement déconnecté

  1. Depuis un poste ayant accès à Pypi, à l'aide du fichier Requirements.txt fournis, entrer les commandes suivantes :
```bash
pip download -r requirements.txt
```
<u>Note :</u> Une attention particulière est à porter sur la différence entre la plateforme depuis laquelle seront téléchargées les dépendances et celle qui recevra l'installation du module ***Commons***.  
Les options --platform, --python-version, --implementation, et --abi peuvent être à utiliser en fonction des cas.

  2. Copier les dépendances téléchargées et le module ***Commons*** sur la machine qui recevra l'installation du module ***Commons*** et entrer les commandes suivantes :
```bash
pip install --force-reinstall --no-index --find-links=/tmp /tmp/l06p_supervision_modules_commons-*.whl
```

## Phase 2 - Génération du Fingerprint

Sur chacune des machines nécessitant l'utilisation de modules de supervision édités par ***L06P Software, entrer les commandes suivantes :
```bash
l06p_get_fingerprint > /tmp/fingerprint.txt
```

## Phase 3 - Commande

Joindre à la commande de souscription les éléments suivants : 
  
  * le fichier *fingerprint.txt* ou son contenu,
  * la liste des modules à activer.

<u>Note :</u> En cas de commande groupée pour plusieurs machines, fournir le Fingerprint de chaque machine ainsi que la liste des modules à activer pour chacune des machines.

En retour, ***L06P Software*** transmet un fichier *l06p_licence.lic* par machine.

## Phase 4 - Installation de la Licence

Copier le fichier *l06p_licence.lic* fournit par ***L06P Software*** dans le répertoire */tmp* de la machine à laquelle celui-ci est destiné, puis entrer les commandes suivantes :
```bash
sudo mkdir -m 777 /usr/local/etc/l06p
install -m 644 /tmp/l06p_licence.lic /usr/local/etc/l06p/l06p_licence.lic
```