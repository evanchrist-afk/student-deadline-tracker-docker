FROM php:8.1-apache

RUN docker-php-ext-install mysqli
RUN apt-get update && apt-get install -y libpng-dev
RUN docker-php-ext-install gd

COPY ./app/ /var/www/html/

EXPOSE 80
