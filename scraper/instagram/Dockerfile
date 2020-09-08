FROM python:3-slim

RUN pip install instaloader && mkdir /data

USER 1000:1000

WORKDIR /data

ENTRYPOINT instaloader
