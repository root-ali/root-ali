+++
title = "Rashnu"
date = 2025-09-01
draft = false
summary = "FinOps platform for bare-metal infrastructure — inventory, depreciation pricing, and per-service cost reports."
tags = ["go", "react", "postgresql", "finops", "docker"]
+++

## Overview

Rashnu is a FinOps tool for attributing bare-metal infrastructure cost across services. You maintain inventory — datacenters, servers, and network gear — attach workloads from a service catalog, apply depreciation-based pricing, and generate per-service cost reports with multi-currency support. A Go API and React frontend sit on PostgreSQL, with JWT auth and Docker Compose for local or full-stack deployment.

## Highlights

- **Infrastructure inventory** — datacenters, servers, and network equipment in one place
- **Service catalog** — map workloads to hardware and allocate cost across compute, memory, storage, object storage, and Kubernetes resource requests
- **Depreciation pricing** — layer pricing models on top of physical assets for accurate attribution
- **Cost reporting** — per-service breakdowns with multi-currency reporting
- **REST API** — JWT-authenticated API; admin role required for writes
- **Docker Compose** — API, Postgres, and Prometheus in a single `docker compose up`

## Stack

- **Backend:** Go 1.26+, PostgreSQL 16
- **Frontend:** React (Vite)
- **Observability:** Prometheus (optional stack via Compose)

## Links

- [Source code](https://github.com/root-ali/rashnu)
