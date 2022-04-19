## Instalar dependencias do projeto
python -m venv venv

## pip install 
pip install django djangorestframework

## start django project
django-admin startproject nomeprojeto .

## criar app books
 django-admin startapp books

## inicializar app
python manage.py runserver

## fazer migração de tabelas
python manage.py migrate