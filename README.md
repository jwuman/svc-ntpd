# docker ntpd

docker run -d --name ntpd --restart=always -p 123:123/udp --cap-add=SYS_NICE --cap-add=SYS_RESOURCE --cap-add=SYS_TIME jwuman/svc-ntpd
