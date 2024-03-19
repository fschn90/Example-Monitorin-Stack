# Example Monitoring Stack

to monitor a Mysql database and the machine its running on.

run with:

```docker-compose
docker-compose -f docker-compose.yml -p "monitoring_stack"
```

based on:

- docker
- docker-compose
- Graphana
- Prometheus

Graphana Dashboards recommended:

- [MySQL Overview](https://grafana.com/grafana/dashboards/7362-mysql-overview/)
- [Node Exporter Full](https://grafana.com/grafana/dashboards/1860-node-exporter-full/)
- [Docker Container & Host Metrics](https://grafana.com/grafana/dashboards/10619-docker-host-container-overview/)

Further reading:

- https://grafana.com/docs/grafana/latest/setup-grafana/installation/docker/
- https://grafana.com/docs/grafana/latest/datasources/prometheus/
- https://grafana.com/oss/prometheus/exporters/mysql-exporter/
