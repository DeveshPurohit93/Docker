FROM ubuntu

ENV DEBIAN_FRONTEND=noninteractive

RUN apt-get -y  update

RUN apt-get -y install apache2

EXPOSE 80

CMD ["/etc/init.d/apache2" ,"start","-D","FOREGROUND"]
CMD ["bash"]
