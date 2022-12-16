# Comparte Raid (CRide)

![](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white
) ![](https://img.shields.io/badge/django%20rest-ff1709?style=for-the-badge&logo=django&logoColor=white) ![](https://img.shields.io/badge/Docker-2CA5E0?style=for-the-badge&logo=docker&logoColor=white) ![](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white) ![](https://img.shields.io/badge/redis-%23DD0031.svg?&style=for-the-badge&logo=redis&logoColor=white)


CRide is a carpooling car project by [Pablo Trinidad](https://github.com/pablotrinidad) inside advanced Django REST Framework course at Platzi where the main goal was to learn how to professionally build a REST API. 

- Github page: https://github.com/pablotrinidad/cride-platzi
- Platzi Course: https://platzi.com/cursos/django-avanzado/



## Features

-   For Django 3.2.16
-   Works with Python 3.6-alpine
-   Docker Compose
-   Celery to asynchronous processes 
-   Flower - Celery monitoring tool
-   Caddy - HTTP server
-   Redis as cache database
-   [12-Factor](http://12factor.net/) based settings via [django-environ](https://github.com/joke2k/django-environ)
-   Optimized development and production settings
-   Send emails via [Anymail](https://github.com/anymail/django-anymail) (using [Mailgun](http://www.mailgun.com/) by default or Amazon SES if AWS is selected cloud provider, but switchable)
-   Media storage using Amazon S3, Google Cloud Storage or Azure Storage
-   Run tests with unittest or pytest
-   Customizable PostgreSQL version

## Development

To start working on this project I highly recommend you to check
[pydanny's](https://github.com/pydanny) [Django Cookiecutter](https://github.com/pydanny/cookiecutter-django) [documentation](https://cookiecutter-django.readthedocs.io/en/latest/developing-locally-docker.html) on how to get this project up and running locally.
If you don't want to do so, just run:

```bash
docker-compose -f local.yml build
docker-compose -f local.yml up
```