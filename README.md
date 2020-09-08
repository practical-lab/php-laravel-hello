# php-laravel-hello

## CLI

### Install phpenv

```bash
anyenv install phpenv
```

### Install php

```bash
phpenv install 7.3.22
```

### Install Composer

[Download Composer](https://getcomposer.org/download/)

```bash
php -r "copy('https://getcomposer.org/installer', 'composer-setup.php');"
php -r "if (hash_file('sha384', 'composer-setup.php') === '8a6138e2a05a8c28539c9f0fb361159823655d7ad2deecb371b04a83966c61223adc522b0189079e3e9e277cd72b8897') { echo 'Installer verified'; } else { echo 'Installer corrupt'; unlink('composer-setup.php'); } echo PHP_EOL;"
php composer-setup.php
php -r "unlink('composer-setup.php');"
```

### Install Laravel

```bash
composer global require laravel/installer
```

### Create laravel project

```bash
laravel new php-laravel-hello
composer create-project --prefer-dist php-laravel-hello
```

### Run app

```bash
php artisan serve
```
