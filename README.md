# Laravel Pay

A Laravel pay built with Laravel, PayPal and Stripe.

## Getting started

### Prerequisites
```bash
php -v
composer -V
```

### Installing

Clone this repo.

```bash
git clone https://github.com/sc27kr/laravel-pay.git
```

Copy .env.

```bash
cd laravel-pay
cp .env.example .env
```

Install the project dependencies.

```bash
composer i
```

Create database and migrate.

```bash
touch database/database.sqlite
php artisan migrate --seed
```

Set the applicatioin key.

```bash
php artisan key:generate
```

Serve the application on the PHP development server.

```
npm run dev
php artisan serve
```

List all registered routes.

```bash
php artisan route:list
```

Enjoy! [localhost:8000](http://localhost:8000)

## Built with

* PHP
* Laravel
* PayPal
* Stripe
