FROM python:3.8-slim-buster
ENV PYTHONENBUFFERED=1
WORKDIR /django-postgres
COPY requirements.txt requirements.txt
RUN pip install -r requirements.txt