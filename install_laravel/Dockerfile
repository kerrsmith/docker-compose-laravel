FROM composer

WORKDIR /temp_install

RUN composer create-project --prefer-dist laravel/laravel . && \
    chmod -R 777 storage/* && \
    chmod -R 777 bootstrap/cache/*
