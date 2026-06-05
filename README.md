# STRES3 — Deterministic AGI Engine for ARC-AGI-3

> **ARC Prize 2026** | First level completed in sp80 | No GPU | No LLM during gameplay

## What is STRES3?

STRES3 is an original deterministic agent architecture built for the ARC-AGI-3 benchmark.
It explores unknown game environments from scratch — without any hardcoded knowledge about colors, rules, or goals.

## Key properties

- **Zero GPU** — runs entirely on CPU
- **No LLM during gameplay** — all decisions are deterministic
- **No hardcoded rules** — the agent discovers game mechanics through observation
- **Persistent frontier memory** — learns across attempts, never repeats mistakes
- **25 games simultaneously** — one algorithm, all environments

## Architecture

Perception Layer     → discovers colors, objects, movement
Frontier Pathfinder  → builds state graph, remembers explored territory
Goal Router          → identifies target candidates from grid geometry
Action6 Anchor Map   → click-based games with coordinate memory
Meta-Learner         → improves parameters between runs

## Results (ARC-AGI-3, local evaluation)

| Game | Status | Notes |
|------|--------|-------|
| sp80 | Level 1 completed | 518 actions |
| 24 other games | In progress | Frontier building |

## Status

Active development. Source code is private during the competition phase.
Public technical documentation will be added after validation.

**Author:** Michal Machura
**Started:** June 2026
