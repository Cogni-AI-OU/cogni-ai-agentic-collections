---
name: kimi-cli-docs
description: >-
  Reference and APIs for retrieving Kimi CLI documentation programmatically for LLMs.
  USE FOR: searching Kimi CLI docs, MoonshotAI models documentation, kimi-cli API reference, tool integrations.
  DO NOT USE FOR: calling live Kimi API endpoints, invoking models directly without CLI.
license: MIT
---

# kimi-cli-docs

<!-- markdownlint-disable MD013 MD023 MD031 MD032 -->

## WHEN TO USE

- **Documentation Search**: Locating specific Kimi CLI or MoonshotAI documentation articles.
- **Article Retrieval**: Fetching the full rendered markdown of a specific Kimi CLI docs page.

## WHEN NOT TO USE

- **Live AI Generation**: Interacting with live Kimi APIs to generate text. Use appropriate API endpoints or SDKs for that.

## References

To fully utilize this skill, you MUST read at least one of the links relevant to the current context:

### Main Sections
- [Configuration Files](https://raw.githubusercontent.com/MoonshotAI/kimi-cli/refs/tags/1.44.0/docs/en/configuration/config-files.md)
- [Data Locations](https://raw.githubusercontent.com/MoonshotAI/kimi-cli/refs/tags/1.44.0/docs/en/configuration/data-locations.md)
- [Environment Variables](https://raw.githubusercontent.com/MoonshotAI/kimi-cli/refs/tags/1.44.0/docs/en/configuration/env-vars.md)
- [Overrides](https://raw.githubusercontent.com/MoonshotAI/kimi-cli/refs/tags/1.44.0/docs/en/configuration/overrides.md)
- [Providers](https://raw.githubusercontent.com/MoonshotAI/kimi-cli/refs/tags/1.44.0/docs/en/configuration/providers.md)
- [Agents Customization](https://raw.githubusercontent.com/MoonshotAI/kimi-cli/refs/tags/1.44.0/docs/en/customization/agents.md)
- [Hooks Customization](https://raw.githubusercontent.com/MoonshotAI/kimi-cli/refs/tags/1.44.0/docs/en/customization/hooks.md)
- [MCP Customization](https://raw.githubusercontent.com/MoonshotAI/kimi-cli/refs/tags/1.44.0/docs/en/customization/mcp.md)
- [Plugins Customization](https://raw.githubusercontent.com/MoonshotAI/kimi-cli/refs/tags/1.44.0/docs/en/customization/plugins.md)
- [Print Mode Customization](https://raw.githubusercontent.com/MoonshotAI/kimi-cli/refs/tags/1.44.0/docs/en/customization/print-mode.md)
- [Skills Customization](https://raw.githubusercontent.com/MoonshotAI/kimi-cli/refs/tags/1.44.0/docs/en/customization/skills.md)
- [Wire Mode Customization](https://raw.githubusercontent.com/MoonshotAI/kimi-cli/refs/tags/1.44.0/docs/en/customization/wire-mode.md)
- [FAQ](https://raw.githubusercontent.com/MoonshotAI/kimi-cli/refs/tags/1.44.0/docs/en/faq.md)
- [Getting Started Guide](https://raw.githubusercontent.com/MoonshotAI/kimi-cli/refs/tags/1.44.0/docs/en/guides/getting-started.md)
- [IDEs Guide](https://raw.githubusercontent.com/MoonshotAI/kimi-cli/refs/tags/1.44.0/docs/en/guides/ides.md)
- [Integrations Guide](https://raw.githubusercontent.com/MoonshotAI/kimi-cli/refs/tags/1.44.0/docs/en/guides/integrations.md)
- [Interaction Guide](https://raw.githubusercontent.com/MoonshotAI/kimi-cli/refs/tags/1.44.0/docs/en/guides/interaction.md)
- [Sessions Guide](https://raw.githubusercontent.com/MoonshotAI/kimi-cli/refs/tags/1.44.0/docs/en/guides/sessions.md)
- [Use Cases Guide](https://raw.githubusercontent.com/MoonshotAI/kimi-cli/refs/tags/1.44.0/docs/en/guides/use-cases.md)
- [Index](https://raw.githubusercontent.com/MoonshotAI/kimi-cli/refs/tags/1.44.0/docs/en/index.md)
- [Keyboard Reference](https://raw.githubusercontent.com/MoonshotAI/kimi-cli/refs/tags/1.44.0/docs/en/reference/keyboard.md)
- [Kimi ACP Reference](https://raw.githubusercontent.com/MoonshotAI/kimi-cli/refs/tags/1.44.0/docs/en/reference/kimi-acp.md)
- [Kimi Command Reference](https://raw.githubusercontent.com/MoonshotAI/kimi-cli/refs/tags/1.44.0/docs/en/reference/kimi-command.md)
- [Kimi Info Reference](https://raw.githubusercontent.com/MoonshotAI/kimi-cli/refs/tags/1.44.0/docs/en/reference/kimi-info.md)
- [Kimi MCP Reference](https://raw.githubusercontent.com/MoonshotAI/kimi-cli/refs/tags/1.44.0/docs/en/reference/kimi-mcp.md)
- [Kimi Term Reference](https://raw.githubusercontent.com/MoonshotAI/kimi-cli/refs/tags/1.44.0/docs/en/reference/kimi-term.md)
- [Kimi Vis Reference](https://raw.githubusercontent.com/MoonshotAI/kimi-cli/refs/tags/1.44.0/docs/en/reference/kimi-vis.md)
- [Kimi Web Reference](https://raw.githubusercontent.com/MoonshotAI/kimi-cli/refs/tags/1.44.0/docs/en/reference/kimi-web.md)
- [Slash Commands Reference](https://raw.githubusercontent.com/MoonshotAI/kimi-cli/refs/tags/1.44.0/docs/en/reference/slash-commands.md)
- [Breaking Changes](https://raw.githubusercontent.com/MoonshotAI/kimi-cli/refs/tags/1.44.0/docs/en/release-notes/breaking-changes.md)
- [Changelog](https://raw.githubusercontent.com/MoonshotAI/kimi-cli/refs/tags/1.44.0/docs/en/release-notes/changelog.md)

### CLI Section

- [ACP Mode](https://raw.githubusercontent.com/google-gemini/gemini-cli/refs/heads/main/docs/cli/acp-mode.md)
- [Auto Memory](https://raw.githubusercontent.com/google-gemini/gemini-cli/refs/heads/main/docs/cli/auto-memory.md)
- [Checkpointing](https://raw.githubusercontent.com/google-gemini/gemini-cli/refs/heads/main/docs/cli/checkpointing.md)
- [CLI Reference](https://raw.githubusercontent.com/google-gemini/gemini-cli/refs/heads/main/docs/cli/cli-reference.md)
- [Creating Skills](https://raw.githubusercontent.com/google-gemini/gemini-cli/refs/heads/main/docs/cli/creating-skills.md)
- [Custom Commands](https://raw.githubusercontent.com/google-gemini/gemini-cli/refs/heads/main/docs/cli/custom-commands.md)
- [Enterprise](https://raw.githubusercontent.com/google-gemini/gemini-cli/refs/heads/main/docs/cli/enterprise.md)
- [Gemini Ignore](https://raw.githubusercontent.com/google-gemini/gemini-cli/refs/heads/main/docs/cli/gemini-ignore.md)
- [Gemini MD](https://raw.githubusercontent.com/google-gemini/gemini-cli/refs/heads/main/docs/cli/gemini-md.md)
- [Generation Settings](https://raw.githubusercontent.com/google-gemini/gemini-cli/refs/heads/main/docs/cli/generation-settings.md)
- [Git Worktrees](https://raw.githubusercontent.com/google-gemini/gemini-cli/refs/heads/main/docs/cli/git-worktrees.md)
- [Headless](https://raw.githubusercontent.com/google-gemini/gemini-cli/refs/heads/main/docs/cli/headless.md)
- [Model Routing](https://raw.githubusercontent.com/google-gemini/gemini-cli/refs/heads/main/docs/cli/model-routing.md)
- [Model Steering](https://raw.githubusercontent.com/google-gemini/gemini-cli/refs/heads/main/docs/cli/model-steering.md)
- [Model](https://raw.githubusercontent.com/google-gemini/gemini-cli/refs/heads/main/docs/cli/model.md)
- [Notifications](https://raw.githubusercontent.com/google-gemini/gemini-cli/refs/heads/main/docs/cli/notifications.md)
- [Plan Mode](https://raw.githubusercontent.com/google-gemini/gemini-cli/refs/heads/main/docs/cli/plan-mode.md)
- [Rewind](https://raw.githubusercontent.com/google-gemini/gemini-cli/refs/heads/main/docs/cli/rewind.md)
- [Sandbox](https://raw.githubusercontent.com/google-gemini/gemini-cli/refs/heads/main/docs/cli/sandbox.md)
- [Session Management](https://raw.githubusercontent.com/google-gemini/gemini-cli/refs/heads/main/docs/cli/session-management.md)
- [Settings](https://raw.githubusercontent.com/google-gemini/gemini-cli/refs/heads/main/docs/cli/settings.md)
- [Skills Best Practices](https://raw.githubusercontent.com/google-gemini/gemini-cli/refs/heads/main/docs/cli/skills-best-practices.md)
- [Skills](https://raw.githubusercontent.com/google-gemini/gemini-cli/refs/heads/main/docs/cli/skills.md)
- [System Prompt](https://raw.githubusercontent.com/google-gemini/gemini-cli/refs/heads/main/docs/cli/system-prompt.md)
- [Telemetry](https://raw.githubusercontent.com/google-gemini/gemini-cli/refs/heads/main/docs/cli/telemetry.md)
- [Themes](https://raw.githubusercontent.com/google-gemini/gemini-cli/refs/heads/main/docs/cli/themes.md)
- [Token Caching](https://raw.githubusercontent.com/google-gemini/gemini-cli/refs/heads/main/docs/cli/token-caching.md)
- [Trusted Folders](https://raw.githubusercontent.com/google-gemini/gemini-cli/refs/heads/main/docs/cli/trusted-folders.md)
- [Using Agent Skills](https://raw.githubusercontent.com/google-gemini/gemini-cli/refs/heads/main/docs/cli/using-agent-skills.md)

#### Tutorials

- [Automation](https://raw.githubusercontent.com/google-gemini/gemini-cli/refs/tags/v0.43.0/docs/cli/tutorials/automation.md)
- [File Management](https://raw.githubusercontent.com/google-gemini/gemini-cli/refs/tags/v0.43.0/docs/cli/tutorials/file-management.md)
- [MCP Setup](https://raw.githubusercontent.com/google-gemini/gemini-cli/refs/tags/v0.43.0/docs/cli/tutorials/mcp-setup.md)
- [Memory Management](https://raw.githubusercontent.com/google-gemini/gemini-cli/refs/tags/v0.43.0/docs/cli/tutorials/memory-management.md)
- [Plan Mode Steering](https://raw.githubusercontent.com/google-gemini/gemini-cli/refs/tags/v0.43.0/docs/cli/tutorials/plan-mode-steering.md)
- [Session Management](https://raw.githubusercontent.com/google-gemini/gemini-cli/refs/tags/v0.43.0/docs/cli/tutorials/session-management.md)
- [Shell Commands](https://raw.githubusercontent.com/google-gemini/gemini-cli/refs/tags/v0.43.0/docs/cli/tutorials/shell-commands.md)
- [Skills Getting Started](https://raw.githubusercontent.com/google-gemini/gemini-cli/refs/tags/v0.43.0/docs/cli/tutorials/skills-getting-started.md)
- [Task Planning](https://raw.githubusercontent.com/google-gemini/gemini-cli/refs/tags/v0.43.0/docs/cli/tutorials/task-planning.md)
- [Web Tools](https://raw.githubusercontent.com/google-gemini/gemini-cli/refs/tags/v0.43.0/docs/cli/tutorials/web-tools.md)

### Core Section

- [Gemma Setup](https://raw.githubusercontent.com/google-gemini/gemini-cli/refs/heads/main/docs/core/gemma-setup.md)
- [Index](https://raw.githubusercontent.com/google-gemini/gemini-cli/refs/heads/main/docs/core/index.md)
- [Local Model Routing](https://raw.githubusercontent.com/google-gemini/gemini-cli/refs/heads/main/docs/core/local-model-routing.md)
- [Remote Agents](https://raw.githubusercontent.com/google-gemini/gemini-cli/refs/heads/main/docs/core/remote-agents.md)
- [Subagents](https://raw.githubusercontent.com/google-gemini/gemini-cli/refs/heads/main/docs/core/subagents.md)

Main Repository: <https://github.com/MoonshotAI/kimi-cli>