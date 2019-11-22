# django_heroku

django project Heroku deploy instructions

## Installing Django

### Create virtual environment and install Django

> pipenv install django==2.2.*

### Create django project named <site_project>

> django-admin startproject site_project .

### Create a new app <newsite>

> python manage.py startapp newsite

## Setting up django project

### Open siteproject/setting.py

1. Add new app:
    > "