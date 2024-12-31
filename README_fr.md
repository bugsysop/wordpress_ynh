# WordPress pour YunoHost (fork)

Ce paquetage vous permet d’installer WordPress rapidement et simplement sur un serveur YunoHost.

🔴 Warning : Il s’agit d’un fork de l’application _officielle_ YNH, personnalisé pour les besoins du serveur tmprs.net.

Nous vous recommandons d’installer WordPress à partir de la version originale de Yunohost (utiliser cette version se fait à vos propres risques).

[![Install WordPress with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=wordpress)


## Hacklog

Testé:
- Installation
- Mise à jour
- Supprimer

Non testé:
- Multisite
- Restauration

**Version installée :** 6.7.1~ynh1     
Testé avec yunohost 12.0.7

## Capture d’écran

![Screenshot of WordPress](./doc/screenshots/screen-themes.png)


## Documentation et resources

- Site officiel de l’app : <https://wordpress.org/>
- Documentation officielle de l’admin : <https://codex.wordpress.org/>
- Dépôt de code officiel de l’app : <https://core.trac.wordpress.org/browser>
- Catalogue d’applications YunoHost : <https://apps.yunohost.org/app/wordpress>
- Signaler un bug : <https://github.com/YunoHost-Apps/wordpress_ynh/issues>

## Informations pour les développeurs

Installer :

```bash
sudo yunohost app install https://github.com//bugsysop/wordpress_ynh --debug
```

Mettre à jour:

```bash
sudo yunohost app upgrade wordpress -u https://github.com//bugsysop/wordpress_ynh --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
