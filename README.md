# Docker-compose files for a simple uptodate
# InfluxDB
# + Grafana stack
# + Cronograph

What to you need to run this software:

* Docker
* Docker Compose

Get the software:

```
git clone https://github.com/mrbitsdcf/docker-influxdb-grafana.git
```

Run your stack:

```
docker-compose up -d
```

Show me the logs:

```
docker-compose logs
```

Stop it:

```
docker-compose stop
docker-compose rm
```

Update it:

```
git pull
docker pull grafana/grafana
docker pull influxdb
docker pull telegraf
```

