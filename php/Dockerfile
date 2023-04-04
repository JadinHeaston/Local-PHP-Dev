FROM php:${PHP_VERSION:-8.1.17-}fpm-alpine${ALPINE_VERSION:-}

RUN apk update; \
    apk upgrade;

RUN docker-php-ext-install mysqli