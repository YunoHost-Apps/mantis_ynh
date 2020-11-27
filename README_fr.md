# Mantis pour YunoHost

[![Integration level](https://dash.yunohost.org/integration/mantis.svg)](https://dash.yunohost.org/appci/app/mantis) ![](https://ci-apps.yunohost.org/ci/badges/mantis.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/mantis.maintain.svg)  
[![Installer Mantis pour YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=mantis)

*[Read this readme in english.](./README.md)* 

> *Ce package vous permet d'installer Mantis rapidement et simplement sur un serveur YunoHost.  
Si vous n'avez pas YunoHost, consultez [le guide](https://yunohost.org/#/install) pour apprendre comment l'installer.*

## Vue d'ensemble

Mantis Bug Tracker est un système de suivi des bogues gratuit et open source. L'utilisation la plus courante de MantisBT est de suivre les bogues logiciels. Cependant, MantisBT est souvent configuré par les utilisateurs pour servir de système de suivi des problèmes plus générique et d'outil de gestion de projet.

**Version incluse :** 2.24.3

## Captures d'écran

![](https://github.com/mantisbt/mantisbt/blob/master/doc/modern_my_view.png)

## Démo

* [Démo officielle](https://mantisbt.org/bugs/my_view_page.php)

#### Où trouver l'utilisateur SQL et le mot de passe de la base.

- **Utilisateur de la base de données :** mantis
- **Nom de la base de données :** mantis
- **Mot de passe :** voir le fichier de configuration `/var/www/mantis/config/config_inc.php`

## Documentation

 * Documentation officielle : https://mantisbt.org/documentation.php
 * Documentation YunoHost :  https://yunohost.org/#/app_mantis_fr

## Caractéristiques spécifiques YunoHost

#### Support multi-utilisateur

* L'authentification LDAP et HTTP est-elle prise en charge ? **Oui**
* L'application peut-elle être utilisée par plusieurs utilisateurs ? **Oui**

#### Architectures supportées

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/mantis%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/mantis/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/mantis%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/mantis/)

## Limitations

* Limitations connues.

## Informations additionnelles

* Autres informations que vous souhaitez ajouter sur cette application.

## Liens

 * Signaler un bug : https://github.com/YunoHost-Apps/mantis_ynh/issues
 * Site de l'application : https://mantisbt.org/
 * Dépôt de l'application principale : https://github.com/mantisbt/mantisbt/
 * Site web YunoHost : https://yunohost.org/

---

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/mantis_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/mantis_ynh/tree/testing --debug
or
sudo yunohost app upgrade mantis -u https://github.com/YunoHost-Apps/mantis_ynh/tree/testing --debug
```
