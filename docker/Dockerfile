FROM php:5.6-apache

RUN docker-php-ext-install mysqli

RUN  cp  /usr/local/etc/php/php.ini-development /usr/local/etc/php/conf.d/php.ini  

RUN echo 'date.timezone = "US/Central"' >> /usr/local/etc/php/conf.d/php.ini

EXPOSE 80
