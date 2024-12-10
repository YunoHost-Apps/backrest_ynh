<!--
Важно: этот README был автоматически сгенерирован <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Он НЕ ДОЛЖЕН редактироваться вручную.
-->

# Backrest для YunoHost

[![Уровень интеграции](https://apps.yunohost.org/badge/integration/backrest)](https://ci-apps.yunohost.org/ci/apps/backrest/)
![Состояние работы](https://apps.yunohost.org/badge/state/backrest)
![Состояние сопровождения](https://apps.yunohost.org/badge/maintained/backrest)

[![Установите Backrest с YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=backrest)

*[Прочтите этот README на других языках.](./ALL_README.md)*

> *Этот пакет позволяет Вам установить Backrest быстро и просто на YunoHost-сервер.*  
> *Если у Вас нет YunoHost, пожалуйста, посмотрите [инструкцию](https://yunohost.org/install), чтобы узнать, как установить его.*

## Обзор

Backrest is a web-accessible backup solution built on top of restic. Backrest provides a WebUI which wraps the restic CLI and makes it easy to create repos, browse snapshots, and restore files. Additionally, Backrest can run in the background and take an opinionated approach to scheduling snapshots and orchestrating repo health operations.


**Поставляемая версия:** 1.6.2~ynh1

## Снимки экрана

![Снимок экрана Backrest](./doc/screenshots/68747470733a2f2f663030302e6261636b626c617a6562322e636f6d2f66696c652f6773686172652f73637265656e73686f74732f323032342f53637265656e73686f742b66726f6d2b323032342d30312d30342b31382d31392d35302e706e67.png)
![Снимок экрана Backrest](./doc/screenshots/68747470733a2f2f663030302e6261636b626c617a6562322e636f6d2f66696c652f6773686172652f73637265656e73686f74732f323032342f53637265656e73686f742b66726f6d2b323032342d30312d30342b31382d33302d31342e706e67.png)

## Документация и ресурсы

- Официальная документация пользователя: <https://garethgeorge.github.io/backrest/introduction/getting-started>
- Официальная документация администратора: <https://github.com/garethgeorge/backrest#installation>
- Репозиторий кода главной ветки приложения: <https://github.com/garethgeorge/backrest>
- Магазин YunoHost: <https://apps.yunohost.org/app/backrest>
- Сообщите об ошибке: <https://github.com/YunoHost-Apps/backrest_ynh/issues>

## Информация для разработчиков

Пришлите Ваш запрос на слияние в [ветку `testing`](https://github.com/YunoHost-Apps/backrest_ynh/tree/testing).

Чтобы попробовать ветку `testing`, пожалуйста, сделайте что-то вроде этого:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/backrest_ynh/tree/testing --debug
или
sudo yunohost app upgrade backrest -u https://github.com/YunoHost-Apps/backrest_ynh/tree/testing --debug
```

**Больше информации о пакетировании приложений:** <https://yunohost.org/packaging_apps>
