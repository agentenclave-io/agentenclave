<h1 align="center">AgentEnclave</h1>

<p align="center">
  <strong>Secure runtime boundaries for AI assistants.</strong><br />
  Give agents the access they need, without giving them the keys to everything.
</p>

<p align="center">
  <a href="https://agentenclave.io">Website</a> ·
  <a href="mailto:nikolay@nikolov.net">Contact</a>
</p>

---

## What is AgentEnclave?

AI assistants are moving beyond chat. They read files, call APIs, use tools, write code, operate infrastructure, and act on behalf of people and teams.

That makes them useful. It also makes them risky.

AgentEnclave is a project focused on secure runtime environments for AI assistants. The goal is simple: let agents do real work inside clear, enforceable boundaries.

Think of it as a safety layer between an AI assistant and the sensitive systems it wants to use.

## The problem

Most AI agent setups still treat access as an afterthought.

- Agents often run with too much local access
- Secrets can be exposed directly to prompts, tools, or logs
- Network access is difficult to reason about once tools start chaining together
- Teams lack a clean audit trail of what an assistant did and why
- Different agent frameworks solve safety in different, incompatible ways
- Security teams need governance without blocking useful automation

As agents become more capable, "just trust the assistant" is not a security model.

## The idea

AgentEnclave explores a framework-agnostic runtime model for AI assistants.

Instead of giving an assistant direct access to everything, the assistant runs inside an environment where sensitive capabilities are brokered, scoped, and auditable.

The assistant can still be useful. It can still call tools. It can still help users and teams get work done. But access is explicit, limited, and visible.

## What AgentEnclave focuses on

### Runtime isolation

Agents should run in controlled environments with clear boundaries around files, processes, network access, and system resources.

### Brokered capabilities

Sensitive actions should go through controlled interfaces rather than being handed directly to the assistant.

### Secret handling

Agents should be able to use approved credentials without exposing raw secrets in prompts, logs, or tool output.

### Policy-controlled access

Organizations should be able to define what an assistant can access, which actions require approval, and where stricter controls are needed.

### Auditability

Agent activity should leave a useful record: what was requested, what was allowed, what was denied, and what happened next.

### Framework independence

The same safety model should work across different assistants, models, tools, and agent frameworks.

## Who it is for

AgentEnclave is being designed for people and teams who want to use AI agents for real work without ignoring security:

- Developers building agent-based systems
- Security teams evaluating AI automation
- Platform teams standardizing internal assistant runtimes
- Enterprises that need governance, auditability, and control
- Researchers exploring safer agent execution models

## What this repository is

This is the public informational repository for AgentEnclave.

It is intentionally lightweight. Detailed implementation plans, internal architecture, security design, and operational notes are not published here.

Public updates will be added as the project matures.

## Status

AgentEnclave is in early design and prototyping.

The project is currently focused on the core security model, developer experience, and practical deployment patterns for controlled AI assistant runtimes.

## Contributing

This repository is currently informational only.

Contribution guidelines will be published later if parts of the project become available for external collaboration.

## Contact

For questions about AgentEnclave, contact Nikolay Nikolov at [nikolay@nikolov.net](mailto:nikolay@nikolov.net).
