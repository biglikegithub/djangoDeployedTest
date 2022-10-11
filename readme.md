docker-compose up --build -d


["gunicorn","--bind=0.0.0.0:8081","--worker-class=gthread","--workers=17","--threads=17","--log-level=INFO","mysite.wsgi:application"]

