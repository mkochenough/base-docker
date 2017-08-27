FROM debian:stretch
MAINTAINER Michael Koch <michael.koch@enough.de>

ENV DEBIAN_FRONTEND=noninteractive

RUN \
	apt-get update && \
	apt-get upgrade -y && \
	apt-get clean && \
	rm -rf /var/lib/apt/lists/*

