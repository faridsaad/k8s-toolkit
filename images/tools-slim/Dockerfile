FROM debian:bullseye-slim
ENV USER root
ENV USERID 0

RUN apt-get update && \
    apt-get -y install curl \
    iputils-ping procps tcpdump \
    wget net-tools vim-tiny

WORKDIR /app

CMD while true; do sleep 10; done
