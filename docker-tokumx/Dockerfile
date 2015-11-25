FROM ubuntu:14.04

ADD ./tokumx-2.0.0-linux-x86_64 /app

WORKDIR /app/bin

CMD ["./mongod","--config","/conf/tokumx.conf"]
