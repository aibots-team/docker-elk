ARG ELASTIC_VERSION

# https://www.docker.elastic.co/
FROM docker.elastic.co/elasticsearch/elasticsearch:${ELASTIC_VERSION}

# Add your elasticsearch plugins setup here
# Example: RUN elasticsearch-plugin install analysis-icu

# Install IK analyzer plugin
RUN elasticsearch-plugin install -b https://github.com/medcl/elasticsearch-analysis-ik/releases/download/v8.11.1/elasticsearch-analysis-ik-8.11.1.zip 