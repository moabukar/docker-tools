FROM elasticsearch

RUN	yum install -y elasticsearch							&&	\
	mkdir -p /usr/share/elasticsearch/config					&&	\
	ln -s /etc/elasticsearch/* /usr/share/elasticsearch/config

# enable to kibana consume (disabled in 1.4)
RUN	echo 'http.cors.enabled: true' >> /etc/elasticsearch/elasticsearch.yml

EXPOSE 9200
EXPOSE 9300

CMD	["/usr/share/elasticsearch/bin/elasticsearch"]
