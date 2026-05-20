# AGENTS-RUNTIME.md

Persistent single-source truth for autonomous agent behavior in runtime environments.

## Agents Catalog

This repository is the source of truth for Cogni AI agent files.
Agent files live in the `agents/` directory so they are accessible directly when
this repo is cloned into `.github/agents`.

- [**Cogni AI Architect**](agents/cogni-ai-architect.agent.md):
  Primary autonomous coding agent with critical thinking, robust problem-solving, and context-aware resource management.
- [**Cogni AI DevOps**](agents/cogni-ai-devops.agent.md):
  Elite autonomous DevOps and Site Reliability Engineering agent focusing on task
  automation, CI/CD pipeline precision, and infrastructure-as-code.
- [**Cogni AI Elite**](agents/cogni-ai-elite.agent.md):
  Elite autonomous systems architect engineered for structural perfection and recursive problem decomposition.
- [**Cogni AI Fact Ops**](agents/cogni-ai-fact-ops.agent.md):
  Autonomous fact operator responsible for maintaining canonical fact files and information consistency.
- [**Cogni AI Context7 Ops**](agents/cogni-ai-context7-ops.agent.md):
  Autonomous context gathering agent specialized in retrieving and filtering documentation from the Context7 service.
- [**Cogni AI GitHub Ops**](agents/cogni-ai-github-ops.agent.md):
  Autonomous GitHub Operator responsible for GitHub operations such as
  modifying comments, issues, or discussions on behalf of other agents.
- [**Cogni AI Manager**](agents/cogni-ai-manager.agent.md):
  Autonomous orchestration and coordination manager responsible for routing work
  to specialized agents and ensuring end-to-end completion.
- [**Cogni AI Keeper**](agents/cogni-ai-keeper.agent.md):
  Canonical fact custody and mindmap stewardship kernel for structured knowledge management.
- [**Cogni AI Python Dev**](agents/cogni-ai-python-dev.agent.md):
  Autonomous Python Developer responsible for writing, testing, and debugging Python 3 code.
- [**Cogni AI Code Reviewer**](agents/cogni-ai-code-reviewer.agent.md):
  Elite autonomous code reviewer for PR analysis, quality enforcement, and zero-defect security validation.
- [**Cogni AI Plan Reviewer**](agents/cogni-ai-plan-reviewer.agent.md):
  Elite autonomous architectural reviewer for plan validation and ensuring strategic alignment.
- [**Cogni AI Tester**](agents/cogni-ai-tester.agent.md):
  Autonomous Tester responsible for executing test tasks, ensuring quality, and verifying system behavior.
- [**Cogni AI Weaver**](agents/cogni-ai-weaver.agent.md):
  Canonical flow custody and diagram stewardship kernel specializing in flowchart and dependency memory.
- [**Cogni AI Brain Ops**](agents/cogni-ai-brain-ops.agent.md):
  Autonomous brainstorming agent responsible for gathering facts, describing constraints,
  and architecting suggested plans and tasks.

### Structural Invariant

- **Agents Location**: Agent files live in the `agents/` directory.

## Skills Catalog

This repository is the source of truth for Cogni AI agent skills.
Skill files live in the `skills/` directory so they are accessible directly when
this repo is cloned into `.github/skills`.

- **[agent-log-analysis](skills/agent-log-analysis/SKILL.md)**: Procedures and templates for analyzing agent session logs.
- **[agent-md](skills/agent-md/SKILL.md)**: Syntax and structure reference for custom agent persona files.
- **[agent-md-writer](skills/agent-md-writer/SKILL.md)**: Guidelines and best practices for writing high-performance agent persona files.
- **[agent-skill-md-writer](skills/agent-skill-md-writer/SKILL.md)**: Workflow and guidelines for generating or refining agent skills.
- **[agents-md-writer](skills/agents-md-writer/SKILL.md)**: Autonomous documentation editor responsible for maintaining AGENTS.md files.
- **[agentskills](skills/agentskills/SKILL.md)**: Guidance on the Agent Skills open standard for creating portable Copilot agent skills.
- **[ai-prompt-writer](skills/ai-prompt-writer/SKILL.md)**: Design, review, and optimize secure AI prompts using advanced patterns.
- **[ansible](skills/ansible/SKILL.md)**: How to run and manage Ansible operations safely and prevent hangs.
- **[apache-airflow-api](skills/apache-airflow-api/SKILL.md)**: Execute Apache Airflow Stable REST API queries.
- **[apache-airflow-dags](skills/apache-airflow-dags/SKILL.md)**: Expert-level guide for authoring Apache Airflow DAGs.
- **[astro-cli](skills/astro-cli/SKILL.md)**: Expert-level guide for using the Astro CLI to manage Astronomer Airflow.
- **[astronomer-docs](skills/astronomer-docs/SKILL.md)**: Read and navigate Astronomer documentation using llms.txt context.
- **[awesome-copilot](skills/awesome-copilot/SKILL.md)**: Community-contributed instructions, agents, and skills for GitHub Copilot.
- **[brainstorm](skills/brainstorm/SKILL.md)**: Activate brainstorming protocol to explore options and research.
- **[brainstorm-agent-runs](skills/brainstorm-agent-runs/SKILL.md)**: Identify and analyze agent runs via GitHub API for a given PR.
- **[brainstorm-github-pr](skills/brainstorm-github-pr/SKILL.md)**: Analyze and visualize commit history and CI pipeline checks for a PR.
- **[cat](skills/cat/SKILL.md)**: Guidelines for safely using `cat` and avoiding shell hangs with heredocs.
- **[chrome-devtools](skills/chrome-devtools/SKILL.md)**: Expert-level browser automation and debugging using Chrome DevTools MCP.
- **[claude-docs](skills/claude-docs/SKILL.md)**: Reference and APIs for retrieving Anthropic Claude documentation.
- **[code-review](skills/code-review/SKILL.md)**: Cognitive framework for expert-level code inspection and logic validation.
- **[code-tour](skills/code-tour/SKILL.md)**: Create, update, and maintain VSCode CodeTour (.tour) JSON walkthrough files.
- **[codeql](skills/codeql/SKILL.md)**: Configure and execute CodeQL code scanning analysis.
- **[coding-standard-writer](skills/coding-standard-writer/SKILL.md)**: Write a coding standards document from provided file(s) or folder(s).
- **[context-aware-ops](skills/context-aware-ops/SKILL.md)**: Intelligent resource management with size checking to preserve context.
- **[copilot-cli](skills/copilot-cli/SKILL.md)**: Guidance for installing and using GitHub Copilot CLI.
- **[copilot-docs](skills/copilot-docs/SKILL.md)**: Reference and documentation for GitHub Copilot CLI customization.
- **[critical-thinking](skills/critical-thinking/SKILL.md)**: Engage deep analytical reasoning and adversarial red-teaming.
- **[datadog-agent](skills/datadog-agent/SKILL.md)**: Expert-level guidance for installing and configuring the Datadog Agent.
- **[datadog-api](skills/datadog-api/SKILL.md)**: Execute Datadog API requests to fetch metrics or monitor statuses.
- **[datadog-mcp](skills/datadog-mcp/SKILL.md)**: Query observability data via Datadog MCP.
- **[datadog-monitors](skills/datadog-monitors/SKILL.md)**: Guidelines for designing and troubleshooting Datadog monitor queries.
- **[datadog-pulumi](skills/datadog-pulumi/SKILL.md)**: Create or debug Datadog monitors in Pulumi YAML.
- **[devcontainer](skills/devcontainer/SKILL.md)**: Create and maintain robust devcontainer.json configurations.
- **[dictation](skills/dictation/SKILL.md)**: Apply dictation correction protocols to fix common speech-to-text errors.
- **[direnv](skills/direnv/SKILL.md)**: How to maintain credentials and authenticate using direnv safely.
- **[docker](skills/docker/SKILL.md)**: How to run and manage Docker containers, images, and networks.
- **[dockerfile](skills/dockerfile/SKILL.md)**: Write and optimize Dockerfiles applying multi-stage builds.
- **[docs-review](skills/docs-review/SKILL.md)**: Enforce documentation quality and consistency across architecture and code.
- **[docs-writer](skills/docs-writer/SKILL.md)**: Create and maintain ADRs, runbooks, READMEs, and code docs.
- **[dot-claude](skills/dot-claude/SKILL.md)**: Configure and manage Claude Code (.claude) workspace settings.
- **[dot-github](skills/dot-github/SKILL.md)**: Standardize .github directory structure and agentic patterns.
- **[dotfiles](skills/dotfiles/SKILL.md)**: Reference for repository dotfiles and standard configurations.
- **[editorconfig](skills/editorconfig/SKILL.md)**: Generate comprehensive .editorconfig files based on project analysis.
- **[fact-writer](skills/fact-writer/SKILL.md)**: Guidance for maintaining verifiable project fact files.
- **[gdpr-compliant](skills/gdpr-compliant/SKILL.md)**: Apply GDPR-compliant engineering practices across your codebase.
- **[gh](skills/gh/SKILL.md)**: GitHub CLI (`gh`) operations for issues, PRs, and workflows.
- **[gh-agent-task](skills/gh-agent-task/SKILL.md)**: GitHub CLI (`gh agent-task`) operations for preview agent tasks.
- **[gh-api](skills/gh-api/SKILL.md)**: Advanced GitHub CLI (`gh api`) queries and mutations.
- **[gh-aw](skills/gh-aw/SKILL.md)**: GitHub Agentic Workflows (`gh aw`) operations for repository automation.
- **[gh-aw-compile](skills/gh-aw-compile/SKILL.md)**: Regenerate and post-process all agentic workflows.
- **[gh-aw-firewall](skills/gh-aw-firewall/SKILL.md)**: Use the AWF (Agentic Workflow Firewall) for network isolation.
- **[gh-aw-firewall-debug](skills/gh-aw-firewall-debug/SKILL.md)**: Debug the AWF firewall and troubleshoot network issues.
- **[gh-aw-new](skills/gh-aw-new/SKILL.md)**: Create new GitHub Agentic Workflows from scratch.
- **[gh-aw-troubleshooting](skills/gh-aw-troubleshooting/SKILL.md)**: Diagnose and fix GitHub Agentic Workflows failures.
- **[gh-codespace](skills/gh-codespace/SKILL.md)**: GitHub CLI (`gh codespace`) operations for managing codespaces.
- **[gh-issue](skills/gh-issue/SKILL.md)**: GitHub CLI (`gh issue`) operations for managing issues.
- **[gh-models](skills/gh-models/SKILL.md)**: GitHub CLI models (`gh models`) operations for running AI models.
- **[gh-pr](skills/gh-pr/SKILL.md)**: GitHub CLI (`gh pr`) operations for pull requests and reviews.
- **[gh-run](skills/gh-run/SKILL.md)**: GitHub CLI (`gh run`) operations for workflow runs and logs.
- **[gh-search](skills/gh-search/SKILL.md)**: GitHub CLI (`gh search`) operations for searching code and PRs.
- **[gh-skill](skills/gh-skill/SKILL.md)**: Expert-level guidance on managing agent skills via GitHub CLI.
- **[git](skills/git/SKILL.md)**: Guide for using git with non-interactive, safe operations.
- **[git-expert](skills/git-expert/SKILL.md)**: Advanced Git operations including reflog and history manipulation.
- **[git-filter-branch](skills/git-filter-branch/SKILL.md)**: Extract subdirectories with history using git filter-branch.
- **[git-merge](skills/git-merge/SKILL.md)**: Guide and safety rules for performing safe git merges.
- **[git-rebase](skills/git-rebase/SKILL.md)**: Advanced Git rebase operations and history cleanup.
- **[gitattributes](skills/gitattributes/SKILL.md)**: Define and modify .gitattributes to standardize repo behavior.
- **[github](skills/github/SKILL.md)**: GitHub-specific features and collaborative practices.
- **[github-actions](skills/github-actions/SKILL.md)**: Diagnosing and debugging failing GitHub Actions workflows.
- **[github-aw](skills/github-aw/SKILL.md)**: Safely update existing GitHub Agentic Workflows (gh-aw).
- **[github-aw-agentics](skills/github-aw-agentics/SKILL.md)**: Expert-level guidance for optimizing and building gh-aw.
- **[github-aw-memory](skills/github-aw-memory/SKILL.md)**: Guide for persistent memory strategies in agentic workflows.
- **[github-aw-patterns](skills/github-aw-patterns/SKILL.md)**: Reference for common agentic operational patterns.
- **[github-aw-practices](skills/github-aw-practices/SKILL.md)**: Organizational practices and rollout strategies for gh-aw.
- **[github-aw-syntax](skills/github-aw-syntax/SKILL.md)**: Complete reference for GitHub Agentic Workflows syntax.
- **[github-aw-troubleshooting](skills/github-aw-troubleshooting/SKILL.md)**: Debug and refine gh-aw by analyzing execution logs.
- **[github-docs](skills/github-docs/SKILL.md)**: Reference and APIs for retrieving GitHub documentation.
- **[github-issue](skills/github-issue/SKILL.md)**: Skills for working with GitHub Issues.
- **[github-mcp-server](skills/github-mcp-server/SKILL.md)**: Guide for configuring the GitHub MCP server.
- **[github-pr](skills/github-pr/SKILL.md)**: Skills for working with changes on a GitHub Pull Request.
- **[github-pr-review](skills/github-pr-review/SKILL.md)**: Comprehensive PR review workflow for quality and security.
- **[github-pulumi](skills/github-pulumi/SKILL.md)**: Manage GitHub resources with Pulumi CLI.
- **[github-script](skills/github-script/SKILL.md)**: Advanced use cases for actions/github-script.
- **[github-topics](skills/github-topics/SKILL.md)**: Search GitHub repositories by topics and keywords.
- **[github](skills/github/SKILL.md)**: GitHub-specific features and collaborative practices.
- **[llmstxt](skills/llmstxt/SKILL.md)**: Standard for using /llms.txt to provide context to LLMs.
- **[lsp-setup](skills/lsp-setup/SKILL.md)**: Enable code intelligence by configuring LSP servers.
- **[mcp-cli](skills/mcp-cli/SKILL.md)**: Interface for MCP (Model Context Protocol) servers via CLI.
- **[mermaid](skills/mermaid/SKILL.md)**: Guide for creating and maintaining stable Mermaid.js diagrams.
- **[mermaid-beta](skills/mermaid-beta/SKILL.md)**: Guide for experimental Mermaid.js beta diagrams.
- **[minizinc](skills/minizinc/SKILL.md)**: Expert MiniZinc modeling for constraint satisfaction.
- **[molecule](skills/molecule/SKILL.md)**: Molecule testing workflows for Ansible roles.
- **[mot](skills/mot/SKILL.md)**: Evaluate and classify models based on Model Openness Framework.
- **[name-com-docs](skills/name-com-docs/SKILL.md)**: Reference for name.com Core API documentation.
- **[npx-skills](skills/npx-skills/SKILL.md)**: Install and manage agent skills using the npx skills CLI.
- **[ollama-cli](skills/ollama-cli/SKILL.md)**: Execute and manage local LLMs using the ollama CLI.
- **[opencode](skills/opencode/SKILL.md)**: Manage OpenCode configuration and access the OpenCode Zen API.
- **[out-yaml](skills/out-yaml/SKILL.md)**: Instructs the agent to produce output strictly in valid YAML.
- **[pdf](skills/pdf/SKILL.md)**: PDF file inspection, editing, and lossless size reduction.
- **[pipenv](skills/pipenv/SKILL.md)**: Manage Python dependencies and environments using pipenv.
- **[pipfile](skills/pipfile/SKILL.md)**: Create and manage Python dependencies via Pipfile.
- **[pre-commit](skills/pre-commit/SKILL.md)**: Using pre-commit to validate code formatting and security.
- **[pulumi-cli](skills/pulumi-cli/SKILL.md)**: Execute Pulumi CLI commands for stack management.
- **[pulumi-docs](skills/pulumi-docs/SKILL.md)**: Access and fetch Pulumi documentation and registry schemas.
- **[python](skills/python/SKILL.md)**: Expert Python skill for writing and testing idiomatic code.
- **[python-cli](skills/python-cli/SKILL.md)**: Execute Python inline scripts for data transformation.
- **[report-writer](skills/report-writer/SKILL.md)**: Generate comprehensive system audit reports.
- **[rfc2119](skills/rfc2119/SKILL.md)**: Enforce correct usage of RFC 2119 requirement keywords.
- **[robust-commands](skills/robust-commands/SKILL.md)**: Resilient command execution with automatic fallbacks.
- **[sbom](skills/sbom/SKILL.md)**: Guidelines for generating a Software Bill of Materials (SBOM).
- **[security-audit](skills/security-audit/SKILL.md)**: Procedures for performing deep security audits and assessments.
- **[security-review](skills/security-review/SKILL.md)**: Lightweight security review focused on Pull Requests.
- **[sed](skills/sed/SKILL.md)**: Fast, non-interactive text stream editing using sed.
- **[shell](skills/shell/SKILL.md)**: Efficient shell command execution with timing and best practices.
- **[agent-skill-md-writer](skills/agent-skill-md-writer/SKILL.md)**: Generate or update SKILL.md files for coding agents.
- **[subagent-task](skills/subagent-task/SKILL.md)**: Guidance and protocols for spawning sub-agents via the task tool.
- **[tdd](skills/tdd/SKILL.md)**: Procedures for test engineering and the TDD lifecycle.
- **[tester](skills/tester/SKILL.md)**: Elite autonomous test engineering kernel for proving correctness.
- **[unicode](skills/unicode/SKILL.md)**: Reference for Unicode character hex ranges and regex blocks.
- **[vim-ex](skills/vim-ex/SKILL.md)**: Non-interactive file editing with Vim Ex mode.
- **[yaml](skills/yaml/SKILL.md)**: Generic guidelines for YAML formatting and linting.
- **[yq](skills/yq/SKILL.md)**: Parse, edit, and transform YAML files using yq.

### Structural Invariant

- **Agents Location**: Agent files live in the `agents/` directory.
- **Skills Location**: Skill files live in the `skills/` directory.

## Subagent Delegation

- **Spawning Sub-agents**:
  If subagent delegation is enabled in the runtime, agents are encouraged to spawn new
  sub-agents to handle complex, multi-step, or parallelizable tasks.
  This promotes modular problem-solving and efficient resource utilization.
