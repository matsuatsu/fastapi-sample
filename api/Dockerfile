FROM python:3.6.10-buster

WORKDIR /api

COPY ./pyproject.toml /api
COPY ./poetry.lock /api

RUN pip install poetry && \
    poetry install