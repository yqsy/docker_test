# Version: 0.0.1

FROM ubuntu:14.04
MAINTAINER yqsy "yqsy021@126.com"
RUN apt-get update -y && apt-get install -y nginx
RUN echo 'Hello yqsy' \
    > /usr/share/nginx/html/index.html
EXPOSE 80
VOLUME ["/var/log"]
ENTRYPOINT ["nginx", "-g", "daemon off;"]