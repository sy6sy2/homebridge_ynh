# Homebridge pour YunoHost

[![Integration level](https://dash.yunohost.org/integration/homebridge.svg)](https://dash.yunohost.org/appci/app/homebridge)  
[![Install homebridge with YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=homebridge)

*[Read this readme in english.](./README.md)* 

> *Ce package vous permet d'installer Homebridge et Homebridge Config UI X rapidement et simplement sur un serveur Yunohost.  
Si vous n'avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l'installer et en profiter.*

## Point important à lire avant l’installation

**Homebridge** nécessite un **root domaine** dédié, ex. homebridge.domain.tld

## Vue d'ensemble
Homebridge is a lightweight NodeJS server that emulates the iOS HomeKit API.
Homebridge Config UI X is a Homebridge Web UI plugin to monitor, manage and control Homebridge from a browser.

**Version incluse:**
* Homebridge : 0.4.50
* Homebridge Config UI X : 4.6.2

## Captures d'écran

![](https://github.com/oznu/homebridge-config-ui-x/raw/master/screenshots/homebridge-config-ui-x-accessories.png)
![](https://camo.githubusercontent.com/e9e98b1b146452a6987e4a05dd4ece8c34781643/68747470733a2f2f6d656469612e67697068792e636f6d2f6d656469612f31306c373949436f6854753469512f67697068792e676966)

## Configuration

Une fois le paquet Homebridge installé, allez à l'URL choisie et suivez les instructions de l'assistant de configuration.

## Documentation

 * Documentation officielle :
    * Homebridge : https://github.com/nfarina/homebridge/wiki
    * Homebridge Config UI X : https://github.com/oznu/homebridge-config-ui-x/wiki

## Caractéristiques spécifiques YunoHost

#### Architectures supportées

* x86-64b - [![Build Status](https://ci-apps.yunohost.org/ci/logs/homebridge%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/homebridge/)
* x86-32b - [![Build Status](https://ci-stretch.nohost.me/ci/logs/homebridge%20%28Apps%29.svg)](https://ci-stretch.nohost.me/ci/apps/homebridge/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/homebridge%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/homebridge/)


## Liens

 * Signaler un bug: https://github.com/SylvainCecchetto/homebridge_ynh/issues
 * Site de l'application: https://homebridge.io
 * Dépôt de l'application principale:
    * Homebridge : https://github.com/nfarina/homebridge
    * Homebridge Config UI X : https://github.com/oznu/homebridge-config-ui-x
 * Site web YunoHost: https://yunohost.org/

---

Informations pour les développeurs
----------------

**Seulement si vous voulez utiliser une branche de test pour le codage, au lieu de fusionner directement dans la banche principale.**
Merci de faire vos pull request sur la [branche testing](https://github.com/SylvainCecchetto/homebridge_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/SylvainCecchetto/homebridge_ynh/tree/testing --debug
ou
sudo yunohost app upgrade homebridge -u https://github.com/SylvainCecchetto/homebridge_ynh/tree/testing --debug
```
