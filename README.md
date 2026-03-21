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
HTTP Methods: GET (Fetch), POST (Create), PUT (Full Update), PATCH (Partial Update), DELETE (Remove)

JWT (JSON Web Token): Secures APIs using stateless token-based authentication.

Redis: In-memory storage used for caching to improve performance and reduce database load.

PostgreSQL: Database used to store persistent application data.

In short: Django builds the backend, DRF creates APIs, JWT secures them, Redis speeds them up

Day 22 Python Practice
This project demonstrates how to build a secure and efficient API using Django REST Framework.
