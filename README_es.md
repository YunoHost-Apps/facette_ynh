<!--
Este archivo README esta generado automaticamente<https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
No se debe editar a mano.
-->

# Facette para Yunohost

[![Nivel de integración](https://dash.yunohost.org/integration/facette.svg)](https://dash.yunohost.org/appci/app/facette) ![Estado funcional](https://ci-apps.yunohost.org/ci/badges/facette.status.svg) ![Estado En Mantención](https://ci-apps.yunohost.org/ci/badges/facette.maintain.svg)

[![Instalar Facette con Yunhost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=facette)

*[Leer este README en otros idiomas.](./ALL_README.md)*

> *Este paquete le permite instalarFacette rapidamente y simplement en un servidor YunoHost.*  
> *Si no tiene YunoHost, visita [the guide](https://yunohost.org/install) para aprender como instalarla.*

## Descripción general

Facette is a web application to display time series data from various sources — such as collectd, Graphite, InfluxDB or KairosDB — on graphs, designed to be easy to setup and to use.

**Versión actual:** 0.5.1~ynh4

**Demo:** <https://play.facette.io/browse/>

## Capturas

![Captura de Facette](./doc/screenshots/screenshot.png)

## :red_circle: Características no deseables

- **Upstream not maintained**: This software is not maintained anymore. Expect it to break down over time, be exposed to unfixed security breaches, etc.

## Documentaciones y recursos

- Sitio web oficial: <https://facette.io/>
- Documentación administrador oficial: <https://docs.facette.io/>
- Repositorio del código fuente oficial de la aplicación : <https://github.com/facette/facette>
- Catálogo YunoHost: <https://apps.yunohost.org/app/facette>
- Reportar un error: <https://github.com/YunoHost-Apps/facette_ynh/issues>

## Información para desarrolladores

Por favor enviar sus correcciones a la [`branch testing`](https://github.com/YunoHost-Apps/facette_ynh/tree/testing

Para probar la rama `testing`, sigue asÍ:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/facette_ynh/tree/testing --debug
o
sudo yunohost app upgrade facette -u https://github.com/YunoHost-Apps/facette_ynh/tree/testing --debug
```

**Mas informaciones sobre el empaquetado de aplicaciones:** <https://yunohost.org/packaging_apps>
