# 🐳 Awesome Docker Compose Stack
<img src="./docs/docker.avif">

Welcome to the **Docker Compose Collection** repository! This repository contains a set of preconfigured Docker Compose files to help you quickly spin up various services with minimal effort. Whether you're developing locally, testing, or deploying services, these configurations are designed to save you time and hassle.

A curated collection of **Docker Compose** configurations for popular self-hosted services.

---

## 📦 What's Inside?


### 🗄️ Database Services
- **MySQL**
- **PostgreSQL + pgAdmin**
- **MongoDB**
- **SQL Server**

---

### 🧰 Development Tools
- **Portainer** – Docker management UI  
- **Nexus Repository Manager** – Binary artifact repository  
- **GitLab CE** – Self-hosted Git server  
- **Jira (Atlassian)** – Project management tool  
- **n8n** – Workflow automation platform  

---

### 📡 Message Brokers
- **RabbitMQ**
- **Redis + Redis UI**
- **Mosquitto MQTT**

---

### 🌐 Web Servers / API Gateways
- **NGINX + NGINX Proxy Manager**
- **Kong Gateway**

---

### 📊 Monitoring & Logging
- **Grafana** – Metrics visualization
- **Prometheus** – Time-series monitoring
- **Sentry** – Error tracking
- **Teleport** – Secure access to infrastructure

---

### 💬 Communication Tools
- **Rocket.Chat** – Team chat and collaboration
- **Slack** – Team communication and collaboration

---

### 🧠 AI and Machine Learning
- **Ollama** – Large-scale AI model deployment
- **Deepseek AI** – AI-powered search features

---

### 📋 Workflow Orchestration
- **Airflow** – Workflow orchestration

---

### 🔍 Search
- **Elitist Search** – Advanced search capabilities

---

### 📝 Collaboration and Knowledge Management
- **Notion** – Enhanced collaboration and knowledge management

---

Each service is preconfigured with sensible defaults, making it easy to get started.


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
