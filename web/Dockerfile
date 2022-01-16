FROM python:3.8-slim-buster

RUN mkdir -p /www

COPY requirements.txt requirements.txt
RUN pip3 install -r requirements.txt


COPY web_app.py /www/web_app.py
EXPOSE 8666
