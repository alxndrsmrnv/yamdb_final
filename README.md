# Yandex.Practicum Project - api_yamdb


This API can help to store films by genre, categories, leave comments, make reviews.

## Tech:
- Python
- Django
- PostgreSQL
- Docker


## Installation

api_yamdb requires Python 3.7 and Docker to run. Docker install guide https://docs.docker.com/engine/install/ubuntu/

You need to create .env file. Example below.
```sh
DB_ENGINE=django.db.backends.postgresql 
DB_NAME=postgres
POSTGRES_USER=admin
POSTGRES_PASSWORD=admin      
DB_HOST=db
DB_PORT=5432
HOST=0:8000
```

## Docker

To build containers run: `sudo docker-compose build`
Then makemigrations: `docker-compose exec web python manage.py migrate`

## Author
Alexander Smirnov https://github.com/alxndrsmrnv

![example workflow](https://github.com/alxndrsmrnv/yamdb_final/actions/workflows/yamdb_workflow.yaml/badge.svg)

Project http://130.193.51.225/
