# laravel-blog-rest
**Laravel 5.4 blog with REST API**

This is a sample project to show how you could write an API using Laravel 5.4

There will be some minor differences, specially regarding downloaded packages, as I used the excellent Laravel Ide Helper to setup PhpStorm bindings and other features.
Running the API

It's very simple to get the API up and running. First, create the database (and database user if necessary) and add them to the .env file.

`DB_DATABASE=your_db_name
DB_USERNAME=your_db_user
DB_PASSWORD=your_password`

Then install, migrate, seed, all that jazz:

    composer install
    php artisan migrate
    php artisan db:seed
    php artisan serve

The API will be running on localhost:8000.