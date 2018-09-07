FROM nginx:stable-alpine

RUN rm -rf /etc/nginx/conf.d/*

COPY ./config/proxy.conf /etc/nginx/conf.d
COPY ./config/.htpasswd /etc/nginx/
COPY ./keys/cert.pem /etc/nginx/
COPY ./keys/key.pem /etc/nginx/