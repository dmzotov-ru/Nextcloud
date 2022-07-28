FROM nextcloud:fpm-alpine
#COPY ./ca.crt /usr/local/share/ca-certificates/ca-oss-dev-cloud.crt
#RUN chmod 0755 /usr/local/share/ca-certificates/ca-oss-dev-cloud.crt 
#COPY ./s3conf /var/www/html/config/s3.config.php
#RUN chmod 0777 /var/www/html/config/s3.config.php && chown www-data:www-data -R /var/www/html/config
COPY ./ca.pem /usr/local/share/ca-certificates/ca-oss-dev-cloud.pem
#COPY ./devcloud-php-curl.ini /usr/local/etc/php/conf.d/devcloud-php-curl.ini
#COPY ./devcloud-php-openssl.ini /usr/local/etc/php/conf.d/devcloud-php-openssl.ini
RUN update-ca-certificates
