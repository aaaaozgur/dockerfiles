FROM ubuntu

RUN apt-get update
RUN apt-get upgrade -y
RUN apt-get install -y nodejs
RUN node --version
RUN apt-get install -y npm
RUN npm --version
RUN npm install -g --unsafe-perm node-red@1.0.2

VOLUME ["/data"]
EXPOSE 1880

CMD node-red