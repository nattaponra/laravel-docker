# laravel-docker

## 1.How to install?
```bash
git clone https://github.com/nattaponra/laravel-docker.git
```
## 2.Install Laravel with composer
```bash
composer create-project --prefer-dist laravel/laravel blog
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
