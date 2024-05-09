FROM    	centos:centos7

ENV HOME    /usr/local/go
ENV GOPATH  $HOME
ENV PATH    $PATH:$GOPATH/bin

RUN yum install -y	\
	bzr 		\
	curl 		\
	git 		\
	golang 		\
	mercurial 	\
	subversion && 	\
    mkdir -p $GOPATH/{bin,src,pkg}

WORKDIR	/usr/local/go

