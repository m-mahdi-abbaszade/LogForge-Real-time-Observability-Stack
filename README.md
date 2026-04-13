# LogForge: Real-time Observability Stack

LogForge is a Docker-based log monitoring system built with OpenSearch, Fluent Bit, and Nginx.

It collects logs in real-time and visualizes them using OpenSearch Dashboards.

---

## 🚀 Architecture

Nginx → Fluent Bit → OpenSearch → Dashboards

---

## ⚙️ Tech Stack

- OpenSearch
- OpenSearch Dashboards
- Fluent Bit
- Nginx
- Docker Compose

---

## 📦 How to Run

```bash
docker-compose up -d
```

---

## 🌐 Services

. Nginx: http://localhost:8080
. Dashboards: http://localhost:5601
. OpenSearch: http://localhost:9200
