# Homebridge for YunoHost

[![Integration level](https://dash.yunohost.org/integration/homebridge.svg)](https://dash.yunohost.org/appci/app/homebridge)  
[![Install homebridge with YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=homebridge)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allow you to install Homebridge and Homebridge Config UI X quickly and simply on a YunoHost server.  
If you don't have YunoHost, please see [here](https://yunohost.org/#/install) to know how to install and enjoy it.*

## Important point to read before installing

**Homebridge** require a dedicated **root domain**, eg. homebridge.domain.tld

## Overview
Homebridge is a lightweight NodeJS server that emulates the iOS HomeKit API.
Homebridge Config UI X is a Homebridge Web UI plugin to monitor, manage and control Homebridge from a browser.

**Shipped version:**
* Homebridge: 0.4.50
* Homebridge Config UI X: 4.6.2

## Screenshots

![](https://github.com/oznu/homebridge-config-ui-x/raw/master/screenshots/homebridge-config-ui-x-accessories.png)
![](https://camo.githubusercontent.com/e9e98b1b146452a6987e4a05dd4ece8c34781643/68747470733a2f2f6d656469612e67697068792e636f6d2f6d656469612f31306c373949436f6854753469512f67697068792e676966)


## Configuration

Once the Homebridge package is installed, go to the chosen URL and follow the setup wizard.

## Documentation

 * Official documentation:
    * Homebridge: https://github.com/nfarina/homebridge
    * Homebridge Config UI X: https://github.com/oznu/homebridge-config-ui-x/wiki

## YunoHost specific features

#### Supported architectures

* x86-64b - [![Build Status](https://ci-apps.yunohost.org/ci/logs/homebridge%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/homebridge/)
* x86-32b - [![Build Status](https://ci-stretch.nohost.me/ci/logs/homebridge%20%28Apps%29.svg)](https://ci-stretch.nohost.me/ci/apps/homebridge/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/homebridge%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/homebridge/)



## Links

 * Report a bug: https://github.com/SylvainCecchetto/homebridge_ynh/issues
 * App website: https://homebridge.io
 * Upstream app repository:
    * Homebridge: https://github.com/nfarina/homebridge/wiki
    * Homebridge Config UI X: https://github.com/oznu/homebridge-config-ui-x
 * YunoHost website: https://yunohost.org/

---

Developers info
----------------

**Only if you want to use a testing branch for coding, instead of merging directly into master.**
Please do your pull request to the [testing branch](https://github.com/SylvainCecchetto/homebridge_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/SylvainCecchetto/homebridge_ynh/tree/testing --debug
or
sudo yunohost app upgrade homebridge -u https://github.com/SylvainCecchetto/homebridge_ynh/tree/testing --debug
```
