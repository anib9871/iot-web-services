release: python manage.py migrate && python manage.py collectstatic --noinput
web: gunicorn iot_project.wsgi