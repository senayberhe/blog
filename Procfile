web: flask db upgrade; flask translate compile; gunicorn blog:app
worker: rq worker -u $REDIS_URL blog-tasks
