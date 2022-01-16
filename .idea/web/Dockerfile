FROM python:3.8-slim-buster

RUN mkdir -p /www

COPY requirements.txt requirements.txt
RUN pip3 install -r requirements.txt


COPY app.py /www/app.py
EXPOSE 8666
