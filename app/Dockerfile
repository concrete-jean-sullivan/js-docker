FROM ubuntu:16.04

MAINTAINER 'Jean Sullivan - Apache2 + PHP 7'

RUN apt update
RUN apt install snmpd -y
RUN apt install apache2 -y
RUN apt-get install php libapache2-mod-php php-mcrypt php-mysql -y
RUN apt-get install vim -y

EXPOSE 8080

COPY ./index.php /var/www/html/

CMD ["/usr/sbin/apache2ctl", "-D", "FOREGROUND"]
