FROM python:3.12
ENV PYTHONUNBUFFERED 1
RUN mkdir /backend
WORKDIR /backend
ADD requirements.txt /backend/
RUN pip3 install -r requirements.txt
ADD . /backend/