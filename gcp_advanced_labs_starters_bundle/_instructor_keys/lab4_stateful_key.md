# Instructor Key (Outline) – Lab 4 – Stateful Microservices on GKE

> NOTE: This is an outline of a strong reference solution. Fill in full Terraform resources as desired.

## Core Architecture
- High-level diagram: see diagrams/lab4_stateful.png
- Major components:
  - GCP project(s)
  - Networking (VPC / subnets / private access)
  - IAM roles and bindings
  - Service-specific resources (GKE, Cloud SQL, Vertex, IAP, etc.)

## Must-Have Elements
- Security baselines
- Observability (logs/metrics)
- Cost / quota awareness

## Common Student Mistakes
- Missing private access
- Overly-broad IAM
- No environment separation
