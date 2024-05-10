FROM nginx:latest

RUN apt-get update && apt-get install -y \
    curl \
    vim

COPY ./index.html /usr/share/nginx/html/

EXPOSE 80
