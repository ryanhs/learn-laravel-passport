# Learn Laravel Passport

## Installation

1. `composer install`
2. .env
3. `php artisan passport:install`
4. add new user
5. check in db for oauth2 client with **Password Grant Client**
6. import to postman: `Learn Laravel Passport.postman_collection.json`
7. run postman

Postman environment variables:

- client_id
- client_secret
- admin_username  \**email*
- admin_password
- access_token
- refresh_token


**notes:**

* I forgot to make environment variable for base_url, default use `http://passport.dev` :-)
