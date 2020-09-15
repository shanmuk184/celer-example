# Start Server
python manage.py runserver
# Start celery worker
celery -A celeryexample.celery -l info