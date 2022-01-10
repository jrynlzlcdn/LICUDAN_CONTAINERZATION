FROM php:8-apache

COPY index.html /var/www/html/index.html
COPY info.php /var/www/html

EXPOSE 80

RUN echo "ServerName localhost" >> /etc/apache2/apache2.conf
CMD ["/usr/sbin/apache2ctl", "-D", "FOREGROUND"]
