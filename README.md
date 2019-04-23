# Monitoring-and-log-system
<p align="center">
  <img width="700" height="350" src="https://github.com/Simp1y/monitoring-and-log-system/blob/master/images/grafana-prometheus.jpg">
</p>
## Docker-Compose:
###### Documentation
###### How to install and configure
- [Docker](https://docs.docker.com/install/linux/docker-ce/ubuntu/)
- [Docker-Compose](https://docs.docker.com/compose/install/)
Command too run: docker-compose -f monitoring.yml up -d
Docker-Compose file: monitoring.yml
Path to main config file for Prometheus: ./prometheus/prometheus.yml (all monitoring targets sets here)
Path to main config file for Grafana: ./grafana/grafana.ini


## Grafana: 
The open platform for analytics and monitoring.
###### Documentation
- [Grafana docs](https://grafana.com/docs/)
- [Grafana dashboards](https://grafana.com/dashboards)
- [How to install and configure](https://grafana.com/docs/installation/)

## Prometheus:
An open-source monitoring system with a dimensional data model, flexible query language, efficient time series database and modern alerting approach.
###### Documentation
- [Prometheus docs](https://prometheus.io/docs/introduction/overview/)
- [How to install and configure](https://devopscube.com/install-configure-prometheus-linux/)

## Node exporter:
Prometheus exporter for machine metrics, written in Go with pluggable metric collectors.
###### Documentation
- [How to install and configure](https://prometheus.io/docs/guides/node-exporter/)

## Loki:
Like Prometheus, but for logs. Loki is a horizontally-scalable, highly-available, multi-tenant log aggregation system inspired by Prometheus. It is designed to be very cost effective and easy to operate. It does not index the contents of the logs, but rather a set of labels for each log stream.
###### Documentation
- [about Loki](https://grafana.com/loki#about)

## Promtail:
Is the agent, responsible for gathering logs and sending them to Loki.

## Alertmanager: 
The Alertmanager handles alerts sent by client applications such as the Prometheus server. It takes care of deduplicating, grouping, and routing them to the correct receiver integration such as email, PagerDuty, or OpsGenie. It also takes care of silencing and inhibition of alerts.
 ###### Documentation
- [about Alertmanager](https://prometheus.io/docs/alerting/alertmanager/)
 
## Google/cAdvisor:
Analyzes resource usage and performance characteristics of running containers.
###### Documentation
- [How to install and configure](https://prometheus.io/docs/guides/cadvisor/)

## worldPing: 
Is a plugin for Grafana that continually tests, stores and alerts on the global performance and availability of your Internet applications so you can pinpoint issues, fix them immediately, and improve your user’s experience.

You can use worldPing to get a real-time view of any endpoint's performance and availability. As often as every 10 seconds, we will test your application from dozens of Probes around the world, Alerting you in real-time if there are any outages or slow-downs.
## Features worldPing plugin
There’s no software or agent to install or configure. Be up and running with worldPing in less than 60 seconds. Just give us the domain name of your site or application, and we’ll automatically detect what to monitor.
#### Supported Protocols
- Ping uptime and performance (eg. latency, loss, jitter)
- DNS uptime and performance (eg. latency, responses)
- HTTP and HTTPS (uptime and performance)
#### Alerting
When you have a problem, worldPing will send you a high quality and speedy alert, configurable on a per-endpoint basis. It also helps triage by pinpointing the problem to a particular region or part of your stack.
#### API Access
Anything that you can do through the UI you can also do through our full featured HTTP API, docs can be found at [docs.worldping.apiary.io](http://docs.worldping.apiary.io)
#### Requirements
WorldPing requires only a [Grafana.com](https://grafana.com) account and [Grafana 3.x](https://grafana.com/grafana/download) to install. There are no other external dependencies, accounts or configuration needed.
###### Documentation
- [worldPing Usecases](http://worldping.raintank.io/worldping/use-cases)
- [worldPing FAQ](https://grafana.com/cloud/worldping#FAQ)
- [worldPing documentation](http://worldping.raintank.io/docs/)


