FROM centos:6.10
MAINTAINER serge
RUN yum update -y
RUN yum install httpd -y
RUN service httpd start
EXPOSE 80
COPY ./index.html /var/www/html
CMD apachectl -D FOREGROUND
