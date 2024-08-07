FROM php:8.0-fpm

RUN docker-php-ext-install pdo pdo_mysql

COPY php-fpm.conf /usr/local/etc/php-fpm.d/zz-docker.conf

