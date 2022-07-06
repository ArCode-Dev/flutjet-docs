

#  API

Flutjet API made from [Laravel 9](https://laravel.com/) <br>
Example of API Documentations [Here](http://103.82.243.88/docs)

## Requirements
- PHP >= 8.0
- BCMath PHP Extension
- Ctype PHP Extension
- cURL PHP Extension
- DOM PHP Extension
- Fileinfo PHP Extension
- JSON PHP Extension
- Mbstring PHP Extension
- OpenSSL PHP Extension
- PCRE PHP Extension
- PDO PHP Extension
- Tokenizer PHP Extension
- XML PHP Extension


## Installation

### 1. Download
  Clone/Download this repository place on your server. *(I highly recommend you use either Laravel Homestead or Laravel Valet, to get the optimal server configuration and no errors through installation.)*

### 2. Environment Files
This project comes with a `.env.example` file in the root of the project.

Copy `env.example` to `.env` where you prepare your environment.

**Note:** Make sure you do not rename `.env.example`, for team purposes.

Edit App URL :
```bash
APP_URL={YOUR_APP_URL}
```

Edit Firebase Project ID :
```bash
FIREBASE_PROJECT_ID={YOUR_FIREBASE_PROJECT_ID}
```

Edit Database Config :
```bash
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=
DB_USERNAME=
DB_PASSWORD=
```

Edit Google Credentials :
```bash
GOOGLE_CLIENT_ID=
GOOGLE_CLIENT_SECRET=
```

### 3. Composer
Larajet API dependencies are managed through the [PHP Composer tool](https://getcomposer.org/). Install the depencencies by navigating into your project in terminal and typing this command:
```bash
composer install
```

After that run :
```bash
php artisan migrate:fresh --seed
```

## API Documentation 
Generate and publish api docs, in terminal and typing this command:
```bash
php artisan scribe:generate
```

You can visit the generated API documentation in http://{$baseUrl}/docs in your local machine.

or here's the published postman [here](working in progress)


**Notes:** 
- If you run this via [Homestead's](https://laravel.com/docs/homestead) ssh, you can this command: `phpunit` (in your project directory).
- After running testing, you can check generated code coverage from `.build` folder.


## Flutjet API Built With

* [laravel/laravel](https://github.com/laravel/laravel) - Web application framework with expressive, elegant syntax.
* [laravel/sanctum](https://github.com/laravel/sanctum) - Provides a featherweight authentication system for SPAs and simple APIs.
* [laravel/socialite](https://github.com/knuckleswtf/scribe) - It handles almost all of the boilerplate social authentication code you are dreading writing.
* [spatie/laravel-permission](https://github.com/spatie/laravel-permission) - Associate users with permissions and roles
* [spatie/laravel-query-builder](https://github.com/spatie/laravel-query-builder) - Build Eloquent queries from API requests.
* [spatie/laravel-json-api-paginate](https://github.com/spatie/laravel-json-api-paginate) - A paginator that plays nice with the JSON API spec.
* [knuckleswtf/scribe](https://github.com/knuckleswtf/scribe) - Generate API documentation for humans from your Laravel codebase.
* [kreait/firebase-tokens-php](https://github.com/kreait/firebase-tokens-php) - A library to work with Google Firebase tokens. You can use it to create custom tokens and verify ID Tokens.
