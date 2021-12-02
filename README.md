# コンテナ起動

- cd laravel_project

- docker-compose build php

- docker-compose build nginx

- docker-compose build front

- docker-compose up -d

# 初期セットアップ
## Laravel

- docker-compose exec php  composer install

- docker-compose exec php composer dump-autoload

- docker-compose exec php mv .env.example .env

- docker-compose exec php php artisan key:generate


## NUXT

- cd src/nuxt

- npm install



# コンテナ起動

- docker-compose up -d

# ローカルアクセス

- http://localhost:8888 (nuxt)

- http://localhost:8080 (laravel)


