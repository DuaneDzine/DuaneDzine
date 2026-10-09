# Duane Dzine

Local-first AI: tooling that makes local LLMs and AI agent fleets actually
usable on a single workstation, plus the systems glue around both.

## What I'm building

- **[lanecheck](https://github.com/DuaneDzine/lanecheck)** — health-check every
  local LLM endpoint from one command. Stdlib-only Python CLI for Ollama and
  OpenAI-compatible endpoints.
- **[ai-stack](https://github.com/DuaneDzine/ai-stack)** — the workstation AI
  stack: a fast GPU lane and a big memory lane, a LiteLLM gateway that fronts
  both (plus cloud when keys are present), and the orchestration that plugs in.
- **[workstation-scripts](https://github.com/DuaneDzine/workstation-scripts)** —
  scripts that keep the stack honest: `stack-validate`, `ai-mode`, model
  builds, and the phone-as-terminal path.
- **[MedBadge](https://github.com/DuaneDzine/MedBadge)** — a healthcare project
  (Next.js + TypeScript + Firebase + Vercel).
- **SwarmWatch** — agent-fleet supervision: capability probes (not just TCP),
  latency and error budgets, dead-man's-switch heartbeats. Coming.

## Themes

- **Local-first** — default to running models on your own hardware; make the
  cloud a deliberate pivot, not a reflex.
- **AI observability** — probes, budgets, fallbacks, and tooling that exits
  non-zero when a lane dies.
- **Systems thinking** — stdlib-only CLIs, no dependencies unless they earn
  their place.

[GitHub.com/DuaneDzine](https://github.com/DuaneDzine)