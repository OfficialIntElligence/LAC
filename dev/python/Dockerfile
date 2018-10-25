FROM python:3.7.1

ENV PYTHONUNBUFFERED 1

RUN mkdir /lac
WORKDIR /lac

ADD ./requirements.txt /lac/
RUN pip install -r requirements.txt

ADD . /lac/
