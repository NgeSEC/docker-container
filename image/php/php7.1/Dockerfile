FROM ubuntu:16.04

RUN apt-get update
RUN apt-get install -y software-properties-common python-software-properties
RUN add-apt-repository -y ppa:ondrej/php
RUN apt-get update 
RUN apt-get install -y php7.1 
        php7.1-mysql \
        php7.1-opcache \
        php7.1-common \
        php7.1-mbstring \
        php7.1-mcrypt \
        php7.1-soap \
        php7.1-cli \
        php7.1-intl \
        php7.1-json \
        php7.1-xsl \
        php7.1-imap \
        php7.1-ldap \
        php7.1-curl \
        php7.1-gd \
        php7.1-dev \
        php7.1-fpm \
        php7.1-bcmath \
        php7.1-imagick \
        php7.1-zip \
        php7.1-zmq \
        php7.1-apcu \

EXPOSE 9000

CMD ["php7-fpm", "--nodaemonize"]
