FROM debian
RUN apt-get update
RUN apt-get -y install apache2
RUN echo “Bienvenidos” > /var/www/html/index.html
ENTRYPOINT ["/usr/sbin/apache2ctl","-D","FOREGROUND"]
EXPOSE 80
