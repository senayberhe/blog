web: flask db upgrade; flask translate compile; gunicorn senay-flask-blog.:app
worker: rq worker senay-flask-blog.-tasks
