FROM mkoch/base
MAINTAINER Michael Koch <michael.koch@enough.de>

RUN \
#	echo 'deb http://172.17.0.1:3142/debian jessie-backports main' >> /etc/apt/sources.list.d/backports.list && \
	echo 'deb http://httpredir.debian.org/debian jessie-backports main' >> /etc/apt/sources.list.d/backports.list && \
	apt-get update && \
	rm -rf /var/lib/apt/lists/*

