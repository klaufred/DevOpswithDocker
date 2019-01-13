FROM ubuntu:16.04

COPY . backend-example-docker
WORKDIR backend-example-docker

RUN apt-get update && apt-get install -y curl

RUN curl -sL https://deb.nodesource.com/setup_10.x | bash
RUN apt-get install -y nodejs

EXPOSE 8000

RUN npm install

CMD npm start