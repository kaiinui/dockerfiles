FROM kaiinui/ruby-fluentd

RUN echo "deb http://apt.mackerel.io/debian/ mackerel contrib" >> /etc/apt/sources.list.d/mackerel.list
RUN wget -O- https://mackerel.io/assets/files/GPG-KEY-mackerel | apt-key add -
RUN apt-get update
RUN apt-get -y install mackerel-agent