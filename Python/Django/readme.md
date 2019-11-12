
# Dockerfile for a Django project

## Dependency
> venv, django

## Building Image
docker image build .

## Running
docker run -v <full path to project folder>:/app -it -p PORT:8888 dd
