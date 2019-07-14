# How To Buildup Laravel Project
```
$ https://github.com/tokidrill/laravel-docker-env.git
$ sed -e "s/Any/YOUR_PROJECT_NAME/g" .env

$ docker-compose up -d --build

$ docker-compose exec app composer create-project --prefer-dist "laravel/laravel=5.8.*" .

# open https://localhost:3500 !
```
