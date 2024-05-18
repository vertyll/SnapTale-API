# SnapTale-API

## Setup

Make sure to install the dependencies:

```bash
composer install 

cp .env.example .env 

php artisan cache:clear

composer dump-autoload

php artisan key:generate

composer require laravel/breeze --dev

php artisan serve
```

Create a DATABASE. Make sure the DB_DATABASE in the .env is the same and then run this command

```
php artisan migrate
```
