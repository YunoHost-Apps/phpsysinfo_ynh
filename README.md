# PHPSysInfo for Yunohost

[![Integration level](https://dash.yunohost.org/appci/app/phpsysinfo_ynh.svg)](https://dash.yunohost.org/appci/app/phpsysinfo_ynh)  
[![Install Custom Webapp with YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=phpsysinfo_ynh)

> *This package allow you to install PHPSysInfo quickly and simply on a YunoHost server.  
If you don't have YunoHost, please see [here](https://yunohost.org/#/install) to know how to install and enjoy it.*

## Overview

A customizable PHP script that displays information about your system nicely.

**Shipped version:** 3.3.2

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

* x86-64b - [![Build Status](https://ci-apps.yunohost.org/ci/logs/phpsysinfo_ynh%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/phpsysinfo_ynh/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/phpsysinfo_ynh%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/phpsysinfo_ynh/)
* Jessie x86-64b - [![Build Status](https://ci-stretch.nohost.me/ci/logs/phpsysinfo_ynh%20%28Apps%29.svg)](https://ci-stretch.nohost.me/ci/apps/phpsysinfo_ynh/)

## Limitations

## Additional information

## Links
* PHPSysInfo website: https://phpsysinfo.github.io/phpsysinfo/
---

Developers info
----------------

**Only if you want to use a testing branch for coding, instead of merging directly into master.**
Please do your pull request to the [testing branch](https://github.com/inrepublica/phpsysinfo_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/phpsysinfo_ynh/tree/testing --debug
or
sudo yunohost app upgrade my_webapp -u https://github.com/YunoHost-Apps/phpsysinfo_ynh/tree/testing --debug
```
