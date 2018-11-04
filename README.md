# Django projects to study the framework

## Main commands

### Instalation required

* install pipenv: py -m pip install pipenv
* install Django: py -m pipenv install Django

### Project commands

* create a project: django-admin startproject NAME
* run the server: py manage.py runserver
* create a app inside a project: py manage.py startapp APP_NAME

### Database commands

* migrate the database: py manage.py migrate
* prepare a migration database for a app: py manage.py makemigrations APP_NAME
* see the SQL operations necessaries to the migration: py manage.py sqlmigrate APP_NAME MIGRATION_NUMBER
* check any problem without make migration: py manage.py check
* open a shell to interact with the project models and more: py manage.py shell

## Django admin commands

* create a new user for django admin: py manage.py createsuperuser

## Resources

### Django admin

* https://docs.djangoproject.com/en/2.1/ref/django-admin/

### Time zones

* https://docs.djangoproject.com/en/2.1/topics/i18n/timezones/
* https://stackoverflow.com/questions/29311354/how-to-set-the-timezone-in-django
* https://docs.djangoproject.com/en/2.1/ref/settings/#std:setting-TIME_ZONE

### Database, model and ORM

* https://docs.djangoproject.com/en/2.1/ref/models/relations/
* https://docs.djangoproject.com/en/2.1/topics/db/queries/#field-lookups-intro
