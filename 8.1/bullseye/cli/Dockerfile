FROM php:8.1-cli-bullseye

RUN apt update && apt install libpq-dev

RUN docker-php-ext-install pdo_pgsql
