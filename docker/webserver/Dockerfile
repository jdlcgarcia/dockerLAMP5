FROM php:5.6-apache
RUN docker-php-ext-install pdo pdo_mysql
RUN apt-get update -y && apt-get install -y libpng-dev
RUN a2enmod rewrite
RUN service apache2 restart
