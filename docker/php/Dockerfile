FROM php:fpm
MAINTAINER Rodolphe Stoclin <srodolphe@gmail.com>
RUN apt-get update \
  && rm -rf /var/lib/apt/lists/* \
  && docker-php-ext-install mysqli
ADD ./30-custom.ini /usr/local/etc/php/conf.d/30-custom.ini
