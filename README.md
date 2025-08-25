# STUDY-DigitalOcean-How_To_Build_a_To-Do_application_Using_Django_and_React
Tutorial Reference: https://www.digitalocean.com/community/tutorials/build-a-to-do-application-using-django-and-react
Tutorial GitHub Project: https://github.com/do-community/django-todo-react

## Initial Project Setup
```
?> mkdir django-todo-react
?> cd django-todo-react
?> pip install pipenv
?> pipenv shell
?> pipenv install django
?> django-admin startproject backend
?> cd backend
?> python manage.py startapp todo 0.0.0.0:8000
?> python manage.py migrate
?> python manage.py startapp todo 0.0.0.0:8000


?> python manage.py makemigrations todo
?> python manage.py migrate todo

?> python manage.py createsuperuser
?> python manage.py startapp todo 0.0.0.0:8000
```

## Setting Up the APIs
```
?> pipenv install djangorestframework django-cors-headers
?> python manage.py startapp todo 0.0.0.0:8000
```
## Updating Node 
## Setting Up the Frontend
```
?> npx create-react-app frontend
