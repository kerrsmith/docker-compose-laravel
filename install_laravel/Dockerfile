FROM composer

WORKDIR /temp_install

RUN composer create-project --prefer-dist laravel/laravel .
RUN chmod -R 777 storage/*
RUN chmod -R 777 bootstrap/cache/*
