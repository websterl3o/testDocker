FROM wyveo/nginx-php-fpm:php72

WORKDIR /usr/share/nginx/

RUN composer self-update --2

RUN rm -rf /usr/share/nginx/html

RUN ln -s public html
