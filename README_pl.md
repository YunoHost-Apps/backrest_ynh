<!--
To README zostało automatycznie wygenerowane przez <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Nie powinno być ono edytowane ręcznie.
-->

# Backrest dla YunoHost

[![Poziom integracji](https://apps.yunohost.org/badge/integration/backrest)](https://ci-apps.yunohost.org/ci/apps/backrest/)
![Status działania](https://apps.yunohost.org/badge/state/backrest)
![Status utrzymania](https://apps.yunohost.org/badge/maintained/backrest)

[![Zainstaluj Backrest z YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=backrest)

*[Przeczytaj plik README w innym języku.](./ALL_README.md)*

> *Ta aplikacja pozwala na szybką i prostą instalację Backrest na serwerze YunoHost.*  
> *Jeżeli nie masz YunoHost zapoznaj się z [poradnikiem](https://yunohost.org/install) instalacji.*

## Przegląd

Backrest is a web-accessible backup solution built on top of restic. Backrest provides a WebUI which wraps the restic CLI and makes it easy to create repos, browse snapshots, and restore files. Additionally, Backrest can run in the background and take an opinionated approach to scheduling snapshots and orchestrating repo health operations.


**Dostarczona wersja:** 1.5.1~ynh4

## Zrzuty ekranu

![Zrzut ekranu z Backrest](./doc/screenshots/68747470733a2f2f663030302e6261636b626c617a6562322e636f6d2f66696c652f6773686172652f73637265656e73686f74732f323032342f53637265656e73686f742b66726f6d2b323032342d30312d30342b31382d31392d35302e706e67.png)
![Zrzut ekranu z Backrest](./doc/screenshots/68747470733a2f2f663030302e6261636b626c617a6562322e636f6d2f66696c652f6773686172652f73637265656e73686f74732f323032342f53637265656e73686f742b66726f6d2b323032342d30312d30342b31382d33302d31342e706e67.png)

## Dokumentacja i zasoby

- Oficjalna dokumentacja: <https://garethgeorge.github.io/backrest/introduction/getting-started>
- Oficjalna dokumentacja dla administratora: <https://github.com/garethgeorge/backrest#installation>
- Repozytorium z kodem źródłowym: <https://github.com/garethgeorge/backrest>
- Sklep YunoHost: <https://apps.yunohost.org/app/backrest>
- Zgłaszanie błędów: <https://github.com/YunoHost-Apps/backrest_ynh/issues>

## Informacje od twórców

Wyślij swój pull request do [gałęzi `testing`](https://github.com/YunoHost-Apps/backrest_ynh/tree/testing).

Aby wypróbować gałąź `testing` postępuj zgodnie z instrukcjami:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/backrest_ynh/tree/testing --debug
lub
sudo yunohost app upgrade backrest -u https://github.com/YunoHost-Apps/backrest_ynh/tree/testing --debug
```

**Więcej informacji o tworzeniu paczek aplikacji:** <https://yunohost.org/packaging_apps>
