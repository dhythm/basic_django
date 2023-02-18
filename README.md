# basic_django

## Creating environment

```sh
mkdir backend
cd backend

poetry init
poetry install

poetry add Django
poetry run django-admin startproject basic_django .

poetry add --dev black pylint

poetry shell
poetry run python manage.py migrate
poetry run python manage.py runserver
```

## Getting started

```sh
cd frontend
npm install
npm run start
```

## Running App and Api in containers

```sh
docker-compose build

docker run -p 3000:3000 -d basic_django-web_front
```
