# Django projects to study the framework

## Django commands

### Instalation required

* install pipenv: python -m pip install pipenv
* install Django: python -m pipenv install Django

### Project commands

* create a project: django-admin startproject NAME
* run the server: python manage.py runserver
* create a app inside a project: python manage.py startapp APP_NAME

### Database commands

* migrate the database: python manage.py migrate
* prepare a migration database for a app: python manage.py makemigrations APP_NAME
* see the SQL operations necessaries to the migration: python manage.py sqlmigrate APP_NAME MIGRATION_NUMBER
* check any problem without make migration: python manage.py check
* open a shell to interact with the project models and more: python manage.py shell

### Django admin commands

* create a new user for django admin: python manage.py createsuperuser

### Tests commands

* run the application tests: python manage.py test APP_NAME

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

### Templates

* https://docs.djangoproject.com/en/2.1/topics/templates/

### Request response

* https://docs.djangoproject.com/en/2.1/ref/request-response/

### Avoiding race conditions

* https://docs.djangoproject.com/en/2.1/ref/models/expressions/#avoiding-race-conditions-using-f

### Class based views (generic display/views)

* https://docs.djangoproject.com/en/2.1/topics/class-based-views/
* https://docs.djangoproject.com/en/2.1/ref/class-based-views/generic-display/#django.views.generic.list.ListView
* https://docs.djangoproject.com/en/2.1/ref/class-based-views/generic-display/#django.views.generic.detail.DetailView

### Tests

* https://docs.djangoproject.com/en/2.1/topics/testing/
* https://docs.djangoproject.com/en/2.1/topics/testing/tools/#django.test.TestCase
* https://docs.djangoproject.com/en/2.1/topics/testing/tools/#django.test.LiveServerTestCase
* https://docs.djangoproject.com/en/2.1/topics/testing/advanced/#topics-testing-code-coverage