# PHPBack pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/phpback.svg)](https://dash.yunohost.org/appci/app/phpback) ![](https://ci-apps.yunohost.org/ci/badges/phpback.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/phpback.maintain.svg)  
[![Installer PHPBack avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=phpback)

*[Read this readme in english.](./README.md)*
*[Lire ce readme en français.](./README_fr.md)*

> *Ce package vous permet d'installer PHPBack rapidement et simplement sur un serveur YunoHost.
Si vous n'avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l'installer et en profiter.*

## Vue d'ensemble

PHPBack is an open source feedback system you can use for your website. It gives your customers a way to communicate their ideas to improve your products. User feedback has proved to be really effective even if you have a community project or a commercial project. 

**Version incluse :** 1.3.2~ynh1

**Démo :** https://www.phpback.org/demo/

## Captures d'écran

![](./doc/screenshots/slider-item-1.png)

## Avertissements / informations importantes

* Any known limitations, constrains or stuff not working, such as (but not limited to):
    * requiring a full dedicated domain ?
    * architectures not supported ?
    * not-working single-sign on or LDAP integration ?
    * the app requires an important amount of RAM / disk / .. to install or to work properly
    * etc...

* Other infos that people should be aware of, such as:
    * any specific step to perform after installing (such as manually finishing the install, specific admin credentials, ...)
    * how to configure / administrate the application if it ain't obvious
    * upgrade process / specificities / things to be aware of ?
    * security considerations ?

## Documentations et ressources

* Site officiel de l'app : https://www.phpback.org/
* Dépôt de code officiel de l'app : https://github.com/phpback/phpback
* Documentation YunoHost pour cette app : https://yunohost.org/app_phpback
* Signaler un bug : https://github.com/YunoHost-Apps/phpback_ynh/issues

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/phpback_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/phpback_ynh/tree/testing --debug
ou
sudo yunohost app upgrade phpback -u https://github.com/YunoHost-Apps/phpback_ynh/tree/testing --debug
```

**Plus d'infos sur le packaging d'applications :** https://yunohost.org/packaging_apps