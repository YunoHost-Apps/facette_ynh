<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# Facette pour YunoHost

[![Niveau d’intégration](https://dash.yunohost.org/integration/facette.svg)](https://dash.yunohost.org/appci/app/facette) ![Statut du fonctionnement](https://ci-apps.yunohost.org/ci/badges/facette.status.svg) ![Statut de maintenance](https://ci-apps.yunohost.org/ci/badges/facette.maintain.svg)

[![Installer Facette avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=facette)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer Facette rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

Facette is a web application to display time series data from various sources — such as collectd, Graphite, InfluxDB or KairosDB — on graphs, designed to be easy to setup and to use.

**Version incluse :** 0.5.1~ynh4

**Démo :** <https://play.facette.io/browse/>

## Captures d’écran

![Capture d’écran de Facette](./doc/screenshots/screenshot.png)

## :red_circle: Anti-fonctionnalités

- **Application non maintenue **: Ce logiciel n'est plus maintenu. Attendez-vous à ce qu'il ne fonctionne plus avec le temps, et que l'on découvre des failles de sécurité qui ne seront pas corrigées, etc.

## Documentations et ressources

- Site officiel de l’app : <https://facette.io/>
- Documentation officielle de l’admin : <https://docs.facette.io/>
- Dépôt de code officiel de l’app : <https://github.com/facette/facette>
- YunoHost Store : <https://apps.yunohost.org/app/facette>
- Signaler un bug : <https://github.com/YunoHost-Apps/facette_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/facette_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/facette_ynh/tree/testing --debug
ou
sudo yunohost app upgrade facette -u https://github.com/YunoHost-Apps/facette_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
