FROM nginx:latest
LABEL authors="mel"

COPY ./nginx/conf.d/default.conf /etc/nginx/conf.d/default.conf

COPY ./app/public /var/www/html/public