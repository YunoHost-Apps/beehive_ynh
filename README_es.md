<!--
Este archivo README esta generado automaticamente<https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
No se debe editar a mano.
-->

# Beehive para Yunohost

[![Nivel de integración](https://dash.yunohost.org/integration/beehive.svg)](https://dash.yunohost.org/appci/app/beehive) ![Estado funcional](https://ci-apps.yunohost.org/ci/badges/beehive.status.svg) ![Estado En Mantención](https://ci-apps.yunohost.org/ci/badges/beehive.maintain.svg)

[![Instalar Beehive con Yunhost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=beehive)

*[Leer este README en otros idiomas.](./ALL_README.md)*

> *Este paquete le permite instalarBeehive rapidamente y simplement en un servidor YunoHost.*  
> *Si no tiene YunoHost, visita [the guide](https://yunohost.org/install) para aprender como instalarla.*

## Descripción general

Beehive is an event and agent system, which allows you to create your own agents that perform automated tasks triggered by events and filters. It is modular, flexible and really easy to extend for anyone. It has modules (we call them Hives), so it can interface with, talk to, or retrieve information from Twitter, Tumblr, Email, IRC, Jabber, RSS, Jenkins, Hue - to name just a few. 

### Features:

- Re-post tweets on your Tumblr blog
- Forward incoming chat messages to your email account
- Turn on the heating system if the temperature drops below a certain value
- Run your own IRC bot that lets you trigger builds on a Jenkins CI
- Control your Hue lighting system
- Notify you when a stock's price drops below a certain value


**Versión actual:** 0.4.0~ynh3

**Demo:** <https://github.com/muesli/beehive/wiki/Available-Hives>

## Capturas

![Captura de Beehive](./doc/screenshots/screenshot1.gif)

## :red_circle: Características no deseables

- **Upstream not maintained**: This software is not maintained anymore. Expect it to break down over time, be exposed to unfixed security breaches, etc.

## Documentaciones y recursos

- Repositorio del código fuente oficial de la aplicación : <https://github.com/muesli/beehive>
- Catálogo YunoHost: <https://apps.yunohost.org/app/beehive>
- Reportar un error: <https://github.com/YunoHost-Apps/beehive_ynh/issues>

## Información para desarrolladores

Por favor enviar sus correcciones a la [`branch testing`](https://github.com/YunoHost-Apps/beehive_ynh/tree/testing

Para probar la rama `testing`, sigue asÍ:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/beehive_ynh/tree/testing --debug
o
sudo yunohost app upgrade beehive -u https://github.com/YunoHost-Apps/beehive_ynh/tree/testing --debug
```

**Mas informaciones sobre el empaquetado de aplicaciones:** <https://yunohost.org/packaging_apps>
