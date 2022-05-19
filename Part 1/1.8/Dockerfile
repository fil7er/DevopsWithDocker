FROM ubuntu:20.04
WORKDIR /usr/src/app
COPY script.sh .
RUN apt update
RUN apt install -y curl
CMD ./script.sh