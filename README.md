# Redis Platform

Production-ready Redis Community Edition deployment
for Kubernetes/OpenShift.

Features:

- Redis Community Edition
- Sentinel High Availability
- Prometheus Metrics
- Grafana Dashboards
- Azure Key Vault Integration
- External Secrets
- GitOps Ready
- OpenShift Compatible
- AKS Compatible
- Multi-tenant deployments

## Architecture

Master
├── Replica 1
└── Replica 2

Sentinel x3

## Deploy

helm install redis \
  ./charts/redis-ce
