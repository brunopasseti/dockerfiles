
# Dockerfile for a Django project

## Dependency
> venv, django

## Building Image
docker image build .

## Running
docker run -v full_path_to_project_folder:/app -it -p PORT:8888 dd
