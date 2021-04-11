# Publicando Imagem Laravel - Part 2

This repository contains the code that solves the challenge "Publicando Imagem Laravel - Parte 2" from DevOps course of Code Education.

In this second part of the challenge, it is suppose to finish the challenge by creating a `.env` file and running the below commands inside the container:

```bash
composer install
```

```bash
php artisan key:generate
```

```bash
php artisan migrate
```

After that, the Laravel application is up and can be seen.

**Note 1**: The code here was based on this other [repository](https://github.com/pedrinhonasc/laravel_image_1) that constains the first part of the challenge.
**Note 2**: A image based on the app container can be pulled from [here](https://hub.docker.com/r/jpedronascimentofilho/laravel).


## Goal

The goal of the challenge is to learn `docker` and `docker-compose` in practice.

## Usage

To run this code, in a terminal, execute:

```bash
docker-compose up -d
```

Then, in a browser enter:

```bash
localhost:8000
```

To stop the containers and remove them, execute:
```bash
docker-compose down
```