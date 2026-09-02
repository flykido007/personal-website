# Draft (sanitized) — 2026-09-01
Source: Drive Work/Resume Google Doc "Draft". Internal product names, order volumes, incident counts, and component wiring stripped because this lands in a public repo.

## GenAI document intelligence for pharmacy operations
- Designed GCP + Gemini document-intelligence workflows to classify and organize high-volume inbound fax and digital documents for pharmacy operations.
- Turned model output into an operator workflow with duplicate detection so staff can search, compare, and clear same-day work faster.

## AI-orchestrated Kubernetes store rollout
- Used AI agent workflows (skills/rules) to design and generate GitLab pipelines and Ansible automation for the on-prem VMware to vanilla Kubernetes + GCP store migration.
- Wired FluxCD GitOps from a central management cluster so store rebuilds follow one repeatable path.

## AI-engineered delivery for platform migrations
- Built an AI delivery system (agent skills, rules, MCP toolchains) that orchestrates tickets, repo changes, docs, and GitLab jobs across store-platform SRE repositories.
- Applied it to store-scale database migration (DB2 to Postgres) and messaging migration (IBM MQ to ActiveMQ) with convert/cutover/rollback pipelines; human review at production cutover gates.

## AI-assisted incident intelligence and store recovery
- Built AI-assisted incident intelligence over historical store-platform incidents: pattern analysis, RCA playbooks, prioritized remediation.
- Authored Kubernetes store-down recovery runbooks and GitLab recovery jobs so on-call can confirm reachability from a pipeline.
- Used AI-assisted debugging during a large multi-store release to trace monitoring failures across GitLab, Pub/Sub, and Grafana and restore stuck pipeline jobs.
