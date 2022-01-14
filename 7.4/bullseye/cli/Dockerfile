FROM php:7.4-cli-bullseye

RUN apt update && apt install libpq-dev

RUN docker-php-ext-install pdo_pgsql
