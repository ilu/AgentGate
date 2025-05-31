# AgentGate – Policy, Logging and Control for Autonomous Agents

**AgentGate** is an open-source control layer for autonomous AI agents and automations. It acts as an intermediary between agents and the external world — including filesystems, processes, APIs, databases, GUIs, and more — enabling:

- Fine-grained permissions
- Action logging and audit trails
- Policy enforcement
- Alerting and human-in-the-loop controls
- Transparent verification of actions

AgentGate is designed to improve the **trust, safety, and observability** of agentic systems. It provides a modular TypeScript SDK and a schema for defining and enforcing what agents are allowed to do, and verifying that they actually did it.

## Why?

As agents are given more power, it's critical to control how they use it. Without oversight, they can access sensitive data, trigger unintended consequences, or fail silently. AgentGate provides a practical framework for safe deployment in real-world workflows.

## What’s included (MVP)

- A schema format for defining agent permissions, scopes, logging, and escalation.
- A TypeScript SDK for enforcing policies and logging actions.
- Example use cases and integrations (e.g., API access, file writes, external tools).
- Documentation and guides to get started.

## Status

AgentGate is under active development. The initial public version is expected in 2025.

## License

MIT
