# Huseyin Kagan Isik

I build local-first developer tools for AI agents, security automation, and verifiable workflows.

My current focus is small, auditable CLIs that help developers move faster without handing control to a black box: instruction checks, handoff packets, host audit reports, and native workflow surfaces that stay useful after the first demo.

## Selected Work

| Project | What it proves | Status |
| --- | --- | --- |
| [AgentFit](https://github.com/kingkyylian/agentfit) | `AGENTS.md`, `CLAUDE.md`, Cursor rules, and coding-agent instructions can be tested like product surface. Includes local scoring, generated fitness tasks, CI reports, and a GitHub Action. | npm CLI, GitHub Action, real-world validation |
| [Linwarden](https://github.com/kingkyylian/linwarden) | Linux host hardening can be audited without root, daemons, network calls, or heavyweight compliance tooling. Outputs Markdown, JSON, and SARIF for CI and code scanning. | PyPI package, GitHub Action, signed releases |
| [HandoffKit](https://github.com/kingkyylian/handoffkit) | Interrupted AI coding sessions need deterministic resume packets, not raw transcript dumps. Captures branch state, diffs, instructions, verification scripts, and secret-aware context. | npm CLI, active release line |
| [Flowline](https://github.com/kingkyylian/flowline) | macOS developer context can live in a local, privacy-preserving top-edge workflow layer instead of another cloud dashboard. | early SwiftUI/AppKit preview |
| [RealityKit Pipeline Guide](https://github.com/kingkyylian/realitykitpipelineguide) | Asset generation for RealityKit should have manifests, CLI gates, screenshot evidence, and repeatable release checks. | preview CLI and teaching repo |

## Currently Shipping

- [AgentFit](https://github.com/kingkyylian/agentfit): improving dry-run validation quality and collecting more public agent-instruction examples.
- [Linwarden](https://github.com/kingkyylian/linwarden): expanding rootless Linux posture checks, SARIF output, and GitHub Action usage.
- [HandoffKit](https://github.com/kingkyylian/handoffkit): tightening resume packets, target-agent formatting, local verification capture, and secret scanning.
- [Flowline](https://github.com/kingkyylian/flowline): turning the macOS overlay MVP into a clear early preview with CI, release notes, and privacy-first positioning.

## Proof Points

- AgentFit found stale command documentation in RedisInsight Cursor rules; maintainers requested a PR and [merged the fix](https://github.com/redis/RedisInsight/pull/5889).
- AgentFit is published as an npm CLI and reusable GitHub Action.
- Linwarden ships on PyPI with SARIF output and a composite GitHub Action for CI/security workflows.
- HandoffKit ships as an npm CLI for clean handoffs between Codex, Claude Code, Cursor, Gemini, ChatGPT, and generic agents.

## Tooling

TypeScript, Node.js, Python, Swift, SwiftUI, AppKit, React, Next.js, PostgreSQL, GitHub Actions, local-first CLI design, security automation, AI agent workflows.

## Engineering Style

- Prefer deterministic defaults and explicit execution modes.
- Keep dry-runs local unless the user selects a real adapter.
- Make reports transparent enough to debug without guessing.
- Treat instruction files, automation scripts, and docs as testable product surface.
