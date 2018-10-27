FROM eu.gcr.io/coffeedesk-cloud/php7:latest

WORKDIR /var/opt/app

COPY composer.* .
RUN composer install

COPY . .
