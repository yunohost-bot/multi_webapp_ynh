# Multi webapp pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/multi_webapp.svg)](https://dash.yunohost.org/appci/app/multi_webapp)  
[![Installer Multi webapp avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=multi_webapp)

*[Read this readme in english.](./README.md)*

> *Ce package vous permet d'installer Multi webapp rapidement et simplement sur un serveur YunoHost.  
Si vous n'avez pas YunoHost, merci de regarder [ici](https://yunohost.org/#/install_fr) pour savoir comment l'installer et en profiter.*

## Résumé

Conteneur d'application web vierge conçu pour être utilisé avec une application web non encore packagée.
Cette application peut être installée plusieurs fois.

**Version embarquée:** NA

## Captures d'écran

## Démo

Aucune démo pour cette application.

## Configuration

## Documentation

 * Documentation YunoHost: Il n'y a pas d'autre documentation, n'hésitez pas à contribuer.

## Fonctionnalités spécifiques à YunoHost

#### Support multi-utilisateurs

#### Architectures supportées.

* x86-64b - [![Build Status](https://ci-apps.yunohost.org/jenkins/job/multi_webapp%20(Community)/badge/icon)](https://ci-apps.yunohost.org/jenkins/job/multi_webapp%20(Community)/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/jenkins/job/multi_webapp%20(Community)%20(%7EARM%7E)/badge/icon)](https://ci-apps-arm.yunohost.org/jenkins/job/multi_webapp%20(Community)%20(%7EARM%7E)/)
* Jessie x86-64b - [![Build Status](https://ci-stretch.nohost.me/jenkins/job/multi_webapp%20(Community)/badge/icon)](https://ci-stretch.nohost.me/jenkins/job/multi_webapp%20(Community)/)

## Limitations

## Informations additionnelles

Un répertoire sera créé pour votre application dans `/var/www/webapp_USER/DOMAIN_PATH`. Votre application doit être placée à l'intérieur.
Vous pouvez trouver une configuration standard de nginx dans `/etc/nginx/conf.d/DOMAIN.d/webapp_DOMAIN_PATH.conf` et une configuration php standard dans `/etc/php5/fpm/pool.d/webapp_DOMAIN_PATH.conf` et `/etc/php5/fpm/conf.d/20-webapp_DOMAIN_PATH.ini`.
Si vous demandez une base de données, vos identifiants seront dans le fichier `/var/www/webapp_USER/DOMAIN_PATH/db_info.txt`.

## Liens

 * Reporter un bug: https://github.com/YunoHost-Apps/multi_webapp_ynh/issues
 * Site de YunoHost: https://yunohost.org/

---

Informations à l'intention des développeurs
----------------

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/multi_webapp_ynh/tree/testing).

Pour tester la branche testing, merci de procéder ainsi.
```
sudo yunohost app install https://github.com/YunoHost-Apps/multi_webapp_ynh/tree/testing --verbose
ou
sudo yunohost app upgrade multi_webapp -u https://github.com/YunoHost-Apps/multi_webapp_ynh/tree/testing --verbose
```