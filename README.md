# Unofficial PclZip library in Laravel package

Version of PclZip = 2.8.2

Document: http://www.phpconcept.net/pclzip

## Install

update root `composer.json`:

```json
"require": {
    "laravel/framework": "4.2.*",
    "chee/pclzip": "dev-master"
},
```

then run `composer update`.

update app/config/app.php:

Service Provider:

```php
'Chee\Pclzip\PclzipServiceProvider'
```

Aliases[Facades]:

```php
'Pclzip'		  => 'Chee\Pclzip\Pclzip'
```
