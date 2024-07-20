### Run the Flask App
```
flask run
```

## WIP
### Start Celery
```
celery -A app.celery_app worker --loglevel INFO --concurrency 1 --max-tasks-per-child=1
```

### Using Flower to inspect Celery
```
celery -A app.celery_app flower
```