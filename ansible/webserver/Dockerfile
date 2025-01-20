FROM ubuntu:latest

RUN apt-get update && \
    apt-get install -y apache2 && \
    apt-get clean

COPY config /etc/apache2/sites-available/000-default.conf

EXPOSE 80

CMD ["apache2ctl", "-D", "FOREGROUND"]
