# Cogni AI Code Reviewer Plugin

This plugin contains the `cogni-ai-code-reviewer` agent and related skills (including `pre-commit` for quality gates).

## Setup & Environment Invariants

- Runs in the context of this plugin directory or when `cogni-ai-code-reviewer` is explicitly loaded.
- Requires the root `AGENTS-RUNTIME.md`, `AGENTS.mmd`, `CONSTRAINTS.mzn`, and `docs/FLOWS.mmd` for global protocols.
- Pre-commit and markdownlint are mandatory for all changes.

## Key Files & Context Injection

- `agents/cogni-ai-code-reviewer.agent.md`: Core persona, cognitive framework, review framework, and directives.
- `agents/cogni-ai-code-reviewer.agent.mmd`: Mermaid state machine for initialization, phases, and global protocols.
- `skills/pre-commit/SKILL.md`: Quality gates and hook configuration.
- Root `AGENTS-RUNTIME.md` and `docs/FLOWS.mmd` are always injected.

## Agent Directives (Contract Style)

**Role**: Elite autonomous code reviewer for PRs with zero-defect enforcement, security, and architectural validation.

**Invariants**:
- MUST load `github-pr-review`, `github-pr`, `critical-thinking`, `code-review`, `security-review`, and related skills.
- MUST follow the review framework in the agent file.
- MUST maintain conceptual integrity and strategic programming imperatives.

**Hardened NEVER Constraints**:
- NEVER approve PRs with unresolved security, architectural drift, or test failures.
- NEVER ignore pre-commit or markdownlint violations.

**Hardened MUST Constraints**:
- MUST run full Waza validation on changed SKILL.md files.
- MUST produce a structured review comment with findings table.

## Testing & Verification Gates

- Waza check on all changed SKILL.md/*.agent.md files.
- Pre-commit run --all-files.
- Markdownlint validation.
- Review against root AGENTS-RUNTIME.md invariants.

## Troubleshooting Matrix

| Symptom | Root Cause | Fix |
|---------|------------|-----|
| Review skips security | Missing `security-review` skill | Explicitly load it in Usage section |
| Waza fails on tokens | SKILL.md >500 tokens | Condense or split to references/ |
| Path errors in agent.md | Incorrect `../docs/FLOWS.mmd` | Use `../../docs/FLOWS.mmd` from plugins/ |

## Final Assurance Gates

- Verify all required sections are present and entropy-pruned.
- Confirm no rubbish or agent-confusing meta notes.
- Validate with `pre-commit run markdownlint -a` and `waza check`.
- Inject full content into every sub-agent context.

## Agents

- [`agents/cogni-ai-code-reviewer.agent.md`](agents/cogni-ai-code-reviewer.agent.md) — Elite autonomous code reviewer for PRs, zero-defect enforcement, security, and architectural validation.
- [`agents/cogni-ai-code-reviewer.agent.mmd`](agents/cogni-ai-code-reviewer.agent.mmd) — Mermaid workflow for the reviewer's initialization, phases, and global protocols.

## Skills

- [`skills/pre-commit/SKILL.md`](skills/pre-commit/SKILL.md) — Comprehensive pre-commit guidance, configuration, custom hooks, diagnostics, and devcontainer integration.

## Usage

Load the reviewer agent for PR reviews. It explicitly loads `github-pr-review`, `github-pr`, `critical-thinking`, `code-review`, `security-review`, and related skills from the collection.

See root `AGENTS-RUNTIME.md` and the agent file for full persona, invariants, and review framework.

**Note**: This plugin follows the organizational plugin pattern. Skills are also available via `gh skill install` (local and remote).
