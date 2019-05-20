# ELK Containerized Demo

Very simple setup to start testing a bundle [Elasticsearch](https://www.elastic.co/products/elasticsearch), [Logstash](https://www.elastic.co/products/kibana) and [Kibana](https://www.elastic.co/products/logstash) on `7.0.1` version. The default ingestion point for [Logstash](https://www.elastic.co/products/kibana) is set to `udp://localhost:12201`.

## Requirements

- Docker

## Running Instructions

1. `docker-compose build`
2. `docker-compose up`
