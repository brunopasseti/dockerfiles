
# Dockerfile and docker-compose for a Django project

## Dependency
> pipenv, django, docker-compose, docker


### Steps

If project is already created:

1. Copy files (*docker-compose.yml, Dockerfile & Pipfile*) to the root project folder.
2. Generate Pipfile.lock: `pipenv lock`.
3. Run: `docker-compose build django` to build the django service.
4. Create and start a container : `docker-compose up`

To create a new project:

1. Copy files (*docker-compose.yml, Dockerfile & Pipfile*) to the root project folder.
2. Generate Pipfile.lock: `pipenv lock`.
3. Run: `docker-compose run django django-admin startproject PROJECT_NAME .` to build the django service and create project.
4. Create and start a container : `docker-compose up`.
