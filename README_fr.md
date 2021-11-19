# Mantis pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/mantis.svg)](https://dash.yunohost.org/appci/app/mantis) ![](https://ci-apps.yunohost.org/ci/badges/mantis.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/mantis.maintain.svg)  
[![Installer Mantis avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=mantis)

*[Read this readme in english.](./README.md)*
*[Lire ce readme en français.](./README_fr.md)*

> *Ce package vous permet d'installer Mantis rapidement et simplement sur un serveur YunoHost.
Si vous n'avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l'installer et en profiter.*

## Vue d'ensemble

MantisBT is an open source issue tracker that provides a delicate balance between simplicity and power. Users are able to get started in minutes and start managing their projects while collaborating with their teammates and clients effectively. 

**Version incluse :** 2.25.2~ynh2

**Démo :** https://mantisbt.org/bugs/my_view_page.php

## Captures d'écran

![](./doc/screenshots/modern_my_view.png)

## Documentations et ressources

* Site officiel de l'app : https://mantisbt.org/
* Documentation officielle de l'admin : https://mantisbt.org/documentation.php
* Dépôt de code officiel de l'app : https://github.com/mantisbt/mantisbt/
* Documentation YunoHost pour cette app : https://yunohost.org/app_mantis
* Signaler un bug : https://github.com/YunoHost-Apps/mantis_ynh/issues

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/mantis_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/mantis_ynh/tree/testing --debug
ou
sudo yunohost app upgrade mantis -u https://github.com/YunoHost-Apps/mantis_ynh/tree/testing --debug
```

**Plus d'infos sur le packaging d'applications :** https://yunohost.org/packaging_apps