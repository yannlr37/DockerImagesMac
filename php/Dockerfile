FROM php:7.4-apache

RUN apt-get update
RUN apt-get install -y vim libxml2-dev
RUN docker-php-ext-install pdo_mysql
RUN docker-php-ext-install soap

RUN curl -sS https://getcomposer.org/installer | php -- --install-dir=/usr/local/bin --filename=composer
