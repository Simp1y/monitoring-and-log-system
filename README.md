# Monitoring-and-log-system
<p align="center">
  <img width="460" height="300" src="https://github.com/yubozhao/loki/blob/documentation-for-aws-storage/docs/logo_and_name.png">
</p>
<h3>Grafana:</h3> The open platform for analytics and monitoring.

<h3>Prometheus:</h3>  An open-source monitoring system with a dimensional data model, flexible query language, efficient time series database and modern alerting approach.

<h3>Node exporter:</h3> Prometheus exporter for machine metrics, written in Go with pluggable metric collectors.

<h3>Loki:</h3> Like Prometheus, but for logs. Loki is a horizontally-scalable, highly-available, multi-tenant log aggregation system inspired by Prometheus. It is designed to be very cost effective and easy to operate. It does not index the contents of the logs, but rather a set of labels for each log stream.

<h3>Promtail:</h3> A logging agent that uses Loki

<h3>Alertmanager:</h3> The Alertmanager handles alerts sent by client applications such as the Prometheus server. It takes care of deduplicating, grouping, and routing them to the correct receiver integration such as email, PagerDuty, or OpsGenie. It also takes care of silencing and inhibition of alerts.
 
<h3>Google/cAdvisor:</h3> Analyzes resource usage and performance characteristics of running containers.

