# laravel-docker

## 1.How to install?
```bash
git clone https://github.com/nattaponra/laravel-docker.git
```

## 2.Install Laravel with composer
```bash
# cd laravel-docker
# composer create-project --prefer-dist laravel/laravel blog
```

## 3. Rename and config database

* laravel-docker/app/.env.example to laravel-docker/app/.env
* setting database follow below example.
```
DB_CONNECTION=mysql
DB_HOST=mysql
DB_PORT=3306
DB_DATABASE=my_user
DB_USERNAME=my_user
DB_PASSWORD=my_password
```
## 3.Update library of laravel project.
```bash
# cd app
# composer update
```

## 4.Start docker with docker composer file.
```bash
# cd ..
# docker-compose up -d
```
## 5.Test access services.
* Website with http  <http:localhost>
* Website with https <https:localhost>
* phpmyadmin with https <http:localhost:5555>
