worker: celery -A gavel:celery worker
web: python initialize.py && gunicorn gavel:app -w 3 -t 3
