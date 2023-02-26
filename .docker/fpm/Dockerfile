FROM php:8.1-fpm

RUN apt-get update \
  && docker-php-ext-install pdo pdo_mysql 

COPY --from=composer:latest /usr/bin/composer /usr/local/bin/composer
