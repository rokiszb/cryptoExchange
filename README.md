Crypto exchange
=================================

Simple crypto exchange app
```
Symfony 5.3

PHP 8.0
```

## Setup

**1. You can simply run this app through docker**

```
docker-compose up -d
```

**2. Or old school way. Download Composer dependencies**

Make sure you have [Composer installed and php 7.2<](https://getcomposer.org/download/)
and then run:

```
cd app
composer install
```

**Start the web server**

You can use Nginx or Apache, but the built-in web server works
great:

```
php -S localhost:8080 -t public
```
or if you have symfony CLI installed:
```
cd app
symfony serve
```

Now check out the site at `http://localhost:8080`
