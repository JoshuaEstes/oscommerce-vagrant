joshuaestes/oscommerce-vagrant
==============================

This repository provides a way to setup and install osCommerce for working on
plugins and other development related tasks.

Installation
============

```bash
git clone https://github.com/JoshuaEstes/oscommerce-vagrant.git
cd oscommerce-vagrant
curl -sS https://getcomposer.org/installer | php
php composer.phar install
php bin/daedalus oscommerceinstall
vagrant up
```
