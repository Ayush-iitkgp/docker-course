# How to create a web container
# httpd is the docler image of the Apache server
FROM httpd:2.4
# If you want to run a simple HTML server, add a simple Dockerfile to your project where public-html/ is the directory containing all your HTML.
# COPY is the docker instruction to copy files from local filesysyem to docker image
COPY . /usr/local/apache2/htdocs/
