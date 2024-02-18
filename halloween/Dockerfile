from httpd:latest

ARG APP_USER=jane-doe
ENV APP_MANAGER=john_doe


RUN apt update -y
WORKDIR /usr/local/apache2/htdocs/

VOLUME /Saves
COPY . /Saves
COPY . .

EXPOSE 80-10000
