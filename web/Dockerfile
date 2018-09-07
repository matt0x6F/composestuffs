FROM nginx:stable-alpine

RUN rm /etc/nginx/conf.d/*

COPY ./config/default.conf /etc/nginx/conf.d

COPY ./html /usr/share/nginx/html