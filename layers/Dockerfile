#FROM ubuntu:16.04
FROM alpine
#alpine is a very small base image that enable us to save almost 50% of space
# to reduce layers, rather than this:
#RUN apt-get update
#RUN apt install curl -y
#RUN apt install ruby -y
#RUN apt install python -y
#RUN apt install build-essential -y
#RUN apt install apache2 -y

#we should do this:
#RUN apt-get update && \
#apt install curl -y && \
#apt install ruby -y && \
#apt install python -y && \
#apt install build-essential -y && \
#apt install apache2 -y

RUN apk update && \
apk add curl && \
apk add ruby && \
apk add python3 && \
apk add build-base && \
apk add apache2