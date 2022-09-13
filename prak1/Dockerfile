FROM php:7.4-apache
RUN docker-php-ext-install mysqli
WORKDIR /usr/src/myapp
COPY . .
EXPOSE 80
CMD [ "php","-S", "0.0.0.0:80", "./index.php" ]