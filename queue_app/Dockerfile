FROM python:3.6

RUN apt-get update && apt-get -y install redis-tools

COPY ./ ./queue_app

WORKDIR ./queue_app


RUN pip install -r requirements.txt