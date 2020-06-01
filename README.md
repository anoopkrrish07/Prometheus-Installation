# Prometheus-Installation Script(Shell)

Visit [prometheus.io](https://prometheus.io) for the full documentation, examples and guides.

Prometheus, a [Cloud Native Computing Foundation](https://cncf.io/) project, is a systems and service monitoring system. It collects metrics from configured targets at given intervals, evaluates rule expressions, displays the results, and can trigger alerts if some condition is observed to be true.

Prometheus's main distinguishing features as compared to other monitoring systems are:

* a multi-dimensional data model (timeseries defined by metric name and set of key/value dimensions)
* a flexible query language to leverage this dimensionality
* no dependency on distributed storage; single server nodes are autonomous
* timeseries collection happens via a pull model over HTTP
* pushing timeseries is supported via an intermediary gateway
* targets are discovered via service discovery or static configuration
* multiple modes of graphing and dashboarding support
* support for hierarchical and horizontal federation


**Here 3 scripts are available to create a simple Prometheus environment.**
```
1, Prometheus-installation.sh --> It fetches and install Prometheus 2.18.1
2, Node-exporter.sh --> node exporter 1.0.0 installation script.
3, Grafana-Installation.sh --> Grafana installation script.
```
