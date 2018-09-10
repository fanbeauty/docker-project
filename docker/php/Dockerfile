FROM php:7.2.8-fpm

#install pdo
RUN docker-php-ext-install pdo_mysql 

#Permission fix
RUN usermod -u 1000 www-data && usermod -G staff www-data

