FROM ubuntu
RUN apt-get update
RUN apt-get install -y apache2
RUN apt-get install -y apache2-utils
RUN apt-get clean
EXPOSE 80
COPY index.html /var/www/html/
WORKDIR /var/www/html
CMD apachectl -D FOREGROUND
