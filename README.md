# Mantis for YunoHost

[![Integration level](https://dash.yunohost.org/integration/mantis.svg)](https://dash.yunohost.org/appci/app/mantis) ![](https://ci-apps.yunohost.org/ci/badges/mantis.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/mantis.maintain.svg)  
[![Install Mantis with YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=mantis)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Mantis quickly and simply on a YunoHost server.  
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

Mantis Bug Tracker is a free and open source, web-based bug tracking system. The most common use of MantisBT is to track software defects. However, MantisBT is often configured by users to serve as a more generic issue tracking system and project management tool.

**Shipped version:** 2.24.3

## Screenshots

![](https://github.com/mantisbt/mantisbt/blob/master/doc/modern_my_view.png)

## Demo

* [Official demo](https://mantisbt.org/bugs/my_view_page.php)

#### Where to find SQL user and password

- **DB user:** mantis
- **DB name:** mantis
- **Password:** to be found in the config file `/var/www/mantis/config/config_inc.php`

## Documentation

 * Official documentation: https://mantisbt.org/documentation.php
 * YunoHost documentation: https://yunohost.org/#/app_mantis

## YunoHost specific features

#### Multi-user support

* Are LDAP and HTTP auth supported ? **Yes**
* Can the app be used by multiple users? **Yes**

#### Supported architectures

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/mantis%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/mantis/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/mantis%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/mantis/)

## Limitations

* Any known limitations.

## Additional information

* Other info you would like to add about this app.

## Links

 * Report a bug: https://github.com/YunoHost-Apps/mantis_ynh/issues
 * App website: https://mantisbt.org/
 * Upstream app repository: https://github.com/mantisbt/mantisbt/
 * YunoHost website: https://yunohost.org/

---

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/mantis_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/mantis_ynh/tree/testing --debug
or
sudo yunohost app upgrade mantis -u https://github.com/YunoHost-Apps/mantis_ynh/tree/testing --debug
```
