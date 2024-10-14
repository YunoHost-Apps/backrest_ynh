<!--
N.B.: README ini dibuat secara otomatis oleh <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Ini TIDAK boleh diedit dengan tangan.
-->

# Backrest untuk YunoHost

[![Tingkat integrasi](https://dash.yunohost.org/integration/backrest.svg)](https://ci-apps.yunohost.org/ci/apps/backrest/) ![Status kerja](https://ci-apps.yunohost.org/ci/badges/backrest.status.svg) ![Status pemeliharaan](https://ci-apps.yunohost.org/ci/badges/backrest.maintain.svg)

[![Pasang Backrest dengan YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=backrest)

*[Baca README ini dengan bahasa yang lain.](./ALL_README.md)*

> *Paket ini memperbolehkan Anda untuk memasang Backrest secara cepat dan mudah pada server YunoHost.*  
> *Bila Anda tidak mempunyai YunoHost, silakan berkonsultasi dengan [panduan](https://yunohost.org/install) untuk mempelajari bagaimana untuk memasangnya.*

## Ringkasan

Backrest is a web-accessible backup solution built on top of restic. Backrest provides a WebUI which wraps the restic CLI and makes it easy to create repos, browse snapshots, and restore files. Additionally, Backrest can run in the background and take an opinionated approach to scheduling snapshots and orchestrating repo health operations.


**Versi terkirim:** 1.5.1~ynh1
## Dokumentasi dan sumber daya

- Website aplikasi resmi: <https://github.com/garethgeorge/backrest>
- Dokumentasi pengguna resmi: <https://garethgeorge.github.io/backrest/introduction/getting-started>
- Dokumentasi admin resmi: <https://github.com/garethgeorge/backrest#installation>
- Depot kode aplikasi hulu: <https://github.com/garethgeorge/backrest>
- Gudang YunoHost: <https://apps.yunohost.org/app/backrest>
- Laporkan bug: <https://github.com/YunoHost-Apps/backrest_ynh/issues>

## Info developer

Silakan kirim pull request ke [`testing` branch](https://github.com/YunoHost-Apps/backrest_ynh/tree/testing).

Untuk mencoba branch `testing`, silakan dilanjutkan seperti:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/backrest_ynh/tree/testing --debug
atau
sudo yunohost app upgrade backrest -u https://github.com/YunoHost-Apps/backrest_ynh/tree/testing --debug
```

**Info lebih lanjut mengenai pemaketan aplikasi:** <https://yunohost.org/packaging_apps>
