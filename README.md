# monitoring_grafana

### Monitoring Setup with InfluxDB, Grafana, and Telegraf

This repository contains an Ansible playbook for installing and configuring Telegraf to collect system metrics and send them to InfluxDB.

InfluxDB and Grafana should be set up separately. The playbook prepares Telegraf to work with InfluxDB, enabling metrics collection for use in dashboards (e.g., memory usage) in Grafana.
