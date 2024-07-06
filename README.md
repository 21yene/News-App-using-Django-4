# News-App-using-Django-4

    python manage.py makemigrations articles

    python manage.py migrate

install Gunicorn
create a requirements.txt file
update ALLOWED_HOSTS in django_project/settings.py
create a Procfile file
create a runtime.txt file
configure static files, install whitenoise, and run
collectstatic
create and update a .gitignore file
create a new Heroku project, push the code to it, and
start a dyno web process

    python -m pip install whitenoise==5.3.0
    python -m pip freeze > requirements.txt

Procfile
web: gunicorn django_project.wsgi --log-file -
runtime.txt
python-3.10.2