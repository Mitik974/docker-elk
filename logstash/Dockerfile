ARG ELASTIC_VERSION

# https://www.docker.elastic.co/
FROM docker.elastic.co/logstash/logstash:${ELASTIC_VERSION:-9.0.2}

# Copy pipeline configuration
COPY pipeline/ /usr/share/logstash/pipeline/

# Add your logstash plugins setup here
# Example: RUN logstash-plugin install logstash-filter-json
