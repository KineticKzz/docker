FROM debian
RUN apt-get update && apt-get install apache2 -y
VOLUME /var/www/html
WORKDIR /var/www/html
ADD web1 .
ENTRYPOINT ["/usr/sbin/apache2ctl", "-D" ,"FOREGROUND"]
EXPOSE 80
