# 🐳 Awesome Docker Compose Stack
<img src="./docs/docker.avif">

Welcome to the **Docker Compose Collection** repository! This repository contains a set of preconfigured Docker Compose files to help you quickly spin up various services with minimal effort. Whether you're developing locally, testing, or deploying services, these configurations are designed to save you time and hassle.

A curated collection of **Docker Compose** configurations for popular self-hosted services.

---

# 🧱 Self-Hosted Infrastructure Stack

A curated collection of Docker Compose files for self-hosting essential services including databases, authentication, AI, monitoring, development tools, messaging, and more.

---

# 🧱 Self-Hosted Infrastructure Stack

A curated collection of Docker Compose files for self-hosting essential services including databases, authentication, AI, monitoring, development tools, messaging, and more.

---

## 📦 What's Inside?

### 🗄️ [Database Services - Storage Solutions](./database/)
- [MySQL](./database/mysql)
- [PostgreSQL + pgAdmin](./database/postgres-pgadmin)
- [MongoDB](./database/mongodb)
- [SQL Server](./database/sqlserver)
- [Redis + Redis UI](./database/redis-redisUI)
- [MinIO](./database/minio)

---

### 🔒 [Auth & Identity Providers](./auth/)
- [Keycloak](./auth/keycloak) – Identity and access management
- [Authentik](./auth/authentik) – SSO and identity provider

---

### 🧠 [AI / Agents / Workflow Tools](./ai/)
- [DeepSeek](./ai/deepseek) – Open-source LLM
- [Ollama](./ai/ollama) – Run AI models locally
- [Flowise](./ai/flowise) – Visual LLM workflow automation
- [n8n](./ai/n8n) – General workflow automation

---

### 🧰 [Development Tools](./dev-tools/)
- [Portainer](./dev-tools/portainer) – Docker container manager
- [Nexus Repository Manager](./dev-tools/nexus-repository-manager) – Binary repository
- [Jira (Atlassian)](./dev-tools/jira-atlasian) – Issue tracking and project management
- [Jupyter Notebook](./dev-tools/jupyter-notebook) – Interactive Python notebooks

---

### ⚙️ [CI/CD Tools](./ci-cd/)
- [GitLab CE](./ci-cd/gitlab-ce) – Self-hosted Git service
- [GitLab Runner](./ci-cd/gitlab-runner) – Job runner for GitLab
- [Jenkins](./ci-cd/jenkins) – Open-source automation server

---

### 📡 [Message Brokers & Communication](./messaging/)
- [RabbitMQ](./messaging/rabbitmq) – Traditional message broker
- [Mosquitto (MQTT)](./messaging/mosquitto) – Lightweight pub/sub messaging
- [Rocket.Chat](./messaging/rocket-chat) – Self-hosted team chat
- [Mattermost](./messaging/mattermost) – Open-source Slack alternative

---

### 🌐 [Web Servers & API Gateways](./gateway/)
- [NGINX Proxy Manager](./gateway/nginx-proxy-manager) – Web proxy with UI
- [Kong Gateway](./gateway/kong-gateway) – API gateway with plugins

---

### 📊 [Monitoring & Telemetry](./monitoring/)
- [Grafana](./monitoring/grafana) – Metrics & dashboard visualization
- [Prometheus](./monitoring/prometheus) – Metrics collection & alerting
- [Teleport](./monitoring/teleport) – Secure infrastructure access
- [Uptime Kuma](./monitoring/uptimeKUMA) – Uptime monitoring with alerts

---

### ❗ [Error Tracking](./error-tracking/)
- [Sentry](./error-tracking/sentry) – Track and debug exceptions

---

### 🔁 [Workflow Orchestration](./workflow/)
- [Airflow](./workflow/airflow) – Data and task pipeline orchestration

---

### 🔍 [Search Platform](./search/)
- [Elasticsearch](./search/elasticsearch) – Full-text search engine

---

### ✅ [Productivity Tools](./productivity/)
- [Notion (Self-hosted)](./productivity/notion) – Note-taking and task management

---

## 📄 Contribution

We welcome contributions!

- See [CONTRIBUTING.md](./CONTRIBUTING.md) for English instructions.
- برای راهنمای فارسی، به [CONTRIBUTING-fa.md](./CONTRIBUTING-fa.md) مراجعه کنید.

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



## Star History

[![Stargazers over time](https://starchart.cc/alisharify7/preconfigured-docker-compose.svg?variant=adaptive)](https://starchart.cc/alisharify7/preconfigured-docker-compose)
