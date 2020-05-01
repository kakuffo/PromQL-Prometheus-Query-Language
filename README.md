# What is Prometheus
DevOps demands Continuous monitoring as one of it pillars of
best practise.  This need has informed the rapid evolution 
of alerting, and visualization tools to become an adoption
necessity for many software development that employe the
DevOps practices.  Prometheus, an open-source software tool
has become an integral continuous monitoring option for many
DevOps development lifecycle, this importance of the tool is
found in the level of monitoring offered by Prometheus. As
a tool it offers three integral monitoring and alerting solutions.
Firstly, Prometheus offers DevOps Alerting, secondly Prometheus
offers DevOps metrics, and finally Prometheus offers DevOps
visualisation.
Counter
Gauge
Histogram
Summary
## Alerting

The output of any alerting process or system is the ability to
provide indication of the subject of alerting deviating from set parameters.
DevOps is the process of encompassing software operation, typically
software infrastructure management into the software development lifecycle.
Therefore, continuous alerting in DevOps is primarily concerned with monitoring
of infrastructure processes, software and augmenting alerting to the complete development
teams in a DevOps.  The alerting component in Prometheus is the responsibility of the
AlertManager.  The AlertManager responds to deviation from set parameters by organising the
alerting data from the monitoring into actionable information that is then pushed to specified E-mail,
Slack, and other compatible, and configured applications.  

### YML Alertmanager configured



#### Configuration file

To specify which configuration file to load, use the --config.file flag.

## Metrics

Prometheus metrics operates as another component of the compere Prometheus open source
application.  The purpose of the metrics is to afford granular actionable data to the 
DevOps teams.  The granularity of the metrics are realised through a metrics Counter, a metrics
Gauge, a metrics Histogram, and a metrics Summary.  Below are the components explained.

### Counter


### Gauge


### Histogram

### Summary

Prometheus
provides a functional query language called PromQL 
(Prometheus Query Language) that lets the user select
and aggregate time series data in real time. The result of 
an expression can either be shown as a graph, viewed as 
tabular data in Prometheus's expression browser, or consumed
by external systems via the HTTP API.