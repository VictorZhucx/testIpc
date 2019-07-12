FROM ubuntu:16.04

COPY edge.sh /usr/local/bin
COPY proxy_sample_remote /usr/local/bin
COPY ./libnanomsg.so.5.0.0 /usr/local/bin

CMD /usr/local/bin/edge.sh
