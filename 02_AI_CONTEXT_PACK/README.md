# AI Context Pack

## Pack Identity

- Upstream: https://github.com/pydantic/pydantic-ai
- Pack type: AI Agent Framework Context Pack
- Doramagic canonical: https://doramagic.ai/en/projects/pydantic-ai/
- Relationship: independent pack; not affiliated or endorsed unless explicitly stated.

## Operating Rules

- Evidence first.
- No official endorsement claim.
- Run evals before claiming success.
- Use pitfall and risk files for recovery.

## Host Files

- `../AGENTS.md`
- `../CLAUDE.md`

## Doramagic Source Extract

# pydantic-ai - Doramagic AI Context Pack

> Purpose: pre-work context for the user's host AI. This pack does not prove that the project has been installed, run, or validated.

## Project

- canonical_name: `pydantic/pydantic-ai`
- capability: AI Agent Framework, the Pydantic way
- expected_user_outcome: AI Agent Framework, the Pydantic way

## Operating Boundaries

- Do not claim that the project has been installed, run, called through an API, or used on local files unless separate evidence proves it.
- Project facts must come from repo evidence, Claim Graph, or explicit source references.
- When a capability is not verified, mark it as unverified instead of completing it as fact.
- publish_status: `publishable`
- blocking_gaps: none

---

## Doramagic Context Augmentation

The following sections strengthen the repository context for a host AI. Human Manual data is a reading route, and pitfall notes become operating constraints.

## Human Manual Outline

Usage rule: this is only a reading route and salience signal, not factual authority. Concrete claims must still return to repo evidence or Claim Graph.

Host AI hard rules:
- Do not treat page titles, section order, summaries, or importance values as factual project evidence.
- When explaining the Human Manual outline, state that it is only a reading route or salience signal.
- Capability, installation, compatibility, runtime state, and risk claims must cite repo evidence, source paths, or Claim Graph.

- **Overview & Core Agent System**: importance `high`
  - source_paths: pydantic_ai_slim/pydantic_ai/agent/__init__.py, pydantic_ai_slim/pydantic_ai/agent/abstract.py, pydantic_ai_slim/pydantic_ai/agent/wrapper.py, pydantic_ai_slim/pydantic_ai/agent/spec.py, pydantic_ai_slim/pydantic_ai/capabilities/__init__.py
- **Models, Providers & Structured Outputs**: importance `high`
  - source_paths: pydantic_ai_slim/pydantic_ai/models/__init__.py, pydantic_ai_slim/pydantic_ai/models/openai.py, pydantic_ai_slim/pydantic_ai/models/anthropic.py, pydantic_ai_slim/pydantic_ai/models/google.py, pydantic_ai_slim/pydantic_ai/models/bedrock.py
- **Tools, Toolsets, MCP & Durable Execution**: importance `high`
  - source_paths: pydantic_ai_slim/pydantic_ai/tools.py, pydantic_ai_slim/pydantic_ai/toolsets/__init__.py, pydantic_ai_slim/pydantic_ai/toolsets/abstract.py, pydantic_ai_slim/pydantic_ai/toolsets/function.py, pydantic_ai_slim/pydantic_ai/toolsets/combined.py
- **UI Adapters, Embeddings & Evaluation**: importance `high`
  - source_paths: pydantic_ai_slim/pydantic_ai/ui/__init__.py, pydantic_ai_slim/pydantic_ai/ui/_adapter.py, pydantic_ai_slim/pydantic_ai/ui/vercel_ai/__init__.py, pydantic_ai_slim/pydantic_ai/ui/vercel_ai/_adapter.py, pydantic_ai_slim/pydantic_ai/ui/vercel_ai/_event_stream.py

## Repo Inspection Evidence

- repo_clone_verified: true
- repo_inspection_verified: true
- repo_commit: `a4973543ae99f66c6f534113079c3bb25cbbb62d`
- inspected_files: `uv.lock`, `pyproject.toml`, `README.md`, `docs/agent.md`, `docs/coding-agent-skills.md`, `docs/input.md`, `docs/nav.json`, `docs/thinking.md`, `docs/common-tools.md`, `docs/capabilities.md`, `docs/cli.md`, `docs/changelog.md`, `docs/embeddings.md`, `docs/troubleshooting.md`, `docs/extensibility.md`, `docs/agent-spec.md`, `docs/native-tools.md`, `docs/third-party-tools.md`, `docs/dependencies.md`, `docs/output.md`

Host AI hard rules:
- Without repo_clone_verified=true, do not claim that the source code has been read.
- Without repo_inspection_verified=true, do not write README, docs, or package-file conclusions as facts.
- Without quick_start_verified=true, do not claim that the Quick Start path has run successfully.

## Doramagic Pitfall Constraints

These rules come from Doramagic discovery, validation, or compilation findings. The host AI must treat them as operating constraints, not background notes.

### Constraint 1: Installation risk requires verification

- Trigger: Project evidence flags a installation risk. Review the linked source before relying on this workflow.
- Host AI rule: Reproduce the official install and quickstart path in an isolated environment.
- Why it matters: May increase setup, validation, or first-run risk for the user.
- Evidence: community_evidence:github | https://github.com/pydantic/pydantic-ai/issues/530
- Hard boundary: Do not present this pitfall as solved, verified, or ignorable unless later evidence explicitly closes it.

### Constraint 2: Installation risk requires verification

- Trigger: Project evidence flags a installation risk. Review the linked source before relying on this workflow.
- Host AI rule: Reproduce the official install and quickstart path in an isolated environment.
- Why it matters: May increase setup, validation, or first-run risk for the user.
- Evidence: community_evidence:github | https://github.com/pydantic/pydantic-ai/issues/4580
- Hard boundary: Do not present this pitfall as solved, verified, or ignorable unless later evidence explicitly closes it.

### Constraint 3: Installation risk requires verification

- Trigger: Project evidence flags a installation risk. Review the linked source before relying on this workflow.
- Host AI rule: Reproduce the official install and quickstart path in an isolated environment.
- Why it matters: May increase setup, validation, or first-run risk for the user.
- Evidence: community_evidence:github | https://github.com/pydantic/pydantic-ai/issues/4773
- Hard boundary: Do not present this pitfall as solved, verified, or ignorable unless later evidence explicitly closes it.

### Constraint 4: Installation risk requires verification

- Trigger: Project evidence flags a installation risk. Review the linked source before relying on this workflow.
- Host AI rule: Reproduce the official install and quickstart path in an isolated environment.
- Why it matters: May increase setup, validation, or first-run risk for the user.
- Evidence: community_evidence:github | https://github.com/pydantic/pydantic-ai/issues/5764
- Hard boundary: Do not present this pitfall as solved, verified, or ignorable unless later evidence explicitly closes it.

### Constraint 5: Configuration risk requires verification

- Trigger: Project evidence flags a configuration risk. Review the linked source before relying on this workflow.
- Host AI rule: Reproduce the official install and quickstart path in an isolated environment.
- Why it matters: May increase setup, validation, or first-run risk for the user.
- Evidence: community_evidence:github | https://github.com/pydantic/pydantic-ai/issues/5755
- Hard boundary: Do not present this pitfall as solved, verified, or ignorable unless later evidence explicitly closes it.

### Constraint 6: Configuration risk requires verification

- Trigger: Project evidence flags a configuration risk. Review the linked source before relying on this workflow.
- Host AI rule: Reproduce the official install and quickstart path in an isolated environment.
- Why it matters: May increase setup, validation, or first-run risk for the user.
- Evidence: community_evidence:github | https://github.com/pydantic/pydantic-ai/issues/5760
- Hard boundary: Do not present this pitfall as solved, verified, or ignorable unless later evidence explicitly closes it.

### Constraint 7: Runtime risk requires verification

- Trigger: Project evidence flags a runtime risk. Review the linked source before relying on this workflow.
- Host AI rule: Reproduce the official install and quickstart path in an isolated environment.
- Why it matters: May increase setup, validation, or first-run risk for the user.
- Evidence: community_evidence:github | https://github.com/pydantic/pydantic-ai/issues/5160
- Hard boundary: Do not present this pitfall as solved, verified, or ignorable unless later evidence explicitly closes it.

### Constraint 8: Maintenance risk requires verification

- Trigger: Project evidence flags a maintenance risk. Review the linked source before relying on this workflow.
- Host AI rule: Reproduce the official install and quickstart path in an isolated environment.
- Why it matters: May increase setup, validation, or first-run risk for the user.
- Evidence: community_evidence:github | https://github.com/pydantic/pydantic-ai/issues/5765
- Hard boundary: Do not present this pitfall as solved, verified, or ignorable unless later evidence explicitly closes it.

### Constraint 9: Security or permission risk requires verification

- Trigger: Developers should check this security_permissions risk before relying on the project: Proposal: Gating tool execution with a policy/audit layer
- Host AI rule: Before packaging this project, run the relevant install/config/quickstart check for: Proposal: Gating tool execution with a policy/audit layer. Context: Source discussion did not expose a precise runtime context.
- Why it matters: Developers may expose sensitive permissions or credentials: Proposal: Gating tool execution with a policy/audit layer
- Evidence: failure_mode_cluster:github_issue | https://github.com/pydantic/pydantic-ai/issues/5730
- Hard boundary: Do not present this pitfall as solved, verified, or ignorable unless later evidence explicitly closes it.

### Constraint 10: Security or permission risk requires verification

- Trigger: Project evidence flags a security or permission risk. Review the linked source before relying on this workflow.
- Host AI rule: Reproduce the official install and quickstart path in an isolated environment.
- Why it matters: May increase setup, validation, or first-run risk for the user.
- Evidence: community_evidence:github | https://github.com/pydantic/pydantic-ai/issues/5769
- Hard boundary: Do not present this pitfall as solved, verified, or ignorable unless later evidence explicitly closes it.

