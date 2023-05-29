web: gunicorn pythonpro_dz_13.wsgi:application --log-file - --log-level debug
python manage.py collectstatic --noinput
manage.py migrate
