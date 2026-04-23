# System Architecture

## Flow

API Services
   ↓
Log Generator
   ↓
Logstash (pipeline)
   ↓
Elasticsearch (storage)
   ↓
Kibana Dashboard (visualization)

OR (metrics path)

API Services
   ↓
Prometheus (metrics collector)
   ↓
Grafana (dashboard)
