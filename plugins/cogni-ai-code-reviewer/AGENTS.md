# Cogni AI Code Reviewer Plugin

This plugin contains the `cogni-ai-code-reviewer` agent and related skills (including `pre-commit` for quality gates).

## Agents
- [`agents/cogni-ai-code-reviewer.agent.md`](agents/cogni-ai-code-reviewer.agent.md) — Elite autonomous code reviewer for PRs, zero-defect enforcement, security, and architectural validation.
- [`agents/cogni-ai-code-reviewer.agent.mmd`](agents/cogni-ai-code-reviewer.agent.mmd) — Mermaid workflow for the reviewer's initialization, phases, and global protocols.

## Skills
- [`skills/pre-commit/SKILL.md`](skills/pre-commit/SKILL.md) — Comprehensive pre-commit guidance, configuration, custom hooks, diagnostics, and devcontainer integration.

## Usage
Load the reviewer agent for PR reviews. It explicitly loads `github-pr-review`, `github-pr`, `critical-thinking`, `code-review`, `security-review`, and related skills from the collection.

See root `AGENTS-RUNTIME.md` and the agent file for full persona, invariants, and review framework.

**Note**: This plugin follows the organizational plugin pattern. Skills are also available via `gh skill install` (local and remote).
