####################################
# PHPDocker.io PHP 7.0 / FPM image #
####################################

FROM phpdockerio/php7-fpm

# Install pgsql
RUN apt-get update \
    && apt-get -y --no-install-recommends install php7.0-pgsql \
    && apt-get clean \
    && rm -rf /var/lib/apt/lists/* /tmp/* /var/tmp/* /usr/share/doc/*


CMD /usr/bin/php-fpm

# Open up fcgi port
EXPOSE 9000
