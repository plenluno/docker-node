FROM centos:6.4
MAINTAINER Plenluno
RUN yum -y install curl perl which
RUN curl -L https://raw.githubusercontent.com/hokaccha/nodebrew/v0.7.3/nodebrew | perl - setup
ENV PATH $HOME/.nodebrew/current/bin:$PATH
ENV NODE_VERSION stable
RUN nodebrew install-binary $NODE_VERSION
RUN nodebrew use $NODE_VERSION
