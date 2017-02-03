FROM python:3.5-alpine
MAINTAINER xuqingdi <zhubenshuli@gmail.com>

RUN apk update \
    && apk add libxml2-dev libxslt-dev libffi-dev gcc musl-dev libgcc openssl-dev libjpeg-turbo-dev \
    && pip install scrapy

WORKDIR /code
