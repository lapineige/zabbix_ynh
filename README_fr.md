<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# Zabbix pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/zabbix.svg)](https://dash.yunohost.org/appci/app/zabbix) ![Statut du fonctionnement](https://ci-apps.yunohost.org/ci/badges/zabbix.status.svg) ![Statut de maintenance](https://ci-apps.yunohost.org/ci/badges/zabbix.maintain.svg)  
[![Installer Zabbix avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=zabbix)

*[Read this readme in english.](./README.md)*

> *Ce package vous permet d'installer Zabbix rapidement et simplement sur un serveur YunoHost.
Si vous n'avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l'installer et en profiter.*

## Vue d'ensemble

Un outil de surveillance pour divers composants informatiques, notamment les réseaux, les serveurs, les machines virtuelles et les services en nuage.


**Version incluse :** 5.0.20~ynh2

## Captures d'écran

![Capture d'écran de Zabbix](./doc/screenshots/screenshot1.png)

## Avertissements / informations importantes

#### Limitations connues et autres informations importantes

* Seule l'architecture x86_64 est prise en charge
* L'authentification unique (SSO) fonctionne.
* Ne modifiez pas le mot de passe de l'utilisateur administrateur par défaut. L'utilisateur est désactivé juste après l'installation mais il est utilisé pour mettre à jour les modèles.
* Le port du serveur Zabbix n'est pas ouvert par défaut pour la surveillance externe (agent actif).
* Vous pouvez ajouter vos utilisateurs dans un groupe dans Zabbix (pour les autorisations/droits).
* Un modèle YunoHost est importé et lié à l'hôte "Zabbix-server" (127.0.0.1) pour la surveillance de base de YunoHost.
## Documentations et ressources

* Site officiel de l'app : <https://www.zabbix.com>
* Documentation officielle de l'admin : <https://www.zabbix.com/manuals>
* Dépôt de code officiel de l'app : <https://github.com/zabbix/zabbix>
* Documentation YunoHost pour cette app : <https://yunohost.org/app_zabbix>
* Signaler un bug : <https://github.com/YunoHost-Apps/zabbix_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/zabbix_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.

``` bash
sudo yunohost app install https://github.com/YunoHost-Apps/zabbix_ynh/tree/testing --debug
ou
sudo yunohost app upgrade zabbix -u https://github.com/YunoHost-Apps/zabbix_ynh/tree/testing --debug
```

**Plus d'infos sur le packaging d'applications :** <https://yunohost.org/packaging_apps>
