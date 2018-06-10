# docker-python
Docker image for [DJANGO](https://www.djangoproject.com/).

## Supported branches and respective Dockerfile links


## What is DJANGO ?


## Getting image
```sh
sudo docker pull lecaoquochung/docker-django
```

## Basic usage

```sh
sudo docker run -v /path/to/your/app:/var/www/html -d lehungio/php-fpm
```

## Running your script

### Running image
Run the PHP-FPM image, mounting a directory from your host.

```sh

```

or using [Docker Compose](https://docs.docker.com/compose/):

### Running as server

```sh

```

### Logging
```sh
sudo docker logs dockerdjango
```
or using [Docker Compose](https://docs.docker.com/compose/) :
```sh
sudo docker-compose logs dockerdjango
```

## Installed extensions
 - Django
 - psycopg2
 - djangorestframework
 - pygments
 - httpie
