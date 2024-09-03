<!--
N.B.: README ini dibuat secara otomatis oleh <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Ini TIDAK boleh diedit dengan tangan.
-->

# Mantis untuk YunoHost

[![Tingkat integrasi](https://dash.yunohost.org/integration/mantis.svg)](https://ci-apps.yunohost.org/ci/apps/mantis/) ![Status kerja](https://ci-apps.yunohost.org/ci/badges/mantis.status.svg) ![Status pemeliharaan](https://ci-apps.yunohost.org/ci/badges/mantis.maintain.svg)

[![Pasang Mantis dengan YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=mantis)

*[Baca README ini dengan bahasa yang lain.](./ALL_README.md)*

> *Paket ini memperbolehkan Anda untuk memasang Mantis secara cepat dan mudah pada server YunoHost.*  
> *Bila Anda tidak mempunyai YunoHost, silakan berkonsultasi dengan [panduan](https://yunohost.org/install) untuk mempelajari bagaimana untuk memasangnya.*

## Ringkasan

MantisBT is an open source issue tracker that provides a delicate balance between simplicity and power. Users are able to get started in minutes and start managing their projects while collaborating with their teammates and clients effectively. 

**Versi terkirim:** 2.26.0~ynh1

**Demo:** <https://mantisbt.org/bugs/my_view_page.php>

## Tangkapan Layar

![Tangkapan Layar pada Mantis](./doc/screenshots/modern_my_view.png)

## Dokumentasi dan sumber daya

- Website aplikasi resmi: <https://mantisbt.org/>
- Dokumentasi admin resmi: <https://mantisbt.org/documentation.php>
- Depot kode aplikasi hulu: <https://github.com/mantisbt/mantisbt/>
- Gudang YunoHost: <https://apps.yunohost.org/app/mantis>
- Laporkan bug: <https://github.com/YunoHost-Apps/mantis_ynh/issues>

## Info developer

Silakan kirim pull request ke [`testing` branch](https://github.com/YunoHost-Apps/mantis_ynh/tree/testing).

Untuk mencoba branch `testing`, silakan dilanjutkan seperti:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/mantis_ynh/tree/testing --debug
atau
sudo yunohost app upgrade mantis -u https://github.com/YunoHost-Apps/mantis_ynh/tree/testing --debug
```

**Info lebih lanjut mengenai pemaketan aplikasi:** <https://yunohost.org/packaging_apps>
