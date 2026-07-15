# FAQ

> Home: [README](./README.md)

## How do I find Amazon / PwC / TCS questions fast?

Open [Companies](./companies/README.md) and click the company name.

## How do I study Kubernetes / Terraform / AWS / DR / AIOps?

Open [Topics](./topics/README.md). Topics are grouped for a DevOps study path:

- **Reliability & SRE** — Disaster Recovery, HA, Incident Management, On-Call, Chaos
- **Observability & AIOps** — Monitoring, Prometheus, Grafana, OpenTelemetry, AIOps
- **Cloud / K8s / IaC / CI/CD** — AWS, Azure, GCP, Kubernetes, Terraform, Jenkins, …

## How do I practice Easy vs Hard questions?

Use [Browse by difficulty](./browse/by-difficulty/README.md).

## What are the most repeated questions?

See [Most asked](./browse/by-frequency.md).

## Why are some answers empty?

Extraction can run without answer enrichment (`enrich_answers: false`) to save LLM quota.
Enable enrichment in the crawler config, or [contribute answers](./CONTRIBUTING.md).

## How is this repository updated?

A pipeline crawls LinkedIn interview posts, extracts questions with an LLM, deduplicates them, and regenerates these Markdown pages.
