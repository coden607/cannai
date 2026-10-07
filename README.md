# Cannai

> **Status: SKELETON** — placeholder repository. No product code exists yet.

## What this is

`cannai` is a reserved/placeholder repository in the coden607 org. As of the
wave-2 factory audit (2026-10-08) it contains only shared agent-instructions —
no application code, no documented feature set, nothing deployable.

## Inventory (recursive, all branches)

| Path | Purpose |
|------|---------|
| `AGENTS.md` | Shared-skills policy: points every AI runtime at the canonical `coden607/skills` library |
| `CLAUDE.md` | Claude Code entrypoint → read `AGENTS.md` |
| `GEMINI.md` | Gemini CLI entrypoint → read `AGENTS.md` |
| `.github/copilot-instructions.md` | Copilot entrypoint → read `AGENTS.md` |

Branches: `main` only (single commit).

## Promised vs. missing

- **Promised:** nothing is documented. No README claims, no roadmap, no spec.
- **Missing:** all product code, tests, CI, deployment config, docs.
- **Deployable:** no. There is no static site, PWA, or server app here.

## What this repo is NOT

Per org convention (see `coden607/Narcoguard` README), project repos are kept
separate. Do not copy code from other coden607 projects into this one without
an explicit task.

## Next steps when work starts

1. Write a real README with the product definition.
2. Add a `.gitignore`, license, and CI before first code lands.
3. Keep the shared-skills policy files — they are intentional.
