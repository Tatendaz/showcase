# Tatenda Zhou — Selected Work

**Software & Systems Architect / SRE · 10+ years.** I design and operate event-driven
backends, data pipelines, AI-agent tooling, and offline-first mobile apps — plus the CI
and observability that keep them honest. Open to **consulting / advisory / speaking**, remote.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-tatendazhou-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/tatendazhou)
[![Email](https://img.shields.io/badge/Email-tatendaz%40me.com-EA4335?logo=maildotru&logoColor=white)](mailto:tatendaz@me.com)
[![X](https://img.shields.io/badge/X-%40realtatendazhou-000000?logo=x&logoColor=white)](https://x.com/realtatendazhou)

---

## About these write-ups

Some of this work is **open source**; some lives in **private repositories** (trading
infrastructure and a mobile product still heading to launch). Either way, the pages below
are write-ups — the problem each system solves, how it's architected, the engineering
decisions behind it, and the tech stack. For the private projects, everything is described
at an architectural level, **without exposing source, secrets, or anything sensitive**.

> 🔎 **Public projects link straight to the code.** For private ones I'm happy to walk
> through the code on request — reach out via any of the badges above.

## Projects

| Project | What it is | Stack | Status |
|---|---|---|---|
| [Vergance — Gaze + Voice for Claude](projects/vergance.md) | Look at the screen and speak → your intent, resolved to *what you looked at*, is delivered to Claude — a gaze + voice multimodal input layer | Swift · GazeKit · Vision / ARKit · Apache-2.0 | Core built & tested; macOS app in progress · **open source** |
| [Quant Backtest Platform (QBT)](projects/quant-backtest-platform.md) | Event-driven crypto backtester — describe a strategy in natural language, test it honestly (fees/funding/slippage), run the same code live | Python · TimescaleDB · FastAPI · Docker | Core working; live/paper rungs on roadmap |
| [Kintree — Family Tree App](projects/familytreeapp.md) | Native mobile app to build and share a family tree across generations, offline-first with real-time sync | Kotlin / Jetpack Compose · Firebase · (parallel SwiftUI iOS) | Architecture & core flows working end-to-end |

## How I work

- **Interfaces first.** Each system is built so the hard parts (execution venues, data
  sources, backend implementations) slot in behind clean boundaries — the core doesn't get
  re-architected when a new integration lands.
- **Honest cores.** Backtests that model fees, funding, and slippage rather than flattering
  returns; deterministic, well-tested domain logic over convenient shortcuts.
- **Operability built in.** Structured logging, Prometheus/Grafana, and CI gates that
  require tests and docs for every change — not bolted on afterward.

## Contact

- LinkedIn — <https://www.linkedin.com/in/tatendazhou>
- Email — <tatendaz@me.com>
- X — [@realtatendazhou](https://x.com/realtatendazhou)
