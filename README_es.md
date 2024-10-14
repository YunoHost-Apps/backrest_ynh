<!--
Este archivo README esta generado automaticamente<https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
No se debe editar a mano.
-->

# Backrest para Yunohost

[![Nivel de integración](https://dash.yunohost.org/integration/backrest.svg)](https://ci-apps.yunohost.org/ci/apps/backrest/) ![Estado funcional](https://ci-apps.yunohost.org/ci/badges/backrest.status.svg) ![Estado En Mantención](https://ci-apps.yunohost.org/ci/badges/backrest.maintain.svg)

[![Instalar Backrest con Yunhost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=backrest)

*[Leer este README en otros idiomas.](./ALL_README.md)*

> *Este paquete le permite instalarBackrest rapidamente y simplement en un servidor YunoHost.*  
> *Si no tiene YunoHost, visita [the guide](https://yunohost.org/install) para aprender como instalarla.*

## Descripción general

Backrest is a web-accessible backup solution built on top of restic. Backrest provides a WebUI which wraps the restic CLI and makes it easy to create repos, browse snapshots, and restore files. Additionally, Backrest can run in the background and take an opinionated approach to scheduling snapshots and orchestrating repo health operations.


**Versión actual:** 1.5.1~ynh1

## Capturas

![Captura de Backrest](./doc/screenshots/68747470733a2f2f663030302e6261636b626c617a6562322e636f6d2f66696c652f6773686172652f73637265656e73686f74732f323032342f53637265656e73686f742b66726f6d2b323032342d30312d30342b31382d31392d35302e706e67.png)
![Captura de Backrest](./doc/screenshots/68747470733a2f2f663030302e6261636b626c617a6562322e636f6d2f66696c652f6773686172652f73637265656e73686f74732f323032342f53637265656e73686f742b66726f6d2b323032342d30312d30342b31382d33302d31342e706e67.png)

## Documentaciones y recursos

- Documentación usuario oficial: <https://garethgeorge.github.io/backrest/introduction/getting-started>
- Documentación administrador oficial: <https://github.com/garethgeorge/backrest#installation>
- Repositorio del código fuente oficial de la aplicación : <https://github.com/garethgeorge/backrest>
- Catálogo YunoHost: <https://apps.yunohost.org/app/backrest>
- Reportar un error: <https://github.com/YunoHost-Apps/backrest_ynh/issues>

## Información para desarrolladores

Por favor enviar sus correcciones a la [rama `testing`](https://github.com/YunoHost-Apps/backrest_ynh/tree/testing).

Para probar la rama `testing`, sigue asÍ:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/backrest_ynh/tree/testing --debug
o
sudo yunohost app upgrade backrest -u https://github.com/YunoHost-Apps/backrest_ynh/tree/testing --debug
```

**Mas informaciones sobre el empaquetado de aplicaciones:** <https://yunohost.org/packaging_apps>
