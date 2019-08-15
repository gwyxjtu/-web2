FROM ctftraining/base_image_nginx_mysql_php_56

COPY src /var/www/html
     
RUN cp -f /var/www/html/nginx.conf /etc/nginx/nginx.conf \
    && rm -rf /var/www/html/nginx.conf
