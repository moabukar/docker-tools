FROM debian:7

ENV	HOME	/usr/local/go
ENV	GOPATH	$HOME
ENV	PATH	$PATH:$GOPATH/bin

RUN	apt-get update && 	\
	apt-get install -y	\
	bzr 			\
	curl 			\
	git 			\
	golang 			\
	mercurial 		\
	subversion && 		\
	apt-get clean && 	\
	mkdir -p $GOPATH/{bin,src,pkg}

WORKDIR	/usr/local/go/src
