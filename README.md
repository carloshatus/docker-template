# docker-template

## Descrição

Template docker-compose, criando um container nginx 1.17 e um container php 7.1.9-fpm ligados através de um link e criando um container mysql 8 e postgres 11, com arquivo de configurações .env.

## Pré-requisitos
- Docker
- Docker-compose

## Utilização

```
$ docker-compose build
$ docker-compose up -d
```