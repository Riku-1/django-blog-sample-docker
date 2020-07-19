FROM python:3.9.0b4-alpine3.12

WORKDIR /code
RUN apk add gcc build-base linux-headers 
RUN pip install Django==3.0.8
RUN pip install uwsgi==2.0.19.1