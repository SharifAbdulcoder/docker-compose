FROM centos:7

RUN yum install httpd -y 

COPY .  /var/www/html/

WORKDIR '/var/www/html'

RUN echo "<img src="funny.gif" alt="My test image">" >> /var/www/html/index.html             

CMD [ "/usr/sbin/httpd", "-D", "FOREGROUND" ]
