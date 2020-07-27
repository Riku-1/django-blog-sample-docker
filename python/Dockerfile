FROM python:3.8.5-alpine3.12

WORKDIR /code
RUN apk add gcc build-base linux-headers mariadb-connector-c-dev
RUN pip install Django==3.0.8
RUN pip install djangorestframework==3.11.0
RUN pip install uwsgi==2.0.19.1
RUN pip install mysqlclient==2.0.1
RUN pip install django-environ==0.4.5