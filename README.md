## Laravel Skeleton

Based on official [Laravel app repository](https://github.com/laravel/laravel).
The version is based on the Laravel Framework one. For example, `v6.6.0` is based on Framework version `v6.6`.

Pre-installed packages:
- [Laravel Passport](https://github.com/laravel/passport)
- [Laravel UI](https://github.com/laravel/ui)
- [Laravel IDE Helper](https://github.com/barryvdh/laravel-ide-helper)
- [Data Transfer Objects](https://github.com/spatie/data-transfer-object)
- [Laravel Model States](https://github.com/spatie/laravel-model-states)
- [PHP Enum](https://github.com/myclabs/php-enum)

## Installation & setup
Install vendor packages:
```sh
composer install
npm install
```

Copy environment example file and generate key:
```sh
cp .env.example .env
php artisan key:generate
```
Edit `.env` with your database configuration and other parameters.

Migrate database:
```sh
php artisan migrate
```

Passport installation:
```sh
php artisan passport:install
```

Generate public assets:
```sh
npm run dev
```
