FROM python:3.8-slim-buster

#This make any python output to be showed in the terminal including error logs
ENV PYTHONUNBUFFERED=1


WORKDIR /another-app
COPY requirements.txt requirements.txt
RUN pip install -r requirements.txt