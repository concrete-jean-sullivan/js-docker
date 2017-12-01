FROM ubuntu:16.04

MAINTAINER Jean Sullivan - Nginx - FrontEnd

RUN apt-get update -y
RUN apt-get install nginx -y
RUN apt-get install vim -y

EXPOSE 80

CMD ["nginx", "-g", "daemon off;"]