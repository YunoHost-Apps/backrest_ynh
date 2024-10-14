<!--
NOTA: Este README foi creado automáticamente por <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
NON debe editarse manualmente.
-->

# Backrest para YunoHost

[![Nivel de integración](https://dash.yunohost.org/integration/backrest.svg)](https://ci-apps.yunohost.org/ci/apps/backrest/) ![Estado de funcionamento](https://ci-apps.yunohost.org/ci/badges/backrest.status.svg) ![Estado de mantemento](https://ci-apps.yunohost.org/ci/badges/backrest.maintain.svg)

[![Instalar Backrest con YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=backrest)

*[Le este README en outros idiomas.](./ALL_README.md)*

> *Este paquete permíteche instalar Backrest de xeito rápido e doado nun servidor YunoHost.*  
> *Se non usas YunoHost, le a [documentación](https://yunohost.org/install) para saber como instalalo.*

## Vista xeral

Backrest is a web-accessible backup solution built on top of restic. Backrest provides a WebUI which wraps the restic CLI and makes it easy to create repos, browse snapshots, and restore files. Additionally, Backrest can run in the background and take an opinionated approach to scheduling snapshots and orchestrating repo health operations.


**Versión proporcionada:** 1.5.1~ynh1

## Capturas de pantalla

![Captura de pantalla de Backrest](./doc/screenshots/68747470733a2f2f663030302e6261636b626c617a6562322e636f6d2f66696c652f6773686172652f73637265656e73686f74732f323032342f53637265656e73686f742b66726f6d2b323032342d30312d30342b31382d31392d35302e706e67.png)
![Captura de pantalla de Backrest](./doc/screenshots/68747470733a2f2f663030302e6261636b626c617a6562322e636f6d2f66696c652f6773686172652f73637265656e73686f74732f323032342f53637265656e73686f742b66726f6d2b323032342d30312d30342b31382d33302d31342e706e67.png)

## Documentación e recursos

- Web oficial da app: <https://github.com/garethgeorge/backrest>
- Documentación oficial para usuarias: <https://garethgeorge.github.io/backrest/introduction/getting-started>
- Documentación oficial para admin: <https://github.com/garethgeorge/backrest#installation>
- Repositorio de orixe do código: <https://github.com/garethgeorge/backrest>
- Tenda YunoHost: <https://apps.yunohost.org/app/backrest>
- Informar dun problema: <https://github.com/YunoHost-Apps/backrest_ynh/issues>

## Info de desenvolvemento

Envía a túa colaboración á [rama `testing`](https://github.com/YunoHost-Apps/backrest_ynh/tree/testing).

Para probar a rama `testing`, procede deste xeito:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/backrest_ynh/tree/testing --debug
ou
sudo yunohost app upgrade backrest -u https://github.com/YunoHost-Apps/backrest_ynh/tree/testing --debug
```

**Máis info sobre o empaquetado da app:** <https://yunohost.org/packaging_apps>
