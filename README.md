# PHPSysInfo for Yunohost

[![Integration level](https://dash.yunohost.org/integration/phpsysinfo.svg)](https://dash.yunohost.org/appci/app/phpsysinfo) ![](https://ci-apps.yunohost.org/ci/badges/phpsysinfo.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/phpsysinfo.maintain.svg)

[![Install Custom Webapp with YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=phpsysinfo)

> *This package allow you to install PHPSysInfo quickly and simply on a YunoHost server.  
If you don't have YunoHost, please see [here](https://yunohost.org/#/install) to know how to install and enjoy it.*

## Overview

A customizable PHP script that displays information about your system nicely.

**Shipped version:** 3.3.4
**License:** [GNU General Public License v2.0](https://github.com/phpsysinfo/phpsysinfo/blob/master/COPYING)

## Screenshots
![screenshot phpsyinfo](https://a.fsdn.com/con/app/proj/phpsysinfo/screenshots/294411.jpg/max/max/1 "phpsysinfo screenshot")

## Demo
[Demo on NAS Synology](http://phpsysinfo.sourceforge.net/multi/index.php?disp=bootstrap&xml=synology)

## Configuration
Edit `phpsysinfo.ini` in `/var/www/YOURPATH/phpsysinfo.ini`.

## Documentation

## YunoHost specific features

#### Multi-users support
No multi-users in this app. Simply a web page.

#### Supported architectures

* x86-64b - [![Build Status](https://ci-apps.yunohost.org/ci/logs/phpsysinfo%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/phpsysinfo/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/phpsysinfo%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/phpsysinfo/)

## Limitations

## Additional information

## Links
* PHPSysInfo website: https://phpsysinfo.github.io/phpsysinfo/
---

Developers info
----------------

**Only if you want to use a testing branch for coding, instead of merging directly into master.**
Please do your pull request to the [testing branch](https://github.com/YunoHost-Apps/phpsysinfo_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/phpsysinfo_ynh/tree/testing --debug
or
sudo yunohost app upgrade my_webapp -u https://github.com/YunoHost-Apps/phpsysinfo_ynh/tree/testing --debug
```
