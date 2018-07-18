# NTP

This is how you run this docker

docker run --name ntp \
           --restart=always \
           --detach=true #or just -d \
           --publish=123:123/udp # or just -p 123:123/udp \
           --cap-add=SYS_NICE \
           --cap-add=SYS_RESOURCE \
           --cap-add=SYS_TIME \
           ntp
