<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# Airsonic for YunoHost

[![Integration level](https://dash.yunohost.org/integration/airsonic.svg)](https://dash.yunohost.org/appci/app/airsonic) ![Working status](https://ci-apps.yunohost.org/ci/badges/airsonic.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/airsonic.maintain.svg)  
[![Install Airsonic with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=airsonic)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Airsonic quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

Stream and manage your music collection

**Shipped version:** 10.6.2~ynh3

**Demo:** https://airsonic.github.io/demo/

## Screenshots

![Screenshot of Airsonic](./doc/screenshots/screenshot_01.png)

## Disclaimers / important information

## YunoHost specific features

* YunoHost LDAP accounts supported: **Yes**
* [Multimedia](https://github.com/YunoHost-Apps/yunohost.multimedia) handled
* Memory RAM limit set to 256 MB because Airsonic was often killed by lack of RAM (hello OOM killer)
* See https://www.reddit.com/r/airsonic/comments/doscco/jvm_memory_issues/

## Documentation and resources

* Official app website: <https://airsonic.github.io/>
* Official admin documentation: <https://airsonic.github.io/docs/>
* Upstream app code repository: <https://github.com/airsonic/airsonic>
* YunoHost documentation for this app: <https://yunohost.org/app_airsonic>
* Report a bug: <https://github.com/YunoHost-Apps/airsonic_ynh/issues>

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/airsonic_ynh/tree/testing).

To try the testing branch, please proceed like that.

``` bash
sudo yunohost app install https://github.com/YunoHost-Apps/airsonic_ynh/tree/testing --debug
or
sudo yunohost app upgrade airsonic -u https://github.com/YunoHost-Apps/airsonic_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
