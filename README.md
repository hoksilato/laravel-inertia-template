# Project template with Laravel & Inertia

## Stack

- PHP 8.1
- Laravel 10.x (with Vite)
- MySQL 8.x
- Inertia
- TypeScript
- Vue
- Tailwind

## How to start

Copy `.env.devcontainer` to `.env` and change the DB configuration to whatever you want.

> Remember creating a new database.

```env
DB_CONNECTION=mysql
DB_HOST=mysql
DB_PORT=3306
DB_DATABASE=booking
DB_USERNAME=root
DB_PASSWORD=
```

Run `$ composer install` for installing dependencies.

Then execute `$ npm install` for installing node packages.

Finally execute `$ npm run dev` and you can access the site!
