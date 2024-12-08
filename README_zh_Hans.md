<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 上的 Backrest

[![集成程度](https://apps.yunohost.org/badge/integration/backrest)](https://ci-apps.yunohost.org/ci/apps/backrest/)
![工作状态](https://apps.yunohost.org/badge/state/backrest)
![维护状态](https://apps.yunohost.org/badge/maintained/backrest)

[![使用 YunoHost 安装 Backrest](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=backrest)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 Backrest。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

Backrest is a web-accessible backup solution built on top of restic. Backrest provides a WebUI which wraps the restic CLI and makes it easy to create repos, browse snapshots, and restore files. Additionally, Backrest can run in the background and take an opinionated approach to scheduling snapshots and orchestrating repo health operations.


**分发版本：** 1.5.1~ynh3

## 截图

![Backrest 的截图](./doc/screenshots/68747470733a2f2f663030302e6261636b626c617a6562322e636f6d2f66696c652f6773686172652f73637265656e73686f74732f323032342f53637265656e73686f742b66726f6d2b323032342d30312d30342b31382d31392d35302e706e67.png)
![Backrest 的截图](./doc/screenshots/68747470733a2f2f663030302e6261636b626c617a6562322e636f6d2f66696c652f6773686172652f73637265656e73686f74732f323032342f53637265656e73686f742b66726f6d2b323032342d30312d30342b31382d33302d31342e706e67.png)

## 文档与资源

- 官方用户文档： <https://garethgeorge.github.io/backrest/introduction/getting-started>
- 官方管理文档： <https://github.com/garethgeorge/backrest#installation>
- 上游应用代码库： <https://github.com/garethgeorge/backrest>
- YunoHost 商店： <https://apps.yunohost.org/app/backrest>
- 报告 bug： <https://github.com/YunoHost-Apps/backrest_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/backrest_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/backrest_ynh/tree/testing --debug
或
sudo yunohost app upgrade backrest -u https://github.com/YunoHost-Apps/backrest_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>
