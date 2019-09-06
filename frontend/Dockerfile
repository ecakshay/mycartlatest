#This is dockerfile for MyCart microservice frontend layer
FROM centos:7
MAINTAINER ec.akshay@gmail.com
RUN yum -y update
RUN yum -y install httpd
ADD code /var/www/html
EXPOSE 80
ENV BACKENDLB=test
CMD ["apachectl", "-D", "FOREGROUND"]