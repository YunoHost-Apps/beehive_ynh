<!--
NOTA: Este README foi creado automáticamente por <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
NON debe editarse manualmente.
-->

# Beehive para YunoHost

[![Nivel de integración](https://dash.yunohost.org/integration/beehive.svg)](https://ci-apps.yunohost.org/ci/apps/beehive/) ![Estado de funcionamento](https://ci-apps.yunohost.org/ci/badges/beehive.status.svg) ![Estado de mantemento](https://ci-apps.yunohost.org/ci/badges/beehive.maintain.svg)

[![Instalar Beehive con YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=beehive)

*[Le este README en outros idiomas.](./ALL_README.md)*

> *Este paquete permíteche instalar Beehive de xeito rápido e doado nun servidor YunoHost.*  
> *Se non usas YunoHost, le a [documentación](https://yunohost.org/install) para saber como instalalo.*

## Vista xeral

Beehive is an event and agent system, which allows you to create your own agents that perform automated tasks triggered by events and filters. It is modular, flexible and really easy to extend for anyone. It has modules (we call them Hives), so it can interface with, talk to, or retrieve information from Twitter, Tumblr, Email, IRC, Jabber, RSS, Jenkins, Hue - to name just a few. 

### Features:

- Re-post tweets on your Tumblr blog
- Forward incoming chat messages to your email account
- Turn on the heating system if the temperature drops below a certain value
- Run your own IRC bot that lets you trigger builds on a Jenkins CI
- Control your Hue lighting system
- Notify you when a stock's price drops below a certain value


**Versión proporcionada:** 0.4.0~ynh4

**Demo:** <https://github.com/muesli/beehive/wiki/Available-Hives>

## Capturas de pantalla

![Captura de pantalla de Beehive](./doc/screenshots/screenshot1.jpg)

## :red_circle: Debes considerar

- **Upstream not maintained**: This software is not maintained anymore. Expect it to break down over time, be exposed to unfixed security breaches, etc.

## Documentación e recursos

- Repositorio de orixe do código: <https://github.com/muesli/beehive>
- Tenda YunoHost: <https://apps.yunohost.org/app/beehive>
- Informar dun problema: <https://github.com/YunoHost-Apps/beehive_ynh/issues>

## Info de desenvolvemento

Envía a túa colaboración á [rama `testing`](https://github.com/YunoHost-Apps/beehive_ynh/tree/testing).

Para probar a rama `testing`, procede deste xeito:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/beehive_ynh/tree/testing --debug
ou
sudo yunohost app upgrade beehive -u https://github.com/YunoHost-Apps/beehive_ynh/tree/testing --debug
```

**Máis info sobre o empaquetado da app:** <https://yunohost.org/packaging_apps>
