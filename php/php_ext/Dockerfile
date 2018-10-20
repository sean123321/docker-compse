FROM php:7.2-fpm
RUN apt-get update \ 
&& docker-php-ext-install mbstring opcache pdo pdo_mysql mysqli
#ENV PHPREDIS_VERSION 3.1.3
#RUN curl -L -o /tmp/redis.tar.gz https://github.com/phpredis/phpredis/archive/$PHPREDIS_VERSION.tar.gz \
#&& tar xfz /tmp/redis.tar.gz \
#&& rm -r /tmp/redis.tar.gz \
#&& mkdir -p /usr/src/php/ext \
#&& mv phpredis-$PHPREDIS_VERSION /usr/src/php/ext/redis \
#&& docker-php-ext-install redis \
#&& rm -rf /usr/src/php #如果这段不加构建的镜像将大100M
