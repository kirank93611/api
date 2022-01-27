release: python manage.py makemigrations
release: python manage.py migrate
release: python manage.py runserver

web: gunicorn djackets_django.wsgi
