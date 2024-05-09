FROM centos-7-repo-elasticsearch

RUN	yum install -y yum-utils				&&	\
	yumdownloader --destdir=/tmp logstash			&&	\
	rpm --nodeps -i `find /tmp -name logstash-*.rpm`	&&	\
	rm /tmp/logstash-*.rpm					&&	\
	yum remove -y yum-utils					&&	\
	yum clean -y all

ENTRYPOINT	[ "/opt/logstash/bin/logstash" ]
