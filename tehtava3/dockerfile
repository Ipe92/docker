FROM ubuntu:latest

WORKDIR /mydir
RUN touch hello.txt
COPY local.txt .
RUN apt-get update && apt-get install -y wget
RUN wget http://example.com/index.html