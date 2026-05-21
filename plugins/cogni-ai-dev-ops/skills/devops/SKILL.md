---
name: devops
description: 'Core DevOps and Site Reliability Engineering workflow, covering CI/CD, Infrastructure as Code, observability, and deployment strategies.'
license: MIT
---

# DevOps Workflow

<!-- markdownlint-disable MD013 MD023 MD031 MD032 -->

## When to Use

- When automating infrastructure deployment.
- When configuring CI/CD pipelines (GitHub Actions, etc.).
- When resolving deployment and operational issues.
- When setting up observability, logging, and monitoring tools.

## Core Principles

- **Infrastructure as Code (IaC)**: Manage all infrastructure using declarative code.
- **Continuous Integration / Continuous Deployment**: Automate testing and deployment to reduce manual toil and errors.
- **Observability**: Ensure systems are measurable through metrics, logs, and traces.
- **Idempotency**: Automation scripts must yield the same state on repeated runs.

## Step-by-Step Workflows

### 1. Analyze Infrastructure Requirements

- Review scaling, security, and networking constraints.
- Determine the appropriate IaC tools.

### 2. Pipeline Design

- Create atomic, independent stages for build, test, and deploy.
- Implement security gates (e.g., secret scanning, linting).

### 3. Execution and Testing

- Write idempotent automation scripts.
- Validate via local testing or staging environments before production rollouts.
