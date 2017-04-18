FROM nginx:stable-alpine
MAINTAINER Allen Zou <zyl_work@163.com>

RUN apt update && apt install -y curl

RUN echo "You must build & install the pages first"

RUN rm -rf /etc/nginx/conf.d
COPY ./gateway.conf /etc/nginx/conf.d/

EXPOSE 80