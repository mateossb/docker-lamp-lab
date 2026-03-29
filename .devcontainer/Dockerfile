FROM php:8.2-apache

RUN apt-get update && apt-get install -y     mariadb-client     curl     nano     iputils-ping     net-tools     && docker-php-ext-install mysqli     && rm -rf /var/lib/apt/lists/*

RUN a2enmod rewrite

WORKDIR /var/www/html
