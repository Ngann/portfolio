pip3 install --upgrade pip
pip3 install --upgrade django
python -V

create project:
django-admin startproject portfolio

create app: app name should be plural
django-admin startapp jobs

run server:
python3 manage.py runserver