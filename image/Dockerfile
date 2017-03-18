FROM osixia/web-baseimage:1.0.0
MAINTAINER Bertrand Gouny <bertrand.gouny@osixia.net>

# Install nginx using osixia/baseimage utils
RUN apt-get update \
		&& /container/tool/add-service-available :nginx \
    && apt-get clean \
    && rm -rf /var/lib/apt/lists/* /tmp/* /var/tmp/*

# Add service directory to /container/service
ADD service /container/service

# Use baseimage install-service script
# https://github.com/osixia/docker-light-baseimage/blob/stable/image/tool/install-service
RUN /container/tool/install-service

# Expose http default port
EXPOSE 80
