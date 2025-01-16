# Mise en service

## Phase 1 - Installation du module Commons

Le module outil ***Commons*** permet le fonctionnement des modules opérationnels ainsi que la gestion du Licensing.

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
<u>Note :</u> Une attention particulière est à porter sur la différence entre la plateforme depuis laquelle seront téléchargées les dépendances et celle qui recevra l'installation du module ***Commons***. Les options --platform, --python-version, --implementation, et --abi peuvent être à utiliser en fonction des cas.

  2. Copier les dépendances téléchargées et le module ***Commons*** sur la machine qui recevra l'installation du module ***Commons*** et entrer les commandes suivantes :
```bash
pip install --force-reinstall --no-index --find-links=/tmp /tmp/l06p_supervision_modules_commons-*.whl
```

## Phase 2 - Génération du Fingerprint

Entrer les commandes suivantes :
```bash
l06p_get_fingerprint > /tmp/fingerprint.txt
```

## Phase 3 - Commande

Joindre à la commande les éléments suivants : 
  * le fichier fingerprint.txt ou son contenu,
  * la liste des modules à activer.

<u>Note :</u> En cas de commande groupée pour plusieurs machine, fournir le Fingerprint de chaque machine ainsi que la liste des modules à activer pour chacune des machines.

En retour, ***L06P Software*** retourne un fichier licence.txt par machine.