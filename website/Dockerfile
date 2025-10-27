FROM devopsedu/webapp
ADD . /var/www/html
RUN rm -f /var/www/html/index.html
CMD ["apachectl", "-D", "FOREGROUND"]
