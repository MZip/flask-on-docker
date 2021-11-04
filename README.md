# flask-on-docker

Following this great example from https://testdriven.io/blog/dockerizing-flask-with-postgres-gunicorn-and-nginx/ until Gunicorn setup.

## Setup

docker-compose build.

docker-compose up -d

Service will be available on: http://localhost:5000/

docker exec flask-on-docker_web_1 python manage.py create_db
docker exec flask-on-docker_web_1 python manage.py seed_db
