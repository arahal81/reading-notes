# Reading 29

## Django Custom User Model

- Django ships with a built-in User model for authentication, however the official Django documentation highly recommends using a custom user model for new projects. The reason is if you want to make any changes to the User model down the road--for example adding a date of birth field--using a custom user model from the beginning makes this quite easy. But if you do not, updating the default User model in an existing Django project is very, very challenging.

## Setup

To start, create a new Django project from the command line. We need to do several things:

    - create and navigate into a dedicated directory called accounts for our code
    - install Django
    - make a new Django project called config
    - make a new app accounts
    - start the local web server
    - Here are the commands to run:

`$ mkdir accounts && cd accounts`
`$ pipenv install django~=3.1.0`
`$ pipenv shell`
`$ django-admin.py startproject config .`
`$ python manage.py startapp accounts`
`$ python manage.py runserver`

## DjangoX

    - Django 3.1 & Python 3.8
    - Install via Pip, Pipenv, or Docker
    - User log in/out, sign up, password reset via django-allauth
    - Static files configured with Whitenoise
    - Styling with Bootstrap v4
    - Debugging with django-debug-toolbar
    - DRY forms with django-crispy-forms
