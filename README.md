<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# Facette for YunoHost

[![Integration level](https://dash.yunohost.org/integration/facette.svg)](https://dash.yunohost.org/appci/app/facette) ![Working status](https://ci-apps.yunohost.org/ci/badges/facette.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/facette.maintain.svg)  
[![Install Facette with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=facette)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Facette quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

Facette is a web application to display time series data from various sources — such as collectd, Graphite, InfluxDB or KairosDB — on graphs, designed to be easy to setup and to use.

**Shipped version:** 0.5.1~ynh2

**Demo:** https://play.facette.io/browse/

## Screenshots

![Screenshot of Facette](./doc/screenshots/screenshot.png)

## Documentation and resources

* Official app website: <https://facette.io/>
* Official admin documentation: <https://docs.facette.io/>
* Upstream app code repository: <https://github.com/facette/facette>
* YunoHost documentation for this app: <https://yunohost.org/app_facette>
* Report a bug: <https://github.com/YunoHost-Apps/facette_ynh/issues>

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/facette_ynh/tree/testing).

To try the testing branch, please proceed like that.

``` bash
sudo yunohost app install https://github.com/YunoHost-Apps/facette_ynh/tree/testing --debug
or
sudo yunohost app upgrade facette -u https://github.com/YunoHost-Apps/facette_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
