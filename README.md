# Monitoring-and-log-system
<h3>Grafana:</h3> The open platform for analytics and monitoring.

Prometheus:  An open-source monitoring system with a dimensional data model, flexible query language, efficient time series database and modern alerting approach.

Node exporter: Prometheus exporter for machine metrics, written in Go with pluggable metric collectors.

Loki: like Prometheus, but for logs. Loki is a horizontally-scalable, highly-available, multi-tenant log aggregation system inspired by Prometheus. It is designed to be very cost effective and easy to operate. It does not index the contents of the logs, but rather a set of labels for each log stream.

Promtail: A logging agent that uses Loki

Alertmanager: The Alertmanager handles alerts sent by client applications such as the Prometheus server. It takes care of deduplicating, grouping, and routing them to the correct receiver integration such as email, PagerDuty, or OpsGenie. It also takes care of silencing and inhibition of alerts.
 
Google/cAdvisor: Analyzes resource usage and performance characteristics of running containers.

