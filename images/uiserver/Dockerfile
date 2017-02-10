FROM ubuntu:xenial
ENV TAG xenial
ENV VERSION 1.13.1
RUN mkdir /install && \
apt-get update && apt-get -y install curl
RUN apt-get -y install libltdl7 iptables && \
curl -fsSL https://apt.dockerproject.org/repo/pool/main/d/docker-engine/docker-engine_1.13.1-0~ubuntu-xenial_amd64.deb -o /install/docker.deb && \
dpkg -i /install/docker.deb && \
rm /install/docker.deb
