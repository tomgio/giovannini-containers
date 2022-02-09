FROM alpine:3.15.0
LABEL version="1.0.0" maintainer="Thomas-G" os="linux" distro="alpine"
ENV CONTAINER_USER="Thomas-G"
RUN adduser $CONTAINER_USER --disabled-password
CMD echo "hello-alpine, I'm $CONTAINER_USER and this is a container from my first image"
