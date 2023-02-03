# Dockerfile um die Funtionalität des EXPOSE Command aufzuzeigen
FROM ubuntu:16.04


RUN apt-get update && apt-get -y upgrade && \
    apt-get install -y nginx

EXPOSE 80

CMD ["nginx", "-g", "daemon off;"]