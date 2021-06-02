web: gunicorn heryproj.wsgi:application --log-file -
python manage.py collectstatic
release: python manage.py migrate
