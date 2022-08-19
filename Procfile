web: gunicorn price_compare.wsgi:application --log-file - --log-level debug
python manage.py collectstatic --noinput
manage.py migrate