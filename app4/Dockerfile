FROM  fedora
MAINTAINER krishan kant 
RUN yum install httpd -y 
LABEL install=webserver
WORKDIR /var/www/html/
ADD code/ ./
EXPOSE 80
ENTRYPOINT httpd -DFOREGROUND
