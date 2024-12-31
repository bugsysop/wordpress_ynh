# WordPress for YunoHost (fork)

This package allows you to install WordPress quickly and simply on a YunoHost server.

:red_circle: **Warning:** This is a _fork_ of the official YNH App, customized for tmprs.net server needs.

We recommend you to install WordPress with the vanilla Yunohost version (or use at your own risks).

[![Install WordPress with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=wordpress)


## Hacklog

Tested:
- Install
- Upgrade
- Remove

Untested:
- Multisite
- Restaure

**Shipped version:** 6.7.1~ynh1 
Tested with yunohost 12.0.7

## Screenshots

![Screenshot of WordPress](./doc/screenshots/screen-themes.png)


## Documentation and resources

- Official app website: <https://wordpress.org/>
- Official admin documentation: <https://codex.wordpress.org/>
- Upstream app code repository: <https://core.trac.wordpress.org/browser>
- YunoHost Store: <https://apps.yunohost.org/app/wordpress>
- Report a bug: <https://github.com/YunoHost-Apps/wordpress_ynh/issues>

## Developer info

Install app (branch: `custom`):

```bash
sudo yunohost app install https://github.com//bugsysop/wordpress_ynh --debug
```

Upgrade app (branch: `custom`):

```bash
sudo yunohost app upgrade wordpress -u https://github.com//bugsysop/wordpress_ynh --debug
```
Install testing (branch: `next`):

```bash
sudo yunohost app install https://github.com/bugsysop/wordpress_ynh/tree/next --debug
```

Upgrade to testing (branch: `next`):

```bash
sudo yunohost app upgrade wordpress -u https://github.com/bugsysop/wordpress_ynh/tree/next --debug
```

**More info regarding YNH app packaging:** <https://yunohost.org/packaging_apps>
