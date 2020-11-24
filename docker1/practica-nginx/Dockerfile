FROM ubuntu:12.04
RUN apt-get update && apt-get install nginx -y
VOLUME /usr/share/nginx/www
WORKDIR /usr/share/nginx/www
ENV MI_WEB .
ADD ${MI_WEB} .
ENTRYPOINT ["/usr/sbin/nginx","-g","daemon off;"]
EXPOSE 80
