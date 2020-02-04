#Docker Build Simulation for Sample.sh
FROM ubuntu:16.04
LABEL MAINTAINER dj@webapps.com
RUN mkdir /code
COPY Sample.sh /cose/Sample.sh
RUN chmod +x /cose/Sample.sh
#sh /cose/Sample.sh
#etc/hosts
ENTRYPOINT ["sh","/cose/Sample.sh"]
CMD [/etc/hosts"]
