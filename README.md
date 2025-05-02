# 🐳 Awesome Docker Compose Stack
<img src="./docs/docker.avif">

Welcome to the **Docker Compose Collection** repository! This repository contains a set of preconfigured Docker Compose files to help you quickly spin up various services with minimal effort. Whether you're developing locally, testing, or deploying services, these configurations are designed to save you time and hassle.

A curated collection of **Docker Compose** configurations for popular self-hosted services.

---

## 📦 What's Inside?

### 🗄️ [Database Services - Storage Solution](./database/)
- [MySQL](./database/mysql)
- [PostgreSQL + pgAdmin](./database/postgres-pgadmin)
- [MongoDB](./database/mongodb)
- [SQL Server](./database/sqlserver)
- [Redis + Redis UI](./database/redis-redisUI)
- [Minio](./database/minio/)

---

### 🔒 [Auth/Security](./auth//)
- [Keycloak](./auth/keycloak/)


---

### 🧰 [Development Tools](./dev-tools/)
- [Portainer](./dev-tools/portainer) – Docker management UI  
- [Nexus Repository Manager](./dev-tools/nexus-repository-manager) – Binary artifact repository  
- [GitLab CE](./dev-tools/gitlab-ce) – Self-hosted Git server  
- [Jira (Atlassian)](./dev-tools/jira-atlasian) – Project management tool  
- [n8n](./dev-tools/n8n) – Workflow automation platform  

---

### 📡 [Message Brokers](./messaging/)
- [RabbitMQ](./messaging/rabbitmq)
- [Mosquitto MQTT](./messaging/mosquitto)

---

### 🌐 [Web Servers / API Gateways](./gateway/)
- [NGINX + NGINX Proxy Manager](./gateway/nginx-proxy-manager)
- [Kong Gateway](./gateway/kong-gateway)

---

### 📊 [Monitoring & Logging](./monitoring/)
- [Grafana](./monitoring/grafana) – Metrics visualization
- [Prometheus](./monitoring/prometheus) – Time-series monitoring
- [Sentry](./monitoring/sentry) – Error tracking
- [Teleport](./monitoring/teleport) – Secure access to infrastructure

---

### 💬 [Communication Tools](./messaging/)
- [Rocket.Chat](./messaging/rocket-chat) – Team chat and collaboration

---

Each service is preconfigured with sensible defaults, making it easy to get started.

---

## 🚀 **Getting Started**

### Prerequisites

Before using these Docker Compose files, ensure you have the following installed:

- [Docker](https://docs.docker.com/get-docker/)
- [Docker Compose](https://docs.docker.com/compose/install/)

---

## 🛠 **Customization**

Each Docker Compose file is designed to be easily customizable. You can modify the following:

- **Environment Variables**: Edit the `.env` file or directly modify the `environment` section in the `docker-compose.yml` file.
- **Ports**: Change the port mappings in the `ports` section to avoid conflicts or match your requirements.
- **Volumes**: Adjust the volume mappings to persist data or use specific directories on your host machine.
