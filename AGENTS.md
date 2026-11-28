# AGENTS.md — SigmaOS-omapager

Machine-readable rules for AI agents working in this repository.

## Build & Test

If the component is scaffolded (docs only), implement build/test commands
with the first real sources and record them here and in `COMPONENT.toml`.
Otherwise use the documented commands for this component's language.

## Rules

- Single `main` branch; feature branches only for work needing tests,
  merged after tests pass.
- No hardcoded secrets — env vars or secret manager only.
- GPL-3.0-or-later. SigmaOS identity only; no upstream project references.
- Docs live in the GitHub Wiki; keep `docs/` minimal staging content.
- Follow SOLID, DRY, KISS, YAGNI; fail-fast errors; secure defaults.
- Component manifest: `COMPONENT.toml`. Interconnect: `tools-sigmaos.sh`.
