#Django project

create virtual environment

django-admin startproject store_project

3.cd store project

4.python manage.py startapp core

pip install djangorestframework
6.pip install psycopg2-binary

add core and rest_framework in installed apps(settings.py)

add database in settings.py like host, name, passwpord

now code in models.ov

then migrate 2 commands

11.seralizer

12.views.py

13.urls.py

runserver

Day 21 Python Practice
Django: Backend framework used to build web applications.

Django REST Framework: Used to build RESTful APIs that return JSON and handle CRUD operations.

API Flow: Client → Django → urls.py → views.py → serializers.py → models.py → Database → JSON Response
