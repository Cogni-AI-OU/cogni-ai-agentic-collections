# Plugins

Portable bundles that package agents, skills, and configuration together for easy installation.

## Available Plugins

- **[cogni-ai-coder](cogni-ai-coder/)** — Autonomous coding agent with coding and critical-thinking skills (1 agent, 2 skills)
- **[cogni-ai-developer](cogni-ai-developer/)** — Autonomous developer agent with development, tdd,
  critical-thinking, and npm-cli skills (1 agent, 4 skills)
- **[cogni-ai-git-ops](cogni-ai-git-ops/)** — Autonomous git operations agent with git skills (1 agent, 2 skills)
- **[cogni-ai-github-ops](cogni-ai-github-ops/)** — Autonomous GitHub operations agent with github skills
  (1 agent, 33 skills)
- **[cogni-ai-programmer](cogni-ai-programmer/)** — Autonomous programmer agent with programming, python,
  threejs-llms, react-llms, nextjs-llms, and reactnative-llms skills (1 agent, 6 skills)
- **[cogni-ai-architect](cogni-ai-architect/)** — Elite autonomous architect agent with software-architecture skill
  for structural perfection and neurosymbolic verification (1 agent, 1 skill)
- **[cogni-ai-tester](cogni-ai-tester/)** — Elite autonomous test engineering agent with testing skill for proving
  software correctness and preventing regressions (1 agent, 1 skill)
- **[cogni-ai-dev-ops](cogni-ai-dev-ops/)** — Elite autonomous DevOps and site reliability agent with devops,
  molecule, pulumi, datadog, and docker skills (1 agent, 7 skills)

## Installation

Register this repository as a plugin marketplace, then install by plugin name:

### GitHub Copilot

```bash
# Register this collection as a marketplace
copilot plugin marketplace add Cogni-AI-OU/cogni-ai-agentic-collections
# Install a specific plugin by name
copilot plugin install cogni-ai-architect@cogni-ai-agentic-collections
```

### Claude Code

```bash
# Register this collection as a marketplace
claude plugin marketplace add Cogni-AI-OU/cogni-ai-agentic-collections
# Install a specific plugin by name
claude plugin install cogni-ai-architect@cogni-ai-agentic-collections
```

Each plugin includes a `README.md` with detailed installation and usage instructions.
