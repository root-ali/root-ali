+++
title = "Velero Reporter"
date = 2025-06-15
draft = false
summary = "Kubernetes operator that watches Velero backups and sends Mattermost notifications on success or failure."
tags = ["go", "kubernetes", "velero", "helm", "mattermost"]
+++

## Overview

Velero Reporter runs in a Kubernetes cluster and watches Velero Backup custom resources for status changes. When a backup completes or fails, it posts a notification to a Mattermost channel via incoming webhooks — giving operators real-time feedback without digging through cluster logs.

## Highlights

- **Informer-based watching** — efficient Velero Backup monitoring without polling
- **Mattermost integration** — configurable webhook URL and token via environment variables
- **Resume-safe** — ConfigMap tracks the last processed resource version across restarts
- **Health checks** — verifies Kubernetes API readiness before processing
- **Helm chart** — deployable in-cluster or out-of-cluster with a single `helm install`

## Stack

- **Runtime:** Go 1.20+, Kubernetes client-go informers
- **Integrations:** Velero CRDs, Mattermost incoming webhooks
- **Deployment:** Docker, Helm chart

## Links

- [Source code](https://github.com/root-ali/velero-reporter)
