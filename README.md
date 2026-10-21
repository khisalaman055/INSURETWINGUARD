# INSURETWINGUARD

**Production Engineering | DevOps | SRE | Cloud | Platform Engineering**

INSURETWINGUARD is a hands-on production engineering lab focused on building, operating, troubleshooting, securing, and recovering distributed systems.

## Project Goals

- Linux production troubleshooting and performance analysis
- AWS infrastructure and Terraform
- Docker, Kubernetes, and Amazon EKS
- Kafka platform operations and reliability
- CI/CD, GitOps, and DevSecOps
- Observability, SLOs, incident response, and disaster recovery
- Evidence-based root cause analysis and automation

## Production Responsibility Workflow

Every lab follows this cycle:

1. **Build** — create or configure the component.
2. **Operate** — capture baseline health and performance.
3. **Break** — introduce a controlled, reversible failure.
4. **Investigate** — collect evidence and test hypotheses.
5. **Recover** — mitigate safely.
6. **Verify** — confirm recovery using measurable evidence.
7. **Prevent** — automate or document safeguards.
8. **Explain** — record the root cause and lessons learned.

## Learning Roadmap

| Phase | Focus |
|---|---|
| 1 | Linux, networking, Git, and AWS fundamentals |
| 2 | Docker, CI/CD, and Terraform |
| 3 | Kubernetes workloads, networking, and storage |
| 4 | Kubernetes L3 operations, security, and EKS |
| 5 | Kafka architecture, KRaft, and reliability |
| 6 | Kafka on Kubernetes, Helm, Argo CD, and platform engineering |
| 7 | Observability, SRE, SLOs, and disaster recovery |
| 8 | Production war rooms, RCA, and final assessment |

The roadmap is structured around a 16-week practical study plan. Competencies are revisited when assessments reveal gaps.

## Current Progress

**Day 1 — Linux Production Engineering**

Completed activities:

- Captured the Linux environment baseline.
- Inspected uptime, load average, memory, filesystem, and inode usage.
- Identified a deliberately created CPU-intensive Python process.
- Investigated its PID, CPU usage, memory usage, and process state.
- Sent SIGTERM and verified process termination.
- Documented the incident in `incidents/INC-D1-001.md`.

**Incident:** `INC-D1-001 — Controlled CPU Saturation`

This was a local Ubuntu/WSL2 training simulation, not a production outage.

## Repository Structure

```text
INSURETWINGUARD/
├── README.md
├── docs/
│   └── day1-baseline.txt
├── incidents/
│   └── INC-D1-001.md
├── runbooks/
├── logs/
└── scripts/
