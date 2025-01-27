from python:3.11-slim

env PYTHONUNBUFFERED 1

workdir /code

copy ./requirements.txt /code/

run pip install -r requirements.txt

copy . /code/