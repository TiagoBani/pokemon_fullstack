FROM node:alpine3.11

RUN apk add --update-cache git curl mysql-client \
    && rm -rf /var/cache/apk/*

ADD . /var/www/html
WORKDIR /var/www/html/pokemon