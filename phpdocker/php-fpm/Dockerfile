FROM phpdockerio/php:8.3-fpm
WORKDIR "/application"

RUN apt-get update \
    && apt-get -y --no-install-recommends install \
        php8.3-bcmath \
        php8.3-bz2 \
        php8.3-cgi \
        php8.3-enchant \
        php8.3-gd \
        php8.3-gmp \
        php8.3-gnupg \
        php8.3-grpc \
        php8.3-http \
        php8.3-mcrypt \
        php8.3-memcache \
        php8.3-memcached \
        php8.3-mysql \
        php8.3-oauth \
        php8.3-odbc \
        php8.3-pcov \
        php8.3-phpdbg \
        php8.3-protobuf \
        php8.3-pspell \
        php8.3-psr \
        php8.3-ssh2 \
        php8.3-xdebug \
    && apt-get clean \
    && rm -rf /var/lib/apt/lists/* /tmp/* /var/tmp/* /usr/share/doc/*
