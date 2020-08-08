FROM php:7.2.7-fpm-alpine3.7
RUN apk update; \
    apk upgrade; \
    apk add libpng-dev;
RUN docker-php-ext-install mysqli gd fileinfo iconv pdo pdo_mysql; \
    docker-php-ext-enable mysqli gd fileinfo iconv pdo pdo_mysql;