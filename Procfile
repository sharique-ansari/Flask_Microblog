web: flask db upgrade; flask translate compile; gunicorn flask_app:app
worker: rq worker  flask_app-tasks