# Mantis for YunoHost

[![Integration level](https://dash.yunohost.org/integration/mantis.svg)](https://dash.yunohost.org/appci/app/mantis) ![](https://ci-apps.yunohost.org/ci/badges/mantis.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/mantis.maintain.svg)  
[![Install Mantis with YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=mantis)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Mantis quickly and simply on a YunoHost server.  
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview
Mantis Server

**Shipped version:** 2.24.3

## Screenshots

![](https://github.com/mantisbt/mantisbt/blob/master/doc/modern_my_view.png)

## Demo

* [Official demo](https://mantisbt.org/bugs/my_view_page.php)

## After installing guide
 
        1. Login to Mantis
        2. put your SQL user and password 
        (you can find them via `nano /var/www/mantis/config/config_inc.php.sample` in CLI mode)
        3. Admin user for db is same user for SQL same for password
        4. First login is
        	- user: administrator
        	- password: root
        5. `sudo rm -r /var/www/mantis/admin`

## Documentation

 * Official documentation: https://mantisbt.org/documentation.php
 * YunoHost documentation: If specific documentation is needed, feel free to contribute.

## YunoHost specific features

#### Multi-user support

* Are LDAP and HTTP auth supported?
* Can the app be used by multiple users?

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
