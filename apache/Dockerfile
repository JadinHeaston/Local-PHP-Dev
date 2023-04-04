FROM httpd:${APACHE_VERSION:-}alpine${ALPINE_VERSION:-}

RUN apk update; \
    apk upgrade;

# Copy apache vhost file to proxy php requests to php-fpm container
COPY apache.conf /usr/local/apache2/conf/apache.conf
RUN echo "Include /usr/local/apache2/conf/apache.conf" \
    >> /usr/local/apache2/conf/httpd.conf