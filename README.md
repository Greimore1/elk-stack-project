# ELK Stack Log Aggregation System

## Overview
A Docker-based log aggregation system using the ELK stack (Elasticsearch, Logstash, and Kibana)

## Prerequisites
- Docker
- Docker Compose


## Installation

### 1. Clone the Repository
```bash
git clone https://github.com/Greimore1/elk-stack-project.git
cd elk-stack-project
```

### 2. Start the ELK Stack
```bash
docker compose up -d
```

### 3. Access Services
- Kibana: http://localhost:5601
- Elasticsearch: http://localhost:9200

## Configuration
- Logstash pipeline: `logstash/pipeline/logstash.conf`
- Logstash settings: `logstash/config/logstash.yml`

## Troubleshooting
- Check container logs: `docker compose logs <service-name>`
- Restart services: `docker compose restart`
