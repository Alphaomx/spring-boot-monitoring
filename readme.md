# Spring Boot Monitoring

A production-ready Spring Boot application demonstrating modern observability practices using **Spring Boot Actuator**, **Prometheus**, **Grafana**, and **OpenTelemetry**. The project provides application health monitoring, metrics visualization, distributed tracing, and centralized logging to help monitor and troubleshoot applications in real time.

## Features

- Real-time application monitoring
- Spring Boot Actuator integration
- Prometheus metrics collection
- Grafana dashboards for visualization
- Distributed tracing with OpenTelemetry
- Docker-based deployment
- Health check endpoints
- JVM and application metrics
- Request monitoring and performance analysis

## Tech Stack

- Java 17
- Spring Boot
- Spring Boot Actuator
- Prometheus
- Grafana
- OpenTelemetry
- Docker
- Maven

## Project Structure

```text
src
├── main
│   ├── java
│   ├── resources
│   └── docker
├── test
└── pom.xml
```

## Prerequisites

- Java 17 or later
- Maven 3.8+
- Docker
- Docker Compose

## Monitoring Endpoints

| Endpoint               | Description                 |
| ---------------------- | --------------------------- |
| `/actuator/health`     | Application health          |
| `/actuator/info`       | Application information     |
| `/actuator/metrics`    | Available metrics           |
| `/actuator/prometheus` | Prometheus metrics endpoint |

## Observability Stack

- **Spring Boot Actuator** – Application health and metrics
- **Prometheus** – Metrics collection
- **Grafana** – Dashboard visualization
- **OpenTelemetry** – Distributed tracing

## Project Highlights

- Production-style observability implementation
- Containerized deployment using Docker
- Real-time metrics collection
- Centralized monitoring dashboards
- Performance monitoring
- Health monitoring for services
- Distributed tracing support

## Future Improvements

- Custom health indicators
- Alert notifications
- Authentication and authorization
- Additional Grafana dashboards
- Kubernetes deployment
- Log aggregation using ELK/OpenSearch
- CI/CD pipeline

## Learning Outcomes

This project helped reinforce concepts related to:

- Spring Boot production deployments
- Application observability
- Metrics collection
- Monitoring and visualization
- Distributed tracing
- Docker-based deployments
- Production troubleshooting
