FROM nginx:latest as web

# - ./nginx/conf.d/default.conf:/etc/nginx/conf.d/default.conf

COPY ./nginx/conf.d/default.conf /etc/nginx/conf.d/default.conf

COPY ./app/public /var/www/html/public