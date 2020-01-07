# Base Image 
FROM ubuntu:16.04

# Owner
MAINTAINER SUKIRAT

# UPDATE the base package
RUN apt-get update

# Install Apache
RUN apt-get install apache2 -y

# Excure the apache serverice

CMD ["/usr/sbin/apache2ctl", "-D", "FOREGROUND"]
