FROM jeromeerasmus/docker-alpine-php:5.6

MAINTAINER Jerome Erasmus

RUN wget https://getcomposer.org/download/1.1.1/composer.phar -O composer \
    && mv composer /usr/bin/composer \
    && chmod +x /usr/bin/composer \
    && chmod +x /usr/bin/composer 

CMD composer self-update

CMD ["/usr/bin/composer"]
