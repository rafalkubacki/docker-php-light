# Docker PHP Light

Lightweight Docker setup for running Nginx & PHP-FPM.
___

## Install

Clone the repository:

```sh
git clone https://github.com/rafalkubacki/docker-php-light.git
```

Go to the directory:

```sh
cd docker-php-light
```

Start the application:

```sh
docker-compose up -d
```

## Run

Open your browser at:

[http://localhost:8000](http://localhost:8000/)

<font size="2">* Please note that anything inside the ``web/public`` directory will be publicly accessible.</font>

## Delete

```sh
docker-compose down -v
```
