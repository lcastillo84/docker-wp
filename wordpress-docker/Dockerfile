FROM wordpress:latest


# Copiar configuración
COPY ./php.ini /usr/local/etc/php/conf.d/php.ini
COPY ./000-default.conf /etc/apache2/sites-available/000-default.conf
COPY ./ports.conf /etc/apache2/ports.conf

# Abrir puerto
EXPOSE 8080
