FROM ubuntu:14.04
MAINTAINER Plenluno
RUN apt-get -y install curl
RUN curl -L git.io/nodebrew | perl - setup
ENV PATH $HOME/.nodebrew/current/bin:$PATH
ENV NODE_VERSION stable
RUN nodebrew install-binary $NODE_VERSION
RUN nodebrew use $NODE_VERSION
