
This is to show different metrics around nodejs api service using koa.

## Key points:

- Have synchronous operation happening
- Show that koa-logger response time and datadog apm response time is different from the *real* response time reported by load testers
- Show how good event loop delay metric is

## Tools

- Koa for web server
- dd-trace for tracing needs
- statsd-exporter/prometheus/grafana for metrics collection
- siege for running load tests