ARG VERSION=7.9.3
FROM docker.elastic.co/logstash/logstash:${VERSION}

# Install Plugins
RUN logstash-plugin install logstash-output-elasticsearch
RUN logstash-plugin install logstash-filter-date_formatter
