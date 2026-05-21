---
name: datadog-docs
description: 'Reference and APIs for retrieving Datadog documentation programmatically for LLMs. You MUST load this skill when asked to search or retrieve Datadog documentation.'
license: MIT
---

# Skill: datadog-docs

<!-- markdownlint-disable MD013 MD023 MD031 MD032 -->

## When to Use

- **Documentation Search**: Locating specific Datadog documentation articles or reference materials.
- **Article Retrieval**: Fetching Datadog documentation using the provided LLM-optimized endpoints.

## When Not to Use

- **API Interaction**: When you need to interact with the Datadog API to fetch live objects or metrics. Use `datadog-api` instead.
- **Agent Configuration**: When you need to configure or install the Datadog Agent. Use `datadog-agent` instead.

## Core Process

1. **Identify the Need**: Determine what Datadog documentation is needed.
2. **Access References**: Use the provided `llms.txt` to access the documentation links.

## References

- <https://docs.datadoghq.com/llms.txt> - The official Datadog documentation curated for LLMs.

## Related Skills

- **datadog-api**:
  You MUST load this skill when interacting with the Datadog API.
- **datadog-agent**:
  You MUST load this skill when configuring the Datadog Agent.
