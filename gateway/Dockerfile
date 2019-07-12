FROM ubuntu:16.04

COPY gateway.sh /usr/local/bin
COPY liblogger.so /usr/local/bin
COPY libgateway.so /usr/local/bin
COPY libnanomsg.so.5.0.0 /usr/local/bin
COPY libhello_world.so /usr/local/bin
COPY proxy_sample /usr/local/bin
COPY proxy_sample_lin.json /usr/local/bin

CMD /usr/local/bin/gateway.sh
