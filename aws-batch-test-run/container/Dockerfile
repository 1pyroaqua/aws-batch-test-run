ARG REGION=us-east-1

FROM python:3.7-alpine

WORKDIR /tmp/code

COPY code /tmp/code

RUN chmod +x *
RUN pip3 --no-cache-dir install -r requirements.txt
