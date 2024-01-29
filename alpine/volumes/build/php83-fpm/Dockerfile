


FROM php:8.3-fpm-alpine3.19

RUN apk add --no-cache  $PHPIZE_DEPS
RUN apk add --update linux-headers && \
    pecl install xdebug
