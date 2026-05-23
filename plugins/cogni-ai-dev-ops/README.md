# Cogni AI DevOps Plugin

[![License][license-image]][license-link]

Elite autonomous DevOps and Site Reliability Engineering plugin. Focuses on task automation, CI/CD pipeline precision, resolving deployment challenges, and enforcing infrastructure-as-code (IaC) scaling invariants.

| | |
|---|---|
| **Description** | Elite autonomous DevOps and site reliability agent |
| **Contents** | 1 agent, 7 skills |
| **Slash Commands** | [`/cogni-ai-dev-ops:devops`](../AGENTS.md) <br/> [`/cogni-ai-dev-ops:molecule`](../AGENTS.md) <br/> [`/cogni-ai-dev-ops:pulumi-cli`](../AGENTS.md) <br/> [`/cogni-ai-dev-ops:docker`](../AGENTS.md) |

## Installation

### GitHub Copilot

```bash
copilot plugin install Cogni-AI-OU/cogni-ai-agentic-collections:plugins/cogni-ai-dev-ops
```

### Claude Code

```bash
claude plugin install cogni-ai-dev-ops@cogni-ai-agentic-collections
```

## What's Included

### Agents

- **cogni-ai-dev-ops** — Elite autonomous site reliability and task automation kernel. Focuses on elimination of toil, infallible CI/CD pipelines, and IaC scaling.

### Skills

- **devops** — Core DevOps and Site Reliability Engineering workflow, covering CI/CD, Infrastructure as Code, observability, and deployment strategies.
- **molecule** — Ansible Molecule testing workflows for developing and testing Ansible roles.
- **pulumi-cli** — Pulumi IaC automation tools for managing stacks and infrastructure deployments.
- **docker** — Docker container management tools for running, managing, and troubleshooting containers and networks.
- **dockerfile** — Expert-level guidance for writing and optimizing Dockerfiles.
- **datadog-docs** — Datadog observability documentation and API reference.
- **pulumi-docs** — Pulumi documentation and resource schema reference.

## Usage

Once installed, invoke the agent via Copilot CLI:

```bash
copilot run --agent cogni-ai-dev-ops "your devops task"
```

## License

MIT

<!-- Named links -->

[license-image]: https://img.shields.io/badge/License-MIT-blue.svg
[license-link]: https://tldrlegal.com/license/mit-license
