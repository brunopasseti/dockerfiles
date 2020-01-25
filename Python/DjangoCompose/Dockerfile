FROM python:3.6-slim-stretch
ENV PYTHONUNBUFFERED 1
RUN mkdir /app
WORKDIR /app
COPY Pipfile /app/
COPY Pipfile.lock /app/
RUN pip install pipenv
RUN pipenv install --system --deploy --ignore-pipfile
COPY . /app/
