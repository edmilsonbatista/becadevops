FROM nginx:1.13.12

RUN apt-get update; apt-get install telnet -y

ADD index.html /usr/share/nginx/html

EXPOSE 80