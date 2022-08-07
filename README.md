<h1 align="center">LARAVEL REST API</h1>

<p align="justify">Building a REST API using Laravel 9. And implement authentication using API keys with Laravel Sanctum.</p>
•   Author: <a href="https://abby2727.github.io/my-portfolio/"> Abdul Pangandaman </a> <br>
•   Twitter: <a href="https://twitter.com/abby_2727"> @abby_2727 </a> <br>
•   Instagram: <a href="https://www.instagram.com/abbyyyyys_/"> @abbyyyyys_ </a> <br> <br>

## Requirement
•   PHP 8.0.2 or higher

## Installation
Setting up your development environment on your local machine:
```
git clone https://github.com/abby2727/laravel-rest-api.git
cd laravel-rest-api
composer install
php artisan key:generate
php artisan migrate
php artisan optimize
php artisan serve
```
## Before Starting

Create Database and Set-up db credential on .env
```
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=laravel_rest_api
DB_USERNAME={USERNAME}
DB_PASSWORD={PASSWORD}
```
## Note:
•   It doesn't contain any frontend. <br>
•   I'am using a Postman platform for testing my API.
