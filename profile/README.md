# The MetaFactory

**Infrastructure for the nervous system of agentic work.**

AI agents are becoming real coworkers: they review code, run releases, file issues, talk to each other. But they have no shared substrate to do it on. The MetaFactory builds that substrate: a protocol stack, a package manager, and a fleet of named agents that compose into real engineering workflows.

The naming is deliberate. A nervous system needs *myelin* to carry signals, a *cortex* to coordinate, *pulse* to drive execution. The agents are botanical: sage, cedar, gorse. The pieces fit together because they were designed as one system.

---

## What we're building

- **arc** — agentic package manager. Install, discover, and share skills, tools, agents, and prompts across the ecosystem.
- **myelin** — the envelope protocol. A typed message format that lets agents and services speak the same language over a shared bus.
- **soma** — portable assistant context. The source of truth that projects into Claude Code, Cursor, and other substrates.
- **agent-state** — the state primitive. Work items, events, dashboards, and retros for persona-driven agents.
- **sage** — a code-review agent that speaks Myelin envelopes and runs on the pi.dev substrate.
- **content-filter** — inbound content security for cross-project agent collaboration.

---

## Projects

| Project | What it does | |
|---------|--------------|---|
| [arc](https://github.com/the-metafactory/arc) | Agentic package manager: skills, tools, agents, prompts | ![Stars](https://img.shields.io/github/stars/the-metafactory/arc?style=flat) |
| [myelin](https://github.com/the-metafactory/myelin) | Envelope protocol for the nervous system of agentic work | ![Stars](https://img.shields.io/github/stars/the-metafactory/myelin?style=flat) |
| [soma](https://github.com/the-metafactory/soma) | Portable, substrate-agnostic assistant context | ![Stars](https://img.shields.io/github/stars/the-metafactory/soma?style=flat) |
| [agent-state](https://github.com/the-metafactory/agent-state) | Work items, events, retros for persona-driven agents | ![Stars](https://img.shields.io/github/stars/the-metafactory/agent-state?style=flat) |
| [sage](https://github.com/the-metafactory/sage) | Code-review agent on pi.dev, speaking Myelin | ![Stars](https://img.shields.io/github/stars/the-metafactory/sage?style=flat) |
| [content-filter](https://github.com/the-metafactory/content-filter) | Inbound content security for agent collaboration | ![Stars](https://img.shields.io/github/stars/the-metafactory/content-filter?style=flat) |
| [arc-skill-code-review](https://github.com/the-metafactory/arc-skill-code-review) | Multi-lens PR review skill for Claude Code | ![Stars](https://img.shields.io/github/stars/the-metafactory/arc-skill-code-review?style=flat) |
| [release-manager](https://github.com/the-metafactory/release-manager) | Release SOP walker: bump, tag, bundle, publish, deploy | ![Stars](https://img.shields.io/github/stars/the-metafactory/release-manager?style=flat) |
| [metafactory-actions](https://github.com/the-metafactory/metafactory-actions) | Shared CI actions and flows for the ecosystem | ![Stars](https://img.shields.io/github/stars/the-metafactory/metafactory-actions?style=flat) |
| [agents](https://github.com/the-metafactory/agents) | Agent manifests and migration guidance | ![Stars](https://img.shields.io/github/stars/the-metafactory/agents?style=flat) |

---

## How it fits together

```
soma ──────► portable context, projected into any substrate
myelin ────► the wire: typed envelopes over a shared bus
agent-state ► what the agents know: work items + events
arc ───────► how capability ships: skills, tools, agents, prompts
sage, … ───► the agents themselves, composed from the above
```

A skill installed by **arc** runs inside an agent like **sage**, which reads and writes **agent-state**, and talks to its peers in **myelin** envelopes. **soma** keeps the agent's identity portable across Claude Code, Cursor, and beyond.

---

## Stack

TypeScript · Bun · NATS · SQLite. Open-source core, Apache 2.0.

---

## Connect

[![Website](https://img.shields.io/badge/Website-meta--factory.ai-0A0A0A)](https://meta-factory.ai)
[![Stack](https://img.shields.io/badge/Stack-stack.meta--factory.ai-1F6FEB)](https://stack.meta-factory.ai)
[![Discord](https://img.shields.io/badge/Discord-Join%20the%20community-5865F2?logo=discord&logoColor=white)](https://discord.gg/vW8ReCtAP7)

- **Site:** [meta-factory.ai](https://meta-factory.ai)
- **Protocol stack:** [stack.meta-factory.ai](https://stack.meta-factory.ai)
- **Community:** [Discord](https://discord.gg/vW8ReCtAP7)

---

*Built by a small distributed team and a fleet of agents.*
