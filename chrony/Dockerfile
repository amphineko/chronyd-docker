FROM alpine:latest

RUN apk add --no-cache chrony

CMD ["/usr/sbin/chronyd", "-f", "/data/chrony.conf", "-n"]

VOLUME ["/data"]
