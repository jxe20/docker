# Verison TEST 1.0

FROM ubuntu:14.04
MAINTAINER Linux turnbull "jxe20@qq.com"
ENV REFRESHED_AT 2015-04-14

RUN apt-get update
RUN apt-get -y -q install nginx
RUN mkdir -p /vat/www/html 
#RUN mkdir -p /home/admin/www
#RUN mkdir -p /opt/picture/productPicture 
#RUN mkdir -p /opt/picture/spacePicture 
ADD ./nginx.conf /etc/nginx/nginx.conf
#ADD ./sk.ico /var/www/heml/sk.ico
#COPY ejs /home/admin/www/ejs

RUN echo -e "==========	install Nginx done,Yeah -_-!!" \
	>/var/www/html/index.html

EXPOSE 80


