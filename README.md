## Technologies and Features Used
-   Laravel 8.0
-   JWT Auth via [Laravel Sanctum](https://laravel.com/docs/master/sanctum)
-   REST API

```bash
git clone <github url>

cd foodapp-server

composer install --no-interaction
npm install
```

-   Edit `.env` and set your database connection details

```bash
cp .env.example .env
```

-   Genrate keys and migrate tables

```bash
php artisan key:generate
php artisan migrate
php artisan db:seed
```
