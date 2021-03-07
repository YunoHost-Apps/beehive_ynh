# Beehive for YunoHost
![](https://raw.githubusercontent.com/muesli/beehive/master/assets/logo_256.png)

[![Integration level](https://dash.yunohost.org/integration/beehive.svg)](https://dash.yunohost.org/appci/app/beehive) ![](https://ci-apps.yunohost.org/ci/badges/beehive.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/beehive.maintain.svg)

[![Install Beehive with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=beehive)


> *This package allows you to install Beehive quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview
Beehive is an event and agent system, which allows you to create your own agents that perform automated tasks triggered by events and filters. It is modular, flexible and really easy to extend for anyone. It has modules (we call them Hives), so it can interface with, talk to, or retrieve information from Twitter, Tumblr, Email, IRC, Jabber, RSS, Jenkins, Hue - to name just a few.

Available hives: [Click here](https://github.com/muesli/beehive/wiki/Available-Hives)

**Shipped version:** 28.01.2021

## Screenshots

![](https://raw.githubusercontent.com/muesli/beehive-docs/master/screencaps/new_bees.gif)

## YunoHost specific features

#### Multi-user support

Are LDAP and HTTP auth supported? No
Can the app be used by multiple users? Yes

#### Supported architectures

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/beehive%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/beehive/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/beehive%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/beehive/)

## Links

 * Report a bug: https://github.com/YunoHost-Apps/beehive_ynh/issues
 * Upstream app repository: https://github.com/muesli/beehive
 * YunoHost website: https://yunohost.org/

---

## Developer info

**Only if you want to use a testing branch for coding, instead of merging directly into master.**
Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/beehive_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/beehive_ynh/tree/testing --debug
or
sudo yunohost app upgrade beehive -u https://github.com/YunoHost-Apps/beehive_ynh/tree/testing --debug
```
