FROM rstudio/docker-r-base:latest
MAINTAINER Chad Barraford <chad@rstudio.com>

ENV R_VERSION 3.0.2

# Install R
RUN apt-get install -y r-base-core=3.0.2-1ubuntu1 r-base-dev=3.0.2-1ubuntu1

# set UTF-8
RUN echo "LANG=C.UTF-8" >> /usr/lib/R/etc/Renviron.site
