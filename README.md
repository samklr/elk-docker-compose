# Dockers-ELK

Run ELK with Docker and Docker Compose.

# Setup

```console
$ docker-compose up -d
```

Wait for Kibana  to initialize, then access [http://localhost:5601](http://localhost:5601) from a web browser.

Default exposed ports:
* 5000: Logstash TCP input.
* 9200: Elasticsearch HTTP
* 9300: Elasticsearch TCP transport
* 5601: Kibana
