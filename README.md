Page
===
Abstract:Se realizo un proyecto con Django, se agrego una aplicación 'pages', luego se realizo una configuración básica con Docker.

## Information
- Title:  `Page`
- Authors:  `jocnn`

## Install & Dependence
- python==3.10.5
- asgiref==3.5.2
- black==22.6.0
- click==8.1.3
- Django==4.0.6
- mypy-extensions==0.4.3
- pathspec==0.9.0
- platformdirs==2.5.2
- sqlparse==0.4.2
- tomli==2.0.1

## Use
- for docker
```
  > docker build .
  > docker-compose up
  > docker-compose down
 ```
## Directory Hierarchy
```
|—— .dockerignore
|—— .gitignore
|—— .venv
|—— Dockerfile
|—— db.sqlite3
|—— django_project
|    |—— __init__.py
|    |—— __pycache__
|        |—— __init__.cpython-310.pyc
|        |—— settings.cpython-310.pyc
|        |—— urls.cpython-310.pyc
|        |—— wsgi.cpython-310.pyc
|    |—— asgi.py
|    |—— settings.py
|    |—— urls.py
|    |—— wsgi.py
|—— docker-compose.yml
|—— manage.py
|—— pages
|    |—— __init__.py
|    |—— __pycache__
|        |—— __init__.cpython-310.pyc
|        |—— admin.cpython-310.pyc
|        |—— apps.cpython-310.pyc
|        |—— models.cpython-310.pyc
|        |—— urls.cpython-310.pyc
|        |—— views.cpython-310.pyc
|    |—— admin.py
|    |—— apps.py
|    |—— migrations
|        |—— __init__.py
|        |—— __pycache__
|            |—— __init__.cpython-310.pyc
|    |—— models.py
|    |—— tests.py
|    |—— urls.py
|    |—— views.py
|—— requirements.txt
```
