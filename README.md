# docker-template

## Descrição

Template docker-compose, criando um container nginx e um container php fpm ligados através de um link, criando um container mysql e um postgres, com arquivo de configurações .env.

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
