# basic_django

## Creating environment

```sh
poetry init
poetry install

poetry add Django
poetry run django-admin startproject basic_django .

poetry add --dev black pylint

poetry shell
poetry run python manage.py runserver
```
