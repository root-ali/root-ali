+++
title = "Iris"
date = 2025-08-01
draft = false
summary = "Alert management and notification system for Grafana and AlertManager — multi-channel delivery, RBAC, and a React dashboard."
tags = ["go", "react", "postgresql", "alerting", "grafana"]
+++

## Overview

Iris receives alerts from monitoring systems like Grafana and AlertManager, stores them centrally, and dispatches notifications through configurable providers — SMS (Kavenegar, Smsir) and email — with priority-based routing and delivery retries. A React web dashboard gives operators a single place to monitor, manage, and route alerts across teams.

## Highlights

- **Alert pipeline** — ingest from AlertManager, persist in PostgreSQL, process via background schedulers
- **Multi-channel notifications** — configurable, priority-based provider system for SMS and email
- **RBAC** — users, roles, and groups for fine-grained alert routing and access control
- **REST API** — JWT-authenticated API for integration with external systems
- **Web dashboard** — React frontend for alert monitoring, user management, and provider configuration
- **Production-ready auth** — CAPTCHA on registration, secure token-based sessions

## Stack

- **Backend:** Go 1.23+, PostgreSQL 13+
- **Frontend:** React (Node.js 16+)
- **Integrations:** AlertManager, Grafana, Kavenegar, Smsir

## Links

- [Source code](https://github.com/lyralab/iris)
