FROM ubuntu:22.04

WORKDIR /usr/scripts

COPY script.sh .

RUN apt-get update && apt-get install curl -y

CMD ./script.sh 
