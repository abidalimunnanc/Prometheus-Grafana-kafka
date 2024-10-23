# Prometheus-Grafana-kafka


## rometheus setupr for kafka
JMX Exporter is a collector that can run as a part of an existing Java application (such as Kafka) and expose its JMX metrics over an HTTP endpoint, which can be consumed by any system such as Prometheus. For more information about Prometheus exporters, here is our article that deep dives into how [Prometheus exporters work][https://www.metricfire.com/blog/first-contact-with-prometheus/]

the JMX exporter instance running as part of the Kafka instance.

The configuration file ```prom-jmx-agent-config.yml```

### docker

```docker compose build```

```docker compose up -d```

### Grafana Dashboard 

Browse to http://localhost:3000, log in using admin/admin, and add the data source  “Prometheus”: will be referring to this data source name when we query in our Grafana dashboards.

### Kafka 
use python script to send message to kaka topics

