# Partimos de PHP con Apache
FROM php:8.2-apache

# Instalamos la extensión mysqli (necesaria para conectar con MariaDB)
RUN docker-php-ext-install mysqli && docker-php-ext-enable mysqli

# Carpeta de trabajo del servidor web
WORKDIR /var/www/html