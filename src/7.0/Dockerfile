FROM jeromeerasmus/docker-alpine-php:7.0

MAINTAINER Jerome Erasmus

RUN wget https://getcomposer.org/download/1.1.1/composer.phar -O composer \
    && mv composer /usr/bin/composer \
    && chmod +x /usr/bin/composer 

CMD composer self-update

CMD apk --update && apk update

CMD apk add --no-cache jq

CMD ["/usr/bin/composer"]
