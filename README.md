## django_start - Django framework reference repository

The purpose of this repository is twofold:

 - A basic demonstration of Django functionality.
 - A reference template of "best practices" & standards to be employed in
    all of my other Django projects.

### Installation
 - `git clone https://github.com/kevinbowen777/django_start.git`
 - `cd django_start`
 - Local installation
     - `poetry install`
     - `python manage.py migrate`
     - `python manage.py createsuperuser`
     - `python manage.py runserver`
 - Docker installation
     - `docker-compose up --build`
     - `docker-compose python manage.py migrate`
     - `docker-compose python manage.py createsuperuser`
 - Open browser to http://127.0.0.1:8000`

---
## Features
 - User registration with email verification & social(GitHub) login

### Live Demo on Heroku:
 - [django-start](https://kbowen-django-start.herokuapp.com/)

---
[![License](https://img.shields.io/badge/license-MIT-green)](https://github.com/kevinbowen777/django_start/blob/master/LICENSE)
---
### Reporting Bugs

   Visit the [Issues page](https://github.com/kevinbowen777/django_start/issues)
      to view currently open bug reports or open a new issue.
