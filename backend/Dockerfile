FROM php:8.2-apache

# Install ekstensi PHP untuk MySQL
RUN docker-php-ext-install mysqli pdo pdo_mysql

# Set document root ke folder src
WORKDIR /var/www/html
