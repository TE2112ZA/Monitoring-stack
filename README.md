# Monitoring Stack (Prometheus + Grafana)

A monitoring stack using **Docker Compose** with Prometheus, Grafana, Node Exporter, and cAdvisor.

## Services
- **Prometheus** → [http://localhost:9090](http://localhost:9090)
- **Grafana** → [http://localhost:3000](http://localhost:3000) (admin/admin)
- **Node Exporter** → [http://localhost:9100](http://localhost:9100) (system metrics)
- **cAdvisor** → [http://localhost:8080](http://localhost:8080) (container metrics)

## Run
```bash
docker compose up -d
```

## Dashboards
- Import dashboards in Grafana:
  - *Node Exporter Full*
  - *Docker / cAdvisor*
