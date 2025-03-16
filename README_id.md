<!--
N.B.: README ini dibuat secara otomatis oleh <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Ini TIDAK boleh diedit dengan tangan.
-->

# Backrest untuk YunoHost

[![Tingkat integrasi](https://apps.yunohost.org/badge/integration/backrest)](https://ci-apps.yunohost.org/ci/apps/backrest/)
![Status kerja](https://apps.yunohost.org/badge/state/backrest)
![Status pemeliharaan](https://apps.yunohost.org/badge/maintained/backrest)

[![Pasang Backrest dengan YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=backrest)

*[Baca README ini dengan bahasa yang lain.](./ALL_README.md)*

> *Paket ini memperbolehkan Anda untuk memasang Backrest secara cepat dan mudah pada server YunoHost.*  
> *Bila Anda tidak mempunyai YunoHost, silakan berkonsultasi dengan [panduan](https://yunohost.org/install) untuk mempelajari bagaimana untuk memasangnya.*

## Ringkasan

Backrest is a web-accessible backup solution built on top of restic. Backrest provides a WebUI which wraps the restic CLI and makes it easy to create repos, browse snapshots, and restore files. Additionally, Backrest can run in the background and take an opinionated approach to scheduling snapshots and orchestrating repo health operations.


**Versi terkirim:** 1.7.3~ynh1

## Tangkapan Layar

![Tangkapan Layar pada Backrest](./doc/screenshots/68747470733a2f2f663030302e6261636b626c617a6562322e636f6d2f66696c652f6773686172652f73637265656e73686f74732f323032342f53637265656e73686f742b66726f6d2b323032342d30312d30342b31382d31392d35302e706e67.png)
![Tangkapan Layar pada Backrest](./doc/screenshots/68747470733a2f2f663030302e6261636b626c617a6562322e636f6d2f66696c652f6773686172652f73637265656e73686f74732f323032342f53637265656e73686f742b66726f6d2b323032342d30312d30342b31382d33302d31342e706e67.png)

## Dokumentasi dan sumber daya

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
