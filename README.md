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
