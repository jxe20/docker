# Redis images Verison TEST 1.0

FROM ubuntu:14.04
MAINTAINER Galen turnbull "jxe20@qq.com"
ENV REFRESHED_AT 2015-04-14


RUN apt-get -y update 
RUN apt-get -y install redis-server redis-tools

EXPOSE 6379
EXPOSE 80
EXPOSE 22

ENTRYPOINT ["/usr/bin/redis-server"]

CMD []

