FROM centos-7-java

ENV	HOME	/root

RUN	rpm --import http://packages.elasticsearch.org/GPG-KEY-elasticsearch

ADD	repos/elasticsearch-1.4.x.repo	/etc/yum.repos.d/
ADD	repos/logstash-1.4.x.repo	/etc/yum.repos.d/
