# Nexoryx_Kafka_Platform

Production-ready Apache Kafka platform for Kubernetes with Kafka brokers, KRaft mode, Kafka UI, Schema Registry, Prometheus monitoring, Grafana dashboards, autoscaling, and distributed event streaming architecture.

## Features

- Apache Kafka KRaft cluster
- Kafka UI management console
- Schema Registry
- Distributed event streaming
- Kubernetes-native deployment
- Persistent storage
- Prometheus monitoring
- Grafana dashboards
- Ingress support
- Autoscaling support
- Resource limits
- Health probes
- Production-ready manifests

## Stack

- Kubernetes
- Apache Kafka
- Kafka UI
- Schema Registry
- Prometheus
- Grafana
- NGINX Ingress

## Deployment

```bash
kubectl apply -f kubernetes/
```

## Namespace

```bash
nexoryx-kafka
```

## Components

- Kafka Brokers
- Kafka UI
- Schema Registry
- Prometheus
- Grafana
- Ingress
- HPA Autoscaling

## Notes

Update domains, storage classes, and secrets before production deployment.
