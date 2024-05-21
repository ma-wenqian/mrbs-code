FROM php:7.3-apache

RUN a2enmod rewrite
RUN docker-php-ext-install mysqli pdo pdo_mysql 
RUN apt-get update && apt-get install -y locales-all
