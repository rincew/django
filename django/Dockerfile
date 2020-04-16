FROM python:3.8-buster
ENV PYTHONUNBUFFERED 1
RUN mkdir /code
RUN mkdir /sock
WORKDIR /code
COPY requirements.txt /code/
RUN pip install -r requirements.txt
COPY . /code/
