<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# Mantis YunoHost-erako

[![Integrazio maila](https://dash.yunohost.org/integration/mantis.svg)](https://ci-apps.yunohost.org/ci/apps/mantis/) ![Funtzionamendu egoera](https://ci-apps.yunohost.org/ci/badges/mantis.status.svg) ![Mantentze egoera](https://ci-apps.yunohost.org/ci/badges/mantis.maintain.svg)

[![Instalatu Mantis YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=mantis)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek Mantis YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

MantisBT is an open source issue tracker that provides a delicate balance between simplicity and power. Users are able to get started in minutes and start managing their projects while collaborating with their teammates and clients effectively. 

**Paketatutako bertsioa:** 2.26.0~ynh1

**Demoa:** <https://mantisbt.org/bugs/my_view_page.php>

## Pantaila-argazkiak

![Mantis(r)en pantaila-argazkia](./doc/screenshots/modern_my_view.png)

## Dokumentazioa eta baliabideak

- Aplikazioaren webgune ofiziala: <https://mantisbt.org/>
- Administratzaileen dokumentazio ofiziala: <https://mantisbt.org/documentation.php>
- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/mantisbt/mantisbt/>
- YunoHost Denda: <https://apps.yunohost.org/app/mantis>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/mantis_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/mantis_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/mantis_ynh/tree/testing --debug
edo
sudo yunohost app upgrade mantis -u https://github.com/YunoHost-Apps/mantis_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
