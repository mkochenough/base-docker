FROM debian:jessie
MAINTAINER Michael Koch <michael.koch@enough.de>

RUN \
	apt-get update && \
	apt-get upgrade -y && \
	apt-get clean && \
	rm -rf /var/lib/apt/lists/*

