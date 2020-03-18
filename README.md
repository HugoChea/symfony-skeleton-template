# Symfony Skeleton Template
Base template to start a Symfony project (v4.4 -LTS) with basic controller and registration & auth
## Requirements
- PHP 7 or above (or edit docker-compose file)
- Composer
## Start the project
- Install all dependancies : `composer install`
- Running docker for mysql container (if lazy, can add php and nginx container, etc...) : `docker-compose up -d`
- Configure .env file for data
- Start a local web server with symfony : `symfony server:start` / `php bin/console server:start`
