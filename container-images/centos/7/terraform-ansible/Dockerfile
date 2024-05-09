FROM centos:centos7

ENV	HOME	/root

RUN	yum install -y			\
	epel-release unzip	&&	\
	yum install -y			\
	ansible

RUN	curl -L --remote-name https://dl.bintray.com/mitchellh/terraform/terraform_0.6.3_linux_amd64.zip

RUN	unzip -d /usr/bin terraform_0.6.3_linux_amd64.zip

WORKDIR	/root

