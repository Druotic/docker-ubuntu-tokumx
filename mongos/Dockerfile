FROM leifw/ubuntu-tokumx:precise
MAINTAINER Leif Walsh <leif.walsh@gmail.com>

RUN sed -i'' -e '/dbpath/d' /etc/tokumx.conf

ENTRYPOINT ["/usr/bin/mongos"]
