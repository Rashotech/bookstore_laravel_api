## About Bookstore API

Bookstore API is an API built using Laravel v8. It consists of CRUD operations on Books and Authors Model. The Book and Authors Model have a many-to-many relationship. The API also have a user authentication created using Laravel Passport.

## Project Setup

- Clone this Repository
- cd to /bookstore
```
composer install
```

- create .env file and set up the database

```
php artisan migrate
```

```
php artisan serve
```
