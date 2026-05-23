# Cogni AI GitHub Ops Plugin

[![License][license-image]][license-link]

Autonomous GitHub Operations agent plugin for GitHub Copilot. Specializes in GitHub workflows, pull requests, issues,
actions, and agentic workflows.

| | |
| --- | --- |
| **Description** | Autonomous GitHub Operations agent with GitHub skills |
| **Contents** | 1 agent, 33 skills |
## Commands (Slash Commands)

| Command | Description |
|---------|-------------|
| [`/cogni-ai-github-ops:gh`](../AGENTS.md) | Load the gh skill -- GitHub CLI (`gh`) operations for issues, PRs, and workflows |
| [`/cogni-ai-github-ops:github`](../AGENTS.md) | Load the github skill -- Guidance on GitHub-specific features and collaborative practices |
| [`/cogni-ai-github-ops:github-actions`](../AGENTS.md) | Load the github-actions skill -- Diagnose GitHub Actions workflow failures |
| [`/cogni-ai-github-ops:github-aw`](../AGENTS.md) | Load the github-aw skill -- Safely update existing GitHub Agentic Workflows (gh-aw) |

## Installation

### GitHub Copilot

```bash
copilot plugin install Cogni-AI-OU/cogni-ai-agentic-collections:plugins/cogni-ai-github-ops
```

### Claude Code

```bash
claude plugin install cogni-ai-github-ops@cogni-ai-agentic-collections
```

## What's Included

### Agents

- **cogni-ai-github-ops** — Autonomous GitHub Operations assistant that handles repository management on GitHub,
  issues, pull requests, workflow runs, and agentic workflows safely and efficiently.

### Skills

- **gh** — GitHub CLI operations for issues, pull requests, workflow runs, reviews, and API.
- **github** — GitHub-specific features and collaborative practices.
- *(And 31 other specialized GitHub skills for actions, agentic workflows, API, codespaces, issues, models, PRs, runs,
  search, topics, and more.)*

## Usage

Once installed, invoke the agent via Copilot CLI:

```bash
copilot run --agent cogni-ai-github-ops "your github operations task"
```

## License

MIT

<!-- Named links -->

[license-image]: https://img.shields.io/badge/License-MIT-blue.svg
[license-link]: https://tldrlegal.com/license/mit-license
