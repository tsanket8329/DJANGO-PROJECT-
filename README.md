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
It includes pagination to handle large datasets, filtering and ordering to fetch required records, and JWT authentication to secure API access. Additionally, it introduces Redis for fast in-memory data handling and performance optimization.

Day 23 Python Practice
#Javascript

<script> function sayHello() { alert("Hello! JS is working"); } sayHello(); </script>
User action(click/type) -> Browser(Edge/Chrome)-> Javascript Engine-> Result on screen HTML - Show content CSS = Decorates content Javascript - Control content Backend:- Output statement


Console show: Step 1: JS startedd (CTRL+ SHIFT+J)
Pop up alert
Page shows - document.write(Writing inside webpage) JS 1.var -old box(weak) 2 let-new box(good) 3.const-Locked box(best) Keyword - var let const Change value - yes yes no Redclare - yes no no Use = avoid use best var name= 'Ram'; var name = 'Shyam'; console.log(name); // Output: Shyam let name= 'Ram'; let name = 'Shyam'; console.log(name);#output - error let name= 'Ram'; name = 'Shyam'; console.log(name); const name= 'Ram'; const name = 'Shyam'; console.log(name);#output - error const name= 'Ram'; console.log(name);#output -Ram #DATATYPES IN JS
