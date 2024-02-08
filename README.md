# django beginner rest framework
 
py -m venv venv

pip install django
pip install djangorestframework

pip freeze

django-admin startproject djangoapi

python manage.py migrate
python manage.py makemigrations
python manage.py makemigrations courses

python manage.py runserver

python manage.py createsuperuser

python manage.py startapp courses