FROM php:8.0.2-fpm

RUN apt-get update && apt-get install -y \
    git \
    curl \
    zip \
    unzip

COPY --from=composer/composer:latest-bin /composer /usr/bin/composer



WORKDIR /var/www/meu-projeto-php