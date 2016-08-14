FROM php:fpm

ADD php.ini /usr/local/etc/php/php.ini

ADD composer.phar /usr/local/bin/composer
RUN chmod 755 /usr/local/bin/composer

RUN apt-get update
RUN apt-get upgrade
RUN apt-get install git
RUN apt-get install zip unzip

RUN ln -sf /usr/share/zoneinfo/Asia/Shanghai  /etc/localtime

VOLUME ["/var/projects/data/html"]