Docker image with Grafana and InfluxDB on CentOS 6
=======================

This Docker image is based on CentOS 6 with latest [InfluxDB](http://influxdb.com/) and [Grafana](http://grafana.org/) `1.9.0-rc1`.

### Grafana

Two InfluxDB databases `app` and `grafana` are created automatically. `app` is used to store application data, `grafana` is used by Grafana.


### Exposed ports

Port | Description
---- | ----------
80 | Grafana UI
8083 | InfluxDB Admin UI
8086 | InfluxDB API
