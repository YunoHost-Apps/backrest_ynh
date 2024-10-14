<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# Backrest YunoHost-erako

[![Integrazio maila](https://dash.yunohost.org/integration/backrest.svg)](https://ci-apps.yunohost.org/ci/apps/backrest/) ![Funtzionamendu egoera](https://ci-apps.yunohost.org/ci/badges/backrest.status.svg) ![Mantentze egoera](https://ci-apps.yunohost.org/ci/badges/backrest.maintain.svg)

[![Instalatu Backrest YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=backrest)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek Backrest YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

Backrest is a web-accessible backup solution built on top of restic. Backrest provides a WebUI which wraps the restic CLI and makes it easy to create repos, browse snapshots, and restore files. Additionally, Backrest can run in the background and take an opinionated approach to scheduling snapshots and orchestrating repo health operations.


**Paketatutako bertsioa:** 1.5.1~ynh1

## Pantaila-argazkiak

![Backrest(r)en pantaila-argazkia](./doc/screenshots/example.jpg)

## Dokumentazioa eta baliabideak

- Aplikazioaren webgune ofiziala: <https://github.com/garethgeorge/backrest>
- Erabiltzaileen dokumentazio ofiziala: <https://garethgeorge.github.io/backrest/introduction/getting-started>
- Administratzaileen dokumentazio ofiziala: <https://github.com/garethgeorge/backrest#installation>
- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/garethgeorge/backrest>
- YunoHost Denda: <https://apps.yunohost.org/app/backrest>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/backrest_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/backrest_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/backrest_ynh/tree/testing --debug
edo
sudo yunohost app upgrade backrest -u https://github.com/YunoHost-Apps/backrest_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
