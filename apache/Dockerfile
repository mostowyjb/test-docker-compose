FROM httpd:latest

# Copy apache vhost file to proxy php requests to php-fpm container
COPY apache.conf /usr/local/apache2/conf/local.apache.conf
RUN echo "Include /usr/local/apache2/conf/local.apache.conf" \
    >> /usr/local/apache2/conf/httpd.conf