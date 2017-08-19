# Version: 0.0.1

FROM ubuntu:16.04
MAINTAINER yqsy "yqsy021@126.com"
RUN apt-get update -qq && apt-get install -y nginx
RUN echo 'Hello yqsy' \
    > /usr/share/nginx/html/index.html
EXPOSE 80