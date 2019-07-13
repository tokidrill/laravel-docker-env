# How to buildup Laravel Project
```
$ git clone THIS_REPOSITORY
$ sed -e "s/Any/YOUR_PROJECT_NAME/g" .env

$ docker-compose up -d --build

$ docker-compose exec app composer create-project --prefer-dist "laravel/laravel=5.8.*" .

# access to https://localhost:3500 !
```
