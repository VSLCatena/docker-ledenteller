FROM php:8-apache
COPY html/ /var/www/html/
RUN chown -R www-data:www-data /var/www/html/data
VOLUME ["/var/www/html/data"]
