FROM php:5.6-cli
COPY ../.vimrc /root
WORKDIR /usr/src/myapp
RUN apt-get update && apt-get install -y \
        vim \
        && apt-get clean \
        && rm -rf /var/lib/apt/lists/* /tmp/* /var/tmp/*
