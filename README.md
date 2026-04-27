# Claude Code Plugins

Custom agents, skills, and commands for software development workflows.

## Install

```bash
# Add the marketplace
/plugin marketplace add https://github.com/tomtucka/claude-plugins

# Install plugins
/plugin install core@tomtucka-claude-plugins
/plugin install code@tomtucka-claude-plugins

```


## Plugins

| Plugin   | Description                                                                                  |
| -------- | -------------------------------------------------------------------------------------------- |
| **core** | Core workflows: commits, learning, code review, prompts, PRs, writing, and persistent memory |
| **code** | Software engineering agents for backend, frontend, cloud, networking, security, and IaC      |

## Skills

### Core

| Skill             | Description                                                                                  |
| ----------------- | -------------------------------------------------------------------------------------------- |
| `commit-messages` | Conventional commit messages that explain the "why" not just the "what"                      |
| `writing`         | Developer-focused writing: tutorials, how-tos, docs with clear structure                     |

## Agents

### Code

| Agent                    | Description                                                                                  |
| ------------------------ | -------------------------------------------------------------------------------------------- |
| `cloud-architect`        | Multi-cloud infrastructure design (AWS/Azure/GCP/OCI), IaC, FinOps, and migration planning   |
| `deployment-engineer`    | CI/CD pipelines, GitOps workflows, progressive delivery, and zero-downtime deployments       |
| `network-engineer`       | Cloud networking, service mesh, zero-trust, SSL/TLS, CDN, and performance optimization       |
| `security-engineer`      | Security architecture, compliance frameworks, vulnerability management, and incident response |
| `senior-backend-engineer`| Backend development and system design                                                        |
| `senior-web-engineer`    | Frontend and web application development                                                     |
| `terraform-specialist`   | Terraform modules, state management, provider configurations, and drift detection            |

