FROM rstudio/docker-r-base:precise
MAINTAINER Chad Barraford <chad@rstudio.com>

ENV R_VERSION 3.0.0

# Install R
RUN apt-get install -y r-base-core=3.0.0-2precise r-base-dev=3.0.0-2precise

# set UTF-8
RUN echo "LANG=C.UTF-8" >> /usr/lib/R/etc/Renviron.site
