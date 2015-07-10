# Ramp Up on Puphpet + Symfony2


## Requirements

* [VirtualBox](https://www.virtualbox.org/wiki/Downloads)
* [Vagrant](https://www.vagrantup.com/downloads.html)


## Required Installs

You must install the following:

```
vagrant plugin install vagrant-bindfs
```


## Vagrant Config

* **IP:** 192.168.56.189
* **CPU(s):** 1
* **Memory:** 2GB
* **Linux OS:** Unbuntu Trusty 12.04 LTS x64
* **System Packages:** vim, git, curl
* **Server:** Apache2
* **Apache Modules:** headers, rewrite
* **Virtual Hosts:** www.tribunemls.dev, tribunemls.dev, api.fsbo.dev, mdwiki.tribunemls.dev, static.tribunemls.dev
* **PHP Version:** 5.4 using mod_php
* **PHP Modules:** cli, common, curl, gd, imagick, intl, mcrypt, xsl
* **Composer Installed**
* **Xdebug Installed**
* **MySQL DB User:** root
* **MySQL DB Pass:** root