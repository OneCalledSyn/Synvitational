web: flask db upgrade; flask translate compile; gunicorn pythonwebsite:app
worker: rq worker -u $REDIS_URL synvitational-tasks
