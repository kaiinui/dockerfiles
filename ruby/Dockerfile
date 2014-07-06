FROM ubuntu:12.04

##
NOT USED NOW
##

RUN apt-get update
RUN apt-get -y dist-upgrade
RUN apt-get install -y --fix-missing curl wget git vim tmux build-essential
RUN wget http://cache.ruby-lang.org/pub/ruby/2.1/ruby-2.1.1.tar.gz
RUN tar xzfv ruby-2.1.1.tar.gz
RUN cd ruby-2.1.1 ; ./configure
RUN cd ruby-2.1.1 ; make && make install