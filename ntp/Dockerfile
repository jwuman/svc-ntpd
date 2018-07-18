FROM alpine:latest
MAINTAINER agtsmith@gmail.com

RUN apk add --no-cache openntpd

COPY asset/ntpd.conf /etc/ntpd.conf

EXPOSE 123

ENTRYPOINT ["/usr/sbin/ntpd", "-v", "-d", "-s" ]
