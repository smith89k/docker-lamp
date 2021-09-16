FROM php:7.4.22-apache-buster

LABEL 'creator'='Asif Iqbal asif@adommo.com'

RUN docker-php-ext-install mysqli && \
	docker-php-ext-install pdo_mysql

# Enable apache modules.
RUN a2enmod rewrite headers
