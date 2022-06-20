# Relay Tests

## Laravel Framework

```
cd laravel/framework

composer install
composer require cachewerk/relay

git apply ../laravel-framework.patch

vendor/bin/phpunit
```

## Laravel Horizon

```
cd laravel/horizon

composer install
composer require cachewerk/relay

git apply ../laravel-horizon.patch

vendor/bin/phpunit
```
