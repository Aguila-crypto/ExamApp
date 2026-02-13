FROM httpd:2.4.
RUN docker -php-ext-install pdo pdo_msql_msqli

COPY ./frontend/*.html /var/www/html
COPY ./frontend/*.css /var/www/html
COPY ./frontend/*.js /var/www/html
COPY . /usr/local/apache2/htdocs




