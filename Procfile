web: flask db upgrade; flask translate compile; gunicorn flask_app:app
worker: rq worker -u $REDIS_URL microblog-tasks