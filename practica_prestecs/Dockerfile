# Partimos de PHP con Apache
FROM php:8.2-apache

# Instalamos la extensión mysqli (necesaria para conectar con MariaDB)
# El comando docker-php-ext-install es una herramienta propia de la imagen de PHP
RUN docker-php-ext-install mysqli && docker-php-ext-enable mysqli

# Actualizamos el sistema
RUN apt-get update && apt-get upgrade -y