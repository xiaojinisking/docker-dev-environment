FROM php:fpm

COPY sources.list /etc/apt/sources.list

RUN pecl install xdebug-2.5.0 \
    && pecl install swoole \
    && pecl install redis-3.1.4RC3 \
    && docker-php-ext-enable  xdebug swoole redis
