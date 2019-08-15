FROM ubuntu:latest
MAINTAINER SARATH KUNALA
RUN apt-get update
RUN apt-get install -y python python-pip wget
RUN pip install Flask
ADD helloworld.py /home/helloworld.py
WORKDIR /home
