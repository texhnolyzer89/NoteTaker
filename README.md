# Laravel Task List app

A Laravel note taking app which uses Blade for the frontend.

## Dependencies

You must have the following programs installed on your machine in order to run this app:

##### php-cli
##### mysql
##### composer
##### laravel

## Installation

Install the packages necessary

```
  composer install
```

Remember to configure enable php extensions by editing the /etc/php.ini file (you must locate it on your system) and downloading extensions such as php-curl and the mysql driver.

Then you must configure your MySQL connection through your .env file. Create a database and table for the project.

After that, you can run the application with

```
  php artisan serve
```

And run the unit tests with

```
  php artisan test
```
