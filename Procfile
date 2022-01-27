release: python manage.py makemigrations
release: python manage.py runserver

web: gunicorn wsgi:application
