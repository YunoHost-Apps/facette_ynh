# Facette for YunoHost

[![Integration level](https://dash.yunohost.org/integration/facette.svg)](https://dash.yunohost.org/appci/app/facette) ![](https://ci-apps.yunohost.org/ci/badges/facette.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/facette.maintain.svg)  
[![Install Facette with YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=facette)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Facette quickly and simply on a YunoHost server.  
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview
Facette is a web application to display time series data from various sources — such as collectd, Graphite, InfluxDB or KairosDB — on graphs, designed to be easy to setup and to use.

**Shipped version:** 0.37.0

## Screenshots

![](https://facette.io/assets/images/sshot-view1.png)

## Demo

* [Official demo](https://play.facette.io/browse/)

## Configuration

## Documentation

 * Official documentation: 
 * YunoHost documentation: https://yunohost.org/#/app_facette

## YunoHost specific features

#### Multi-user support

* Is LDAP supported? **No**
* Can the app be used by multiple users? **Yes**

#### Supported architectures

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/facette%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/facette/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/facette%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/facette/)

## Links

 * Report a bug: https://github.com/YunoHost-Apps/facette_ynh/issues
 * App website: https://facette.io/
 * Upstream app repository: https://github.com/facette/facette
 * YunoHost website: https://yunohost.org/

---

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/facette_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/facette_ynh/tree/testing --debug
or
sudo yunohost app upgrade facette -u https://github.com/YunoHost-Apps/facette_ynh/tree/testing --debug
```
