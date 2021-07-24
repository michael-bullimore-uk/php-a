FROM php:8.0-fpm

# Dependencies
RUN apt-get update && apt-get install -y git unzip

# PHP extensions
# RUN docker-php-ext-install mbstring

# Composer
COPY --from=composer /usr/bin/composer /usr/bin/composer

WORKDIR /var/www/php-a
