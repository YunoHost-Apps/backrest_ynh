<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# Backrest pour YunoHost

[![Niveau d’intégration](https://apps.yunohost.org/badge/integration/backrest)](https://ci-apps.yunohost.org/ci/apps/backrest/)
![Statut du fonctionnement](https://apps.yunohost.org/badge/state/backrest)
![Statut de maintenance](https://apps.yunohost.org/badge/maintained/backrest)

[![Installer Backrest avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=backrest)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer Backrest rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

Backrest est une solution de sauvegarde accessible via une interface Web basée sur Restic. Backrest fournit une interface Web qui enveloppe la CLI restic et facilite la création de dépôts, la navigation dans les instantanés et la restauration de fichiers. De plus, Backrest peut s'exécuter en arrière-plan et adopter une approche avisée pour planifier des instantanés et orchestrer les opérations de santé des dépôts.


**Version incluse :** 1.5.1~ynh3

## Captures d’écran

![Capture d’écran de Backrest](./doc/screenshots/68747470733a2f2f663030302e6261636b626c617a6562322e636f6d2f66696c652f6773686172652f73637265656e73686f74732f323032342f53637265656e73686f742b66726f6d2b323032342d30312d30342b31382d31392d35302e706e67.png)
![Capture d’écran de Backrest](./doc/screenshots/68747470733a2f2f663030302e6261636b626c617a6562322e636f6d2f66696c652f6773686172652f73637265656e73686f74732f323032342f53637265656e73686f742b66726f6d2b323032342d30312d30342b31382d33302d31342e706e67.png)

## Documentations et ressources

- Documentation officielle utilisateur : <https://garethgeorge.github.io/backrest/introduction/getting-started>
- Documentation officielle de l’admin : <https://github.com/garethgeorge/backrest#installation>
- Dépôt de code officiel de l’app : <https://github.com/garethgeorge/backrest>
- YunoHost Store : <https://apps.yunohost.org/app/backrest>
- Signaler un bug : <https://github.com/YunoHost-Apps/backrest_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/backrest_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/backrest_ynh/tree/testing --debug
ou
sudo yunohost app upgrade backrest -u https://github.com/YunoHost-Apps/backrest_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
