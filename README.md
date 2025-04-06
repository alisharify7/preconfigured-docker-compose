# Docker Compose Collection 🐳
<img src="./docs/docker.avif">

Welcome to the **Docker Compose Collection** repository! This repository contains a set of preconfigured Docker Compose files to help you quickly spin up various services with minimal effort. Whether you're developing locally, testing, or deploying services, these configurations are designed to save you time and hassle.


## 📦 **What's Inside?**

This repository includes Docker Compose configurations for the following services:

- **Database Services**:
  - Redis / redis ui
  - Mysql
  - Postgres / Pgadmin4 
- **Web Servers / Gateway**:
  - Nginx + manager UI
  - Kong Gateway
- **Development Tools**:
    -   
- **Message Brokers**:
  - Redis + redisUI
  - Mosquitto MQTT
  - RabbitMQ
- **Monitoring & Logging**:
  - teleport
- **Other Services**:
  - Jira Atlasian

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
