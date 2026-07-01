+++
title = "dtail"
date = 2025-04-01
draft = false
summary = "CLI to tail and colorize logs from Docker containers by name or prefix."
tags = ["go", "cli", "docker"]
+++

## Overview

dtail is a lightweight Go CLI that streams logs from one or more Docker containers, matching by exact name or prefix. Output is colorized per container so you can follow multiple services at once without losing track of which line came from where.

## Highlights

- **Multi-container tailing** — pass one or more names or prefixes on the command line
- **Colorized output** — each container gets its own color for quick visual separation
- **Configurable tail depth** — `-n` / `--tail` flag (default 10 lines)
- **Graceful shutdown** — handles Ctrl+C and SIGTERM cleanly
- **Pluggable backend** — `DockerService` interface with a stub for development without a daemon

## Stack

- **Runtime:** Go 1.20+
- **Integration:** Docker daemon (optional stub for local dev)

## Links

- [Source code](https://github.com/root-ali/dtail)
