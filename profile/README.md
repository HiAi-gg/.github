# HiAi.gg

**Practical open-source tools for AI-native software and agent workflows.**

HiAi builds focused tools for working with AI agents: shared knowledge, portable plugins, observability, and a shared UI kit.

Most projects are designed to stay small, understandable, self-hostable, and easy to connect through APIs, MCP, and CLI tools.

---

## Active Projects

### AI & Agent Infrastructure

| Project | Description | License | Status |
|---|---|---|---|
| **[DocsMint](https://github.com/HiAi-gg/docsmint)** | Self-hosted AI-native knowledge workspace for people, applications, and agents. Rich editing, automatic embeddings, multilingual hybrid search, GraphRAG, REST API, TypeScript SDK, CLI, and MCP server. | Apache-2.0 | **Active** |
| **[hiai-observe](https://github.com/HiAi-gg/hiai-observe)** | Lightweight all-in-one observability for applications and AI agents: errors, uptime, infrastructure, logs, OpenTelemetry, Sentry-compatible ingest, LLM tracing, MCP, CLI, and SDK. | MIT | **Active** |

---

### Agent Plugins

A portable tooling ecosystem for packaging **Agent Skills, MCP servers, and CLI integrations** so they can be reused across compatible AI coding environments.

| Project | Description | License | Status |
|---|---|---|---|
| **[agent-plugins](https://github.com/HiAi-gg/agent-plugins)** | Curated collection of portable Agent Plugins with trusted integrations, focused Agent Skills, safe defaults, and reproducible builds. | MIT | **Active** |
| **[agent-plugins-builder](https://github.com/HiAi-gg/agent-plugins-builder)** | CLI for creating, migrating, and packaging portable Agent Plugins from declarative configs, existing agent setups, skills, and MCP servers. | MIT | **Active** |
| **[agent-plugins-doctor](https://github.com/HiAi-gg/agent-plugins-doctor)** | Validation and diagnostics CLI for Agent Plugins. Checks compatibility and structure, explains problems, and safely fixes supported issues. | MIT | **Active** |

Learn more about the portable format at **[agent-plugins.org](https://agent-plugins.org/)**.

---

## Shared UI

| Project | Description | License | Status |
|---|---|---|---|
| **[hiai-ui](https://github.com/HiAi-gg/hiai-ui)** | Shared Svelte design system, tokens, primitives, and reusable application components used across HiAi products. | MIT | **Maintained** |

---

## Frozen Projects

These repositories remain available as open source, but are not currently under active development.

| Project | Description | License | Status |
|---|---|---|---|
| **[hiai-opencode](https://github.com/HiAi-gg/hiai-opencode)** | Multi-agent plugin for OpenCode 1.x. Frozen after OpenCode 2.0: 1.x plugins do not load, and this package is not ported. Last release 0.6.6. | MIT | **Frozen** |
| **[hiai-store](https://github.com/HiAi-gg/hiai-store)** | Multi-tenant e-commerce platform with storefront, merchant administration, checkout, payments, shipping, and product infrastructure. | MIT | **Frozen** |

---

## Archived

| Project | Description | License | Status |
|---|---|---|---|
| **[hiai-bobcode](https://github.com/HiAi-gg/hiai-bobcode)** | Former standalone multi-agent coding environment. Superseded by **hiai-opencode**, which is frozen on the OpenCode 1.x plugin API. | MIT | **Archived** |

---

## What Connects These Projects

HiAi projects are independent tools, not pieces of one mandatory framework.

Where it makes sense, they share a few principles:

- **AI-native interfaces** — APIs, MCP, CLI, and agent-friendly workflows are first-class features.
- **Small and understandable** — avoid unnecessary infrastructure and abstraction.
- **Self-hosting** — important data and services should be able to run on infrastructure you control.
- **Portability** — avoid locking workflows to one model, agent, or vendor.
- **Composable tools** — projects should remain useful independently and integrate cleanly when used together.
- **Reproducible development** — explicit configuration, automated validation, and predictable builds.
- **Permissive open source** — public projects use MIT or Apache-2.0 licensing.

---

## Built With Agents

A large part of HiAi is developed by one human working together with multiple AI agents.

The goal is not simply to generate more code. HiAi explores what software development looks like when agents can research, implement, review, test, operate browsers, use shared knowledge, and work through explicit quality gates.

**One human + many agents.**

---

## Links

- **Website:** [hiai.gg](https://hiai.gg)
- **DocsMint:** [docsmint.com](https://docsmint.com)
- **GitHub:** [github.com/HiAi-gg](https://github.com/HiAi-gg)
- **Contact:** hiai@webs.cool

---

Built by one human + many agents ❤️
