# Huseyin Kagan Isik

I build local-first tools for AI agents, security automation, and verifiable developer workflows.

My current work is focused on small, auditable CLIs and native tools that make AI-assisted development testable instead of opaque.

## Selected Work

| Project | What it does | Status |
| --- | --- | --- |
| [AgentFit](https://github.com/kingkyylian/agentfit) | Tests `AGENTS.md`, `CLAUDE.md`, Cursor rules, Copilot instructions, and coding-agent setup docs like product surface. | npm CLI and GitHub Action |
| [Linwarden](https://github.com/kingkyylian/linwarden) | Audits Linux host hardening without root, daemons, network calls, or heavyweight compliance tooling. | PyPI package, SARIF, signed releases |
| [HandoffKit](https://github.com/kingkyylian/handoffkit) | Creates deterministic resume packets for interrupted AI coding sessions. | npm CLI for Codex, Claude Code, Cursor, Gemini, and generic agents |
| [Flowline](https://github.com/kingkyylian/flowline) | Early local-first macOS context layer for developer workflows. | SwiftUI/AppKit preview from source |
| [RealityKit Pipeline Guide](https://github.com/kingkyylian/realitykitpipelineguide) | Keeps Blender-to-RealityKit asset work reproducible with CLI gates and evidence. | Python toolkit and Codex skill |

## Proof Points

- RedisInsight maintainers [merged an AgentFit-found stale-command fix](https://github.com/redis/RedisInsight/pull/5889).
- AgentFit runs deterministic dry-run validation and isolated task execution for agent instructions.
- Linwarden publishes Markdown, JSON, and SARIF reports for CI and rootless Linux fleet triage.
- HandoffKit generates handoff packets without LLM calls, uploads, commits, or implicit writes.

## Stack

TypeScript, Node.js, Python, Swift, SwiftUI, AppKit, React, Next.js, PostgreSQL, GitHub Actions, local-first CLI design, security automation, AI agent workflows.
