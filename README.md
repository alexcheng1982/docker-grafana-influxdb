Docker image with Grafana and InfluxDB on CentOS 6
=======================

This Docker image is based on CentOS 6 with latest [InfluxDB](http://influxdb.com/) and [Grafana](http://grafana.org/) `1.9.0-rc1`.

## InfluxDB databases

Two InfluxDB databases `app` and `grafana` are created automatically. `app` is used to store application data, `grafana` is used by Grafana.


## Exposed ports

* __80__   - Grafana UI
* __8083__ - InfluxDB Admin UI
* __8086__ - InfluxDB API


## How to run

Pull the image using `docker pull alexcheng/docker-grafana-influxdb`, then run it using `docker run -d -p 80:80 -p 8083:8083 -p 8086:8086 alexcheng/docker-grafana-influxdb`.
