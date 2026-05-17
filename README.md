# Huseyin Kagan Isik

Software developer building local-first tools for AI agents, security automation, and developer workflows.

I care about small, verifiable systems: CLIs that explain their decisions, reports that can be checked in CI, and automation that stays useful after the first demo.

## Current Focus

- Testing whether coding-agent instructions actually work in real repositories.
- Building deterministic developer tools around AI-assisted engineering.
- Shipping practical security and audit CLIs for local environments.
- Turning validation work into upstream fixes instead of generic product claims.

## Selected Work

| Project | What it does | Stack |
| --- | --- | --- |
| [AgentFit](https://github.com/kingkyylian/agentfit) | Local-first checks for `AGENTS.md`, `CLAUDE.md`, Cursor rules, and coding-agent instructions. Includes CLI reports, scoring, generated fitness tasks, and a GitHub Action. | TypeScript, Node.js, GitHub Actions |
| [Linwarden](https://github.com/kingkyylian/linwarden) | Rootless Linux host inventory and hardening audit CLI. | Python |
| [RealityKit Pipeline Guide](https://github.com/kingkyylian/realitykitpipelineguide) | Teaching repo for the Blender to USDZ to RealityKit iOS asset pipeline. | Python, RealityKit |

## Recent Signal

- AgentFit found stale command documentation in RedisInsight Cursor rules; the maintainers requested a PR and [merged the fix](https://github.com/redis/RedisInsight/pull/5889).
- AgentFit is published as an npm CLI and reusable GitHub Action.
- Current work is focused on better report quality, real-world validation, and low-noise maintainer feedback.

## Tooling

TypeScript, Node.js, Python, Swift, React, Next.js, PostgreSQL, GitHub Actions, local-first CLI design, AI agent workflows.

## Engineering Style

- Prefer deterministic defaults and explicit execution modes.
- Keep dry-runs local unless the user selects a real adapter.
- Make reports transparent enough to debug without guessing.
- Treat instruction files, automation scripts, and docs as testable product surface.
