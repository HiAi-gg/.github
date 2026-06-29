# HiAi.gg

**Lightweight AI tools**

Small, fast, and practical self-hosted projects focused on AI-native workflows, shared memory, and real autonomy.

---

## Open Source Projects

| Project | Description | Stack | License | Status |
|---------|-------------|-------|---------|--------|
| **[hiai-docs](https://github.com/HiAi-gg/hiai-docs)** | The most mature and complete project. The lightest AI-native self-hosted knowledge vault with automatic RAG (Ollama + pgvector), TipTap v3 rich editor, hybrid semantic search, and clean REST API for agents. | Bun + SvelteKit + Elysia + Drizzle + PostgreSQL + pgvector | MIT | **Active** (most complete) |
| **[hiai-observe](https://github.com/HiAi-gg/hiai-observe)** | Lightweight all-in-one observability platform. Errors, uptime, Docker stats, logs, and AI tracing — all in a single container. Excellent alternative to Sentry + Uptime Kuma + Dozzle. | Bun + Svelte + Elysia + PostgreSQL | MIT | **Active** |
| **[hiai-bobcode](https://github.com/HiAi-gg/hiai-bobcode)** | Main AI coding agent. 10-agent team (with Bob as orchestrator), memory, design awareness, parallel task execution, and rich set of skills. | Bun + TypeScript + SolidJS | MIT | **Active** |
| **[hiai-opencode](https://github.com/HiAi-gg/hiai-opencode)** | 14-agent OpenCode plugin (predecessor of Bobcode). Turns regular OpenCode into a powerful multi-agent development environment with MCP tools, browser automation and design systems. | HTML + TypeScript | MIT | **Development paused** |
| **[hiai-admin](https://github.com/HiAi-gg/hiai-admin)** | Admin panel and dashboard for managing the HiAi ecosystem. | Svelte + Bun | MIT | **Beta** |
| **[hiai-ui](https://github.com/HiAi-gg/hiai-ui)** | Core design system and UI component library (shadcn-svelte + tokens) for the entire HiAi ecosystem. | Svelte + Tailwind | MIT | **Active** (design foundation) |
| **[hiai-kit](https://github.com/HiAi-gg/hiai-kit)** | Opinionated starter kit for building production-ready AI agents (Mastra + memory + observability). | Bun + Mastra + SvelteKit + PostgreSQL | MIT | **Alpha** |
| **[hiai-post](https://github.com/HiAi-gg/hiai-post)** | AI-powered content generation and multi-platform publishing (social networks). | Bun + SvelteKit + Elysia + PostgreSQL | MIT | **Alpha** |
| **[hiai-store](https://github.com/HiAi-gg/hiai-store)** | Multi-tenant e-commerce module (storefront + merchant admin, Stripe, shipping). | Bun + SvelteKit + Elysia + PostgreSQL | MIT | **Alpha** |

---

## Core Idea

All projects follow the same principles:
- Minimal resource usage
- Strong focus on local-first AI (embeddings, RAG, pgvector)
- Clean APIs and MCP integrations for agent workflows
- Full self-hosting and data ownership
- MIT License — free to use, modify, and build upon

Most development happens together with AI agents (Bob and others) sharing long-term memory.

---

## Links

- Website: [hiai.gg](https://hiai.gg)
- Contact: hiai@webs.cool

---

Made by one human + many agents ❤️
