FROM debian:jessie
MAINTAINER Michael Koch <michael.koch@enough.de>

RUN \
#	sed -i 's/httpredir.debian.org/172.17.0.1:3142/' /etc/apt/sources.list && \
#	sed -i 's/security.debian.org/172.17.0.1:3142\/debian-security/' /etc/apt/sources.list && \
	apt-get update && \
	apt-get upgrade -y && \
	apt-get clean && \
	rm -rf /var/lib/apt/lists/*

