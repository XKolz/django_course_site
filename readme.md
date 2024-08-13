Django is a python web development framework
built for python  3 or higher

batteries

build for production-ready websites, real life products.

## why do we use django?
user--------Request----------Server
user--------Response---------Server(Database)(business logic)

Parsing requests, sending responses, querying the db, working with data, sessions, file upload, etc.

## Course prequistes
Basic python knowlegde is required
Basic web dev knowledge is required


To start django
1. first install django
python -m pip install Django

2. then create your project folder with this,
django-admin startproject django_course_site 

3. this creates the another app folder
 python3 manage.py startapp meetups

4. run a new migrations to edit the db, after you have editted the model
create it
python manage.py makemigrations
run it
python manage.py makemigrate



3. run the project
python3 
python manage.py runserver