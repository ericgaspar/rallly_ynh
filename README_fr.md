# Rallly pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/hedgedoc.svg)](https://dash.yunohost.org/appci/app/hedgedoc) ![](https://ci-apps.yunohost.org/ci/badges/hedgedoc.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/hedgedoc.maintain.svg)  
[![Installer Rallly avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=hedgedoc)

*[Read this readme in english.](./README.md)* 

> *Ce package vous permet d'installer Rallly rapidement et simplement sur un serveur YunoHost.  
Si vous n'avez pas YunoHost, consultez [le guide](https://yunohost.org/#/install) pour apprendre comment l'installer.*

## Vue d'ensemble
HedgeDoc est un service web de traitement de texte collaboratif en temps réel. Il utilise le langage Markdown.

**Version incluse :** 1.6.0

## Captures d'écran

![](https://demo.hedgedoc.org/screenshot.png)

## Démo

* [Démo officielle](https://rallly.co/HkLW9gobw)

## Configuration

Vous pouvez configurer HedgeDoc en modifiant le fichier `/var/www/hedgedoc/config.json` et en vous aidant de la [documentation](https://github.com/hedgedoc/server/blob/master/docs/configuration.md)

## Documentation

 * Documentation officielle : https://github.com/hedgedoc/server/tree/master/docs/
 * Documentation YunoHost : https://yunohost.org/#/app_hedgedoc_fr

## Caractéristiques spécifiques YunoHost

#### Support multi-utilisateur

* L'authentification LDAP est-elle prise en charge ? **Oui**
* L'application peut-elle être utilisée par plusieurs utilisateurs ? **Oui**

#### Architectures supportées

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/hedgedoc%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/hedgedoc/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/hedgedoc%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/hedgedoc/)

## Liens

 * Signaler un bug : https://github.com/YunoHost-Apps/hedgedoc_ynh/issues
 https://rallly.co/
 * Dépôt de l'application principale : https://github.com/lukevella/Rallly
 * Site web YunoHost : https://yunohost.org/

---

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/hedgedoc_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/hedgedoc_ynh/tree/testing --debug
ou
sudo yunohost app upgrade hedgedoc -u https://github.com/YunoHost-Apps/hedgedoc_ynh/tree/testing --debug
```
