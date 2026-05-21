# Cogni AI Git Ops Plugin

[![License][license-image]][license-link]

Autonomous Git Operations agent plugin for GitHub Copilot. Specializes in version control, complex git workflows, rebase operations, and repository management.

| | |
|---|---|
| **Description** | Autonomous Git Operations agent with git skills |
| **Contents** | 1 agent, 5 skills |
| **Slash Commands** | [`/cogni-ai-git-ops:git`](../AGENTS.md) <br/> [`/cogni-ai-git-ops:git-expert`](../AGENTS.md) |

## Installation

### Using Copilot CLI

```bash
copilot plugin install Cogni-AI-OU/cogni-ai-copilot-collections:plugins/cogni-ai-git-ops
```

## What's Included

### Agents

- **cogni-ai-git-ops** — Autonomous Git Operations assistant that handles complex repository management tasks, merges, rebases, and history rewriting safely.

### Skills

- **git** — Guide for using git with non-interactive, safe operations.
- **git-expert** — Advanced Git operations including reflog and history manipulation.
- **git-filter-branch** — Extract subdirectories with history using git filter-branch.
- **git-merge** — Guide and safety rules for performing safe git merges.
- **git-rebase** — Advanced Git rebase operations and history cleanup.

## Usage

Once installed, invoke the agent via Copilot CLI:

```bash
copilot run --agent cogni-ai-git-ops "your git operations task"
```

## License

MIT

<!-- Named links -->

[license-image]: https://img.shields.io/badge/License-MIT-blue.svg
[license-link]: https://tldrlegal.com/license/mit-license
