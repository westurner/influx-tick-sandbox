ARG INFLUXDB_TAG
FROM quay.io/influxdb/influxdb:$INFLUXDB_TAG

#RUN apk add collectd
RUN mkdir -p /usr/local/share/collectd && \
    wget -P /usr/local/share/collectd https://raw.githubusercontent.com/collectd/collectd/master/src/types.db
