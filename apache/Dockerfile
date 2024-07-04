FROM ubuntu:20.04
RUN apt-get update && \
    apt-get install -y apache2 && \
    echo '<h1>Hello World from Apache!</h1>' > /var/www/html/index.html
EXPOSE 80
CMD ["apachectl", "-D", "FOREGROUND"]
