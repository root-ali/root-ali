+++
title = "Resume"
type = "page"
+++

<p class="resume-meta">
  <strong>Ali Soltani</strong> · Senior DevOps &amp; Platform Engineer<br>
  Tehran, Iran · Open to relocation — EU Blue Card / Highly-Skilled-Migrant eligible<br>
  <a href="mailto:soltaniam@hotmail.com">soltaniam@hotmail.com</a> · +98 915 323 9343 ·
  <a href="https://www.linkedin.com/in/ali-soltani-54594ab3/" rel="noopener" target="_blank">LinkedIn</a> ·
  <a href="https://github.com/root-ali" rel="noopener" target="_blank">GitHub</a> ·
  <a href="https://ali-soltani.ir" rel="noopener" target="_blank">ali-soltani.ir</a>
</p>

<a href="/resume.pdf" class="btn">Download PDF</a>

## Summary

DevOps and platform engineer with over ten years building and running production systems for fintech and payment platforms. Now leads a DevOps and infrastructure team while staying close to the work itself: designing multi-datacenter platforms, running Kubernetes and distributed databases, and keeping the monitoring and security around them in good shape. Just as comfortable writing tools and services in Go and Python as operating the systems they support.

## Skills

- **Orchestration & Containers:** Kubernetes (RKE2 & Kubespray), Docker, Podman, Helm
- **Databases & Storage:** CockroachDB, PostgreSQL, ClickHouse, MongoDB, Redis, MinIO (S3-compatible)
- **Observability & Alerting:** Prometheus, Thanos, Grafana, Loki, Alertmanager, Elasticsearch / Kibana, Splunk
- **Security & DevSecOps:** Wazuh, FortiGate, TLS / PKI, penetration testing, vulnerability management
- **IaC & Automation:** Ansible (advanced), Ansible AWX, Terraform, Pulumi, Jinja2
- **CI/CD & Artifacts:** GitLab CI/CD, Jenkins, Harbor, Nexus, NetBox (IPAM)
- **Linux Networking:** Policy / static routing, iptables, ipset, custom routing tooling, site-to-site VPN (WireGuard / GRE / IPIP), Cisco Nexus
- **Virtualisation & Compute:** VMware ESXi / vSphere, bare-metal, NVIDIA GPU (LLM inference)
- **Programming:** Go, Python, gRPC, Bash / Shell scripting
- **Operating Systems:** Linux (Ubuntu, Rocky / RHEL)

## Experience

### Senior DevOps & Platform Engineer — Jibit
*Oct 2021 – Present · Tehran, Iran*

Fintech building payment and financial-infrastructure services.

- Lead and mentor the DevOps and infrastructure team, covering hiring, onboarding, and a KPI-based performance-management system, while staying hands-on across the platform.
- Design and operate a three-site active/active platform across 3 geographically distributed datacenters, providing high availability for mission-critical payment services.
- Run production Kubernetes (RKE2 and Kubespray) on bare-metal and VMware across [# nodes], handling cluster lifecycle, LVM storage provisioning, and node-level operations.
- Operate CockroachDB as the distributed-SQL backbone — multi-region clusters, certificate lifecycle, and batched data migrations — alongside PostgreSQL, MinIO object storage, MongoDB, and Redis.
- Built and maintain a fully self-hosted observability and alerting stack (Prometheus / Thanos, Grafana, Loki, Alertmanager, Elasticsearch / Kibana) and security monitoring with Wazuh and Splunk, replacing legacy Zabbix / Graylog tooling.
- Automate the estate end-to-end with Ansible / AWX, Terraform, and Pulumi; standardised IPAM and configuration management with NetBox, and built custom Linux networking tooling (policy-based routing, iptables, and ipset automation across hosts).
- Lead DevSecOps initiatives: security validation, AI-assisted penetration testing (network, web, and Kubernetes), and vulnerability-assessment maturity.
- Delivered a 1G→25G core network migration (Cisco Nexus 9300) using a zero-downtime, colocated-rack approach; manage CI/CD and the registry layer (GitLab, Harbor, Nexus) across all sites.

### DevOps Engineer — Radar Faratech Hooshmand
*Oct 2020 – Oct 2021 · Tehran, Iran*

Location-data infrastructure startup.

- Introduced and operated Kubernetes orchestration in production for the company's location-data platform.
- Built git-based CI/CD pipelines with webhook automation and autoscaling; managed cloud and on-prem services including VPNs, proxies, caching, CDN, backups, and central logging.
- Administered Linux production VMs and VMware hypervisors; ran monitoring (Grafana) and centralised logging.

### DevOps Engineer — Part Software Group (PartDP)
*Dec 2015 – Oct 2020 · Mashhad, Iran*

Fintech software company.

- Transitioned from systems administration into DevOps, owning application deployment and continuous-delivery pipelines in production.
- Managed Linux production workloads and VMware virtualisation; implemented monitoring (Zabbix, Grafana) and centralised logging (Graylog).
- Administered networking, site-to-site tunnels, and mixed Windows / Active Directory / Exchange environments.

### System Administrator — Farab (MURL) & Mashhad Washer Co.
*2013 – 2015 · Mashhad, Iran*

- Windows Server, Active Directory, Exchange, VoIP, and site-to-site network administration in mixed corporate environments.

## Selected Projects & Tools

- **Chaparkhoneh** — Public service status page: a concurrent gRPC service backed by a ClickHouse store for recording and querying service-health data.
- **Iris** — Alerting and notification platform for the Alertmanager + Grafana stack, with delivery retries and a unified dashboard aggregating all alerts.
- **FinOps cost-allocation platform** — Go + React platform attributing bare-metal infrastructure cost across compute, memory, storage, object storage, and Kubernetes resource requests, with multi-currency reporting.
- **Linux routing & firewall tooling** — Custom tools for policy-based routing and iptables / ipset automation across Linux hosts.

## Languages

- **Persian** — Native
- **English** — Professional working proficiency
