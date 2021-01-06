FROM nginx
RUN mkdir -p /var/www/html
COPY default.conf /etc/nginx/conf.d/default.conf
COPY html/ /var/www/html
RUN chown -R nginx:nginx /var/www

