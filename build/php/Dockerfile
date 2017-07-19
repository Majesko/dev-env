FROM php:fpm-alpine

RUN apk add --no-cache libmcrypt-dev libxml2-dev zlib-dev
RUN docker-php-ext-install iconv mcrypt xml pdo_mysql tokenizer zip

