# docker-template

## Descrição

Template docker-compose, criando um container nginx 1.17 e um container php 7.1.9-fpm ligados através de um link e criando um container mysql 8 e postgres 11, com arquivo de configurações .env.

- nginx:latest
- php:7.1.9-fpm
- mysql:latest
- postgres:latest

## Pré-requisitos
- Docker
- Docker-compose

## Utilização

Copiar o arquivo env-example para .env e editar os valores das variáveis.

```
$ docker-compose build
$ docker-compose up -d
```
