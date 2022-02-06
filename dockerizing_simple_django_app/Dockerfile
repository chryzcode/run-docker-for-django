#choose a lightweight linux operating system with python installed
FROM python:3.8-slim-buster

#created a working directory in the docker image environment
WORKDIR /app

#copy all the requirements for the project and create a new requirements.txt file in the docker image environment 
COPY requirements.txt requirements.txt

#install the requirements
RUN pip install -r requirements.txt

#copy all necessary files in the project to the newly docker image environment
COPY . .

#runserver and make the server avaiable externally visible from thr docker environment
CMD [ "python", "manage.py", "runserver", "0.0.0.0:8000" ]