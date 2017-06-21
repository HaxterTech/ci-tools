FROM docker:latest
MAINTAINER Atthaphong Limsupnark <atthaphong@haxter.tech>

RUN apk add --update alpine-sdk
RUN apk add --no-cache py-pip libffi
RUN pip install --upgrade pip
RUN pip install docker-compose