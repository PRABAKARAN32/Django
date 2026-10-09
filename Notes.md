# This is Key Notes for Django

Django followes the MVT - Model View Template Software Partern

### Virtual Enveronment

**Create a virtual Environment** - `python3 -m venv <environment-name>`

**Enter in the Environment** - `source <environment-name>/bin/activate`

**init.py** if the file is present it is a project.

**default port** -> 8000

### What is manage.py?

        it is used to do some "Administrative Task."

### What is asgi.py and wsgi.py?

        It is a HTTP server in production.

### What is settings.py?

        This is for Default.py
        1) BASE_DIR
        2) SECRET_KEY
        3) DEBUG
        4) ALLOWED_HOSTS
        5) INSTALLED_APPS
        6) MIDDLEWARE
        7) ROOT_URLCONF
        8) TEMPLATES

## Commands

    1) Create the Django Server -> `django-admin startproject <project-name> .`

    2) To Run the Server -> `python manage.py runserver`

    3) To Create a app -> `python manage.py startapp <app-name>`
