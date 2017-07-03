Python TodoBackend Application

Getting Started.

Create Django Project
    pip install django==1.9
    django-admin startproject todobackend

Install Python Dependencies, Create and Activate virtualenv

1. First ensure pip is installed
    pip install pip --upgrade
2. Install the Virtualenv package globally
    pip install virtualenv
3. Create a new Virtual environment venv at the root of the project, note this is gitignored.
    virtualenv venv
4. Now Activate the virtual environment
    source venv/bin/activate


Install Required Dependencies for the project in a Virtual environment.

1. First ensure pip is installed
    pip install pip --upgrade
2. Install Django 1.9
    pip install django==1.9
3. Install Django Rest Framework 3.3
    pip install djangorestframework==3.3
4. Install Django Cors Headers
    pip install django-cors-headers==1.1

Add App todo, responsible for creating and managing todo items using startapp command from the management script.
    python manage.py startapp todo
