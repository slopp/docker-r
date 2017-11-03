FROM rstudio/docker-r-base:latest
MAINTAINER RStudio Docker <docker@rstudio.com>

ENV R_VERSION 3.2.0

# Install R
RUN apt-get install -y r-base-core=3.2.0-4trusty0 r-base-dev=3.2.0-4trusty0

# set UTF-8
RUN echo "LANG=C.UTF-8" >> /usr/lib/R/etc/Renviron.site
