# StreamNative Cloud Dashboards

StreamNative Cloud users can use the pre-built grafana dashboards and alerting rules to monitor the Pulsar cluster resources.

## Grafana Dashboards

### Setup the Prometheus instance

Follow the [Prometheus integration](https://docs.streamnative.io/docs/cloud-metrics-api#prometheus-integration) to setup a prometheus as the Grafana datasource.

### Setup the Grafana instance

Follow the [Set up Grafana](https://grafana.com/docs/grafana/latest/setup-grafana/) to set the Grafana up and running. Import the [pre-built grafana dashboards](https://github.com/streamnative/streamnative-cloud-dashboard/tree/main/dashboards). 

## Alerting

StreamNative Cloud users can refer the [alerting rules](https://raw.githubusercontent.com/streamnative/streamnative-cloud-dashboard/refs/heads/main/alerts/rule.yaml) to configure for the [Alertmanager](https://prometheus.io/docs/alerting/latest/alertmanager/).
