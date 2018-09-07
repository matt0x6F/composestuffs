FROM nginx:stable-alpine

RUN rm /etc/nginx/conf.d/*
COPY ./default.conf /etc/nginx/conf.d

WORKDIR /usr/share/nginx/html
COPY ./html /usr/share/nginx/html

EXPOSE 8080