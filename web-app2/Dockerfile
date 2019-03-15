FROM centos

RUN yum install httpd -y

WORKDIR '/var/www/html/'

RUN echo "<img src="funny.gif" alt="My test image">" >> /var/www/html/index.html 

COPY . /var/www/html

EXPOSE 80

CMD [ "/usr/sbin/httpd",  "-D",  "FOREGROUND"]
