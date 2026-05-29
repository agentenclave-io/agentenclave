# AgentEnclave

AgentEnclave is an open project exploring secure runtime environments for AI assistants.

AI agents are quickly moving from chat windows into real work: reading files, calling tools, using APIs, writing code, managing infrastructure, and acting on behalf of people and teams. That creates a simple problem: useful agents need access, but access without boundaries is risky.

AgentEnclave focuses on those boundaries.

The goal is to make AI assistants safer to run by giving them a controlled environment with clear permissions, limited access to sensitive resources, and an auditable record of what happened. The project is designed around practical questions:

- What should an assistant be allowed to access?
- Who grants that access?
- How can secrets be used without exposing them directly to the assistant?
- How can teams review what an assistant did after the fact?
- How can the same safety model work across different agent frameworks?

AgentEnclave is intended to be framework agnostic. It should be possible to use the same security and governance ideas with different assistants, models, tools, and deployment environments.

## What we care about

- Safer agent execution
- Clear permission boundaries
- Human-controlled access to sensitive capabilities
- Separation between assistants and the resources they use
- Auditability for actions taken by AI systems
- Practical adoption by developers, teams, and organizations

## What this repository is

This repository is the public entry point for the AgentEnclave project.

For now, it contains a short public description only. Detailed design notes, implementation plans, and security architecture are not published here yet.

## Status

AgentEnclave is in early design and prototyping.

The public materials will stay high level until the project is ready to share more.

## Contact

For questions about the project, contact Nikolay Nikolov at nikolay@nikolov.net.
