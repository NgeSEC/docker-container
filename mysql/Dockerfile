FROM ubuntu:16.04

RUN apt-get update && \
    apt-get -y install mysql-server-5.7 mysql-client-5.7 

EXPOSE 3306 

CMD ["/usr/bin/mysqld_safe"]