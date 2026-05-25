---
name: gemini-cli-docs
description: 'USE FOR: Reading, searching, or referencing Gemini CLI documentation (docs directory, CLI reference, tutorials, hooks, extensions, tools, configuration, MCP, and IDE integration guides). DO NOT USE FOR: Operating the Gemini CLI itself, writing Gemini CLI plugins or extensions, or setting up Gemini authentication and credentials. You MUST load this skill when asked to read, search, or retrieve Gemini CLI documentation.'
license: MIT
---

# Gemini CLI Docs

<!-- markdownlint-disable MD013 MD023 MD031 MD032 -->

## When to Use

- **Documentation Lookup**: Finding specific Gemini CLI doc pages for features, CLI commands, or configuration.
- **Tutorial Reference**: Fetching how-to guides on automation, MCP setup, skills, shell commands, and memory management.
- **Architecture Reference**: Looking up hooks/extensions specs, tool definitions, IDE companion spec, or policy engine docs.

## When Not to Use

- **Running Gemini CLI Commands**: Interacting with a live `gemini` CLI session — use direct CLI execution instead.
- **Writing Extensions/Skills**: Authoring new Gemini CLI plugins, hooks, or agent skills — use the appropriate development skill.

## Core Process

1. **Identify the Topic**: Determine the docs area (CLI reference, hooks, extensions, tools, tutorials, get-started, admin, reference, or core).
2. **Fetch Doc Content**: Build the URL path using the pattern:
   ```text
   https://raw.githubusercontent.com/google-gemini/gemini-cli/main/docs/<area>/<filename>
   ```
3. **Process Content**: Extract relevant information to answer the query.

Use `webfetch` or equivalent to retrieve raw markdown files.

## Docs Path Reference

`docs/<area>/` — sub-directories and typical files:

| Area | Key Files |
| --- | --- |
| `(root)` | CONTRIBUTING.md, index.md, local-development.md, npm.md, releases.md |
| `admin/` | enterprise-controls.md |
| `cli/` | CLI reference, skills, model-routing, sandbox, session-management, plan-mode, generation-settings, themes, system-prompt, token-caching, trusted-folders, and more |
| `cli/tutorials/` | automation.md, mcp-setup.md, shell-commands.md, skills-getting-started.md, memory-management.md, task-planning.md, web-tools.md |
| `core/` | gemma-setup.md, local-model-routing.md, remote-agents.md, subagents.md |
| `extensions/` | best-practices.md, reference.md, releasing.md, writing-extensions.md |
| `get-started/` | authentication.mdx, installation.mdx, gemini-3.md |
| `hooks/` | best-practices.md, reference.md, writing-hooks.md |
| `ide-integration/` | ide-companion-spec.md |
| `reference/` | commands.md, configuration.md, tools.md, keyboard-shortcuts.md, policy-engine.md |
| `resources/` | faq.md, troubleshooting.md, quota-and-pricing.md, uninstall.md |
| `tools/` | activate-skill.md, file-system.md, mcp-server.md, memory.md, shell.md, web-fetch.md, planning.md, and more |

## References

### Docs (root)
- [CONTRIBUTING.md](https://raw.githubusercontent.com/google-gemini/gemini-cli/main/docs/CONTRIBUTING.md)
- [index.md](https://raw.githubusercontent.com/google-gemini/gemini-cli/main/docs/index.md)
- [local-development.md](https://raw.githubusercontent.com/google-gemini/gemini-cli/main/docs/local-development.md)
- [npm.md](https://raw.githubusercontent.com/google-gemini/gemini-cli/main/docs/npm.md)
- [releases.md](https://raw.githubusercontent.com/google-gemini/gemini-cli/main/docs/releases.md)

### Admin
- [enterprise-controls.md](https://raw.githubusercontent.com/google-gemini/gemini-cli/main/docs/admin/enterprise-controls.md)

### CLI
- [cli-reference.md](https://raw.githubusercontent.com/google-gemini/gemini-cli/main/docs/cli/cli-reference.md)
- [creating-skills.md](https://raw.githubusercontent.com/google-gemini/gemini-cli/main/docs/cli/creating-skills.md)
- [generation-settings.md](https://raw.githubusercontent.com/google-gemini/gemini-cli/main/docs/cli/generation-settings.md)
- [model-routing.md](https://raw.githubusercontent.com/google-gemini/gemini-cli/main/docs/cli/model-routing.md)
- [plan-mode.md](https://raw.githubusercontent.com/google-gemini/gemini-cli/main/docs/cli/plan-mode.md)
- [sandbox.md](https://raw.githubusercontent.com/google-gemini/gemini-cli/main/docs/cli/sandbox.md)
- [session-management.md](https://raw.githubusercontent.com/google-gemini/gemini-cli/main/docs/cli/session-management.md)
- [skills.md](https://raw.githubusercontent.com/google-gemini/gemini-cli/main/docs/cli/skills.md)
- [system-prompt.md](https://raw.githubusercontent.com/google-gemini/gemini-cli/main/docs/cli/system-prompt.md)
- [themes.md](https://raw.githubusercontent.com/google-gemini/gemini-cli/main/docs/cli/themes.md)
- [token-caching.md](https://raw.githubusercontent.com/google-gemini/gemini-cli/main/docs/cli/token-caching.md)
- [trusted-folders.md](https://raw.githubusercontent.com/google-gemini/gemini-cli/main/docs/cli/trusted-folders.md)

### CLI Tutorials
- [automation.md](https://raw.githubusercontent.com/google-gemini/gemini-cli/main/docs/cli/tutorials/automation.md)
- [mcp-setup.md](https://raw.githubusercontent.com/google-gemini/gemini-cli/main/docs/cli/tutorials/mcp-setup.md)
- [memory-management.md](https://raw.githubusercontent.com/google-gemini/gemini-cli/main/docs/cli/tutorials/memory-management.md)
- [shell-commands.md](https://raw.githubusercontent.com/google-gemini/gemini-cli/main/docs/cli/tutorials/shell-commands.md)
- [skills-getting-started.md](https://raw.githubusercontent.com/google-gemini/gemini-cli/main/docs/cli/tutorials/skills-getting-started.md)
- [task-planning.md](https://raw.githubusercontent.com/google-gemini/gemini-cli/main/docs/cli/tutorials/task-planning.md)
- [web-tools.md](https://raw.githubusercontent.com/google-gemini/gemini-cli/main/docs/cli/tutorials/web-tools.md)

### Core
- [gemma-setup.md](https://raw.githubusercontent.com/google-gemini/gemini-cli/main/docs/core/gemma-setup.md)
- [local-model-routing.md](https://raw.githubusercontent.com/google-gemini/gemini-cli/main/docs/core/local-model-routing.md)
- [remote-agents.md](https://raw.githubusercontent.com/google-gemini/gemini-cli/main/docs/core/remote-agents.md)
- [subagents.md](https://raw.githubusercontent.com/google-gemini/gemini-cli/main/docs/core/subagents.md)

### Extensions
- [best-practices.md](https://raw.githubusercontent.com/google-gemini/gemini-cli/main/docs/extensions/best-practices.md)
- [reference.md](https://raw.githubusercontent.com/google-gemini/gemini-cli/main/docs/extensions/reference.md)
- [releasing.md](https://raw.githubusercontent.com/google-gemini/gemini-cli/main/docs/extensions/releasing.md)
- [writing-extensions.md](https://raw.githubusercontent.com/google-gemini/gemini-cli/main/docs/extensions/writing-extensions.md)

### Get Started
- [authentication.mdx](https://raw.githubusercontent.com/google-gemini/gemini-cli/main/docs/get-started/authentication.mdx)
- [installation.mdx](https://raw.githubusercontent.com/google-gemini/gemini-cli/main/docs/get-started/installation.mdx)
- [gemini-3.md](https://raw.githubusercontent.com/google-gemini/gemini-cli/main/docs/get-started/gemini-3.md)

### Hooks
- [best-practices.md](https://raw.githubusercontent.com/google-gemini/gemini-cli/main/docs/hooks/best-practices.md)
- [reference.md](https://raw.githubusercontent.com/google-gemini/gemini-cli/main/docs/hooks/reference.md)
- [writing-hooks.md](https://raw.githubusercontent.com/google-gemini/gemini-cli/main/docs/hooks/writing-hooks.md)

### IDE Integration
- [ide-companion-spec.md](https://raw.githubusercontent.com/google-gemini/gemini-cli/main/docs/ide-integration/ide-companion-spec.md)

### Reference
- [commands.md](https://raw.githubusercontent.com/google-gemini/gemini-cli/main/docs/reference/commands.md)
- [configuration.md](https://raw.githubusercontent.com/google-gemini/gemini-cli/main/docs/reference/configuration.md)
- [keyboard-shortcuts.md](https://raw.githubusercontent.com/google-gemini/gemini-cli/main/docs/reference/keyboard-shortcuts.md)
- [policy-engine.md](https://raw.githubusercontent.com/google-gemini/gemini-cli/main/docs/reference/policy-engine.md)
- [tools.md](https://raw.githubusercontent.com/google-gemini/gemini-cli/main/docs/reference/tools.md)

### Resources
- [faq.md](https://raw.githubusercontent.com/google-gemini/gemini-cli/main/docs/resources/faq.md)
- [quota-and-pricing.md](https://raw.githubusercontent.com/google-gemini/gemini-cli/main/docs/resources/quota-and-pricing.md)
- [troubleshooting.md](https://raw.githubusercontent.com/google-gemini/gemini-cli/main/docs/resources/troubleshooting.md)
- [uninstall.md](https://raw.githubusercontent.com/google-gemini/gemini-cli/main/docs/resources/uninstall.md)

### Tools
- [activate-skill.md](https://raw.githubusercontent.com/google-gemini/gemini-cli/main/docs/tools/activate-skill.md)
- [file-system.md](https://raw.githubusercontent.com/google-gemini/gemini-cli/main/docs/tools/file-system.md)
- [mcp-server.md](https://raw.githubusercontent.com/google-gemini/gemini-cli/main/docs/tools/mcp-server.md)
- [memory.md](https://raw.githubusercontent.com/google-gemini/gemini-cli/main/docs/tools/memory.md)
- [planning.md](https://raw.githubusercontent.com/google-gemini/gemini-cli/main/docs/tools/planning.md)
- [shell.md](https://raw.githubusercontent.com/google-gemini/gemini-cli/main/docs/tools/shell.md)
- [web-fetch.md](https://raw.githubusercontent.com/google-gemini/gemini-cli/main/docs/tools/web-fetch.md)

### Repository
- [Gemini CLI Repository](https://github.com/google-gemini/gemini-cli)
