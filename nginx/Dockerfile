FROM nginx

RUN rm /etc/nginx/conf.d/default.conf

COPY nginx.conf /etc/nginx/

COPY vhost.conf /etc/nginx/sites-enabled/
