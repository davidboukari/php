# php


## Editors
* netbeans
* sublimetext
* atom editor
* phpStorm
* ShareCode

## Frameworks
* Symfony

## Install php

```bash
yum install epel-release yum-utils
yum install http://rpms.remirepo.net/enterprise/remi-release-7.rpm
yum-config-manager --enable remi-php74
yum install php php-common php-opcache php-mcrypt php-cli php-gd php-curl php-mysql php-zipstream php-zip
yum install unzip
```
## Enable a specific version

```bash
yum-config-manager --enable remi-php74
```

```bash
https://ostechnix.com/how-to-switch-between-multiple-php-versions-in-ubuntu/
$ sudo a2dismod php7.2
Module php7.2 disabled.
To activate the new configuration, you need to run:
systemctl restart apache2

Next, enable PHP 5.6 module:

$ sudo a2enmod php5.6

Set PHP 5.6 as default version:

$ sudo update-alternatives --set php /usr/bin/php5.6

Alternatively, you can run the following command to set which system wide version of PHP you want to use by default.

$ sudo update-alternatives --config php
```
