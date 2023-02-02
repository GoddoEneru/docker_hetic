FROM ubuntu:latest

RUN apt-get update && apt-get upgrade && apt-get install -y python3 python3-pip

EXPOSE 8000

CMD python3 -m http.server 8000
