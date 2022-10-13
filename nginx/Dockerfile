FROM nginx

# Change Nginx config here...
RUN rm -rf /etc/nginx/conf.d/default.conf
RUN rm -rf /etc/nginx/nginx.conf
ADD ./nginx.conf /etc/nginx/nginx.conf
ADD ./nginx-site.conf /etc/nginx/conf.d/nginx-site.conf
ADD ./nginx-laravel.conf /etc/nginx/conf.d/nginx-laravel.conf
ADD ./php-fpm.conf /etc/nginx/conf.d/php-fpm.conf