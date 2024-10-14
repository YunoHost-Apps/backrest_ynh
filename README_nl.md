<!--
NB: Deze README is automatisch gegenereerd door <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Hij mag NIET handmatig aangepast worden.
-->

# Backrest voor Yunohost

[![Integratieniveau](https://dash.yunohost.org/integration/backrest.svg)](https://ci-apps.yunohost.org/ci/apps/backrest/) ![Mate van functioneren](https://ci-apps.yunohost.org/ci/badges/backrest.status.svg) ![Onderhoudsstatus](https://ci-apps.yunohost.org/ci/badges/backrest.maintain.svg)

[![Backrest met Yunohost installeren](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=backrest)

*[Deze README in een andere taal lezen.](./ALL_README.md)*

> *Met dit pakket kun je Backrest snel en eenvoudig op een YunoHost-server installeren.*  
> *Als je nog geen YunoHost hebt, lees dan [de installatiehandleiding](https://yunohost.org/install), om te zien hoe je 'm installeert.*

## Overzicht

Backrest is a web-accessible backup solution built on top of restic. Backrest provides a WebUI which wraps the restic CLI and makes it easy to create repos, browse snapshots, and restore files. Additionally, Backrest can run in the background and take an opinionated approach to scheduling snapshots and orchestrating repo health operations.


**Geleverde versie:** 1.5.1~ynh1
## Documentatie en bronnen

- Officiele website van de app: <https://github.com/garethgeorge/backrest>
- Officiele gebruikersdocumentatie: <https://garethgeorge.github.io/backrest/introduction/getting-started>
- Officiele beheerdersdocumentatie: <https://github.com/garethgeorge/backrest#installation>
- Upstream app codedepot: <https://github.com/garethgeorge/backrest>
- YunoHost-store: <https://apps.yunohost.org/app/backrest>
- Meld een bug: <https://github.com/YunoHost-Apps/backrest_ynh/issues>

## Ontwikkelaarsinformatie

Stuur je pull request alsjeblieft naar de [`testing`-branch](https://github.com/YunoHost-Apps/backrest_ynh/tree/testing).

Om de `testing`-branch uit te proberen, ga als volgt te werk:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/backrest_ynh/tree/testing --debug
of
sudo yunohost app upgrade backrest -u https://github.com/YunoHost-Apps/backrest_ynh/tree/testing --debug
```

**Verdere informatie over app-packaging:** <https://yunohost.org/packaging_apps>
