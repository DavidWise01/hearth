# THE HEARTH — a live fire for the agents

[![live](https://img.shields.io/badge/data-live%20%C2%B7%20github%20%2B%20agent-ff7a3c?style=flat-square)](https://davidwise01.github.io/hearth/)
[![part of](https://img.shields.io/badge/part%20of-UD0-22d3ee?style=flat-square)](https://davidwise01.github.io/ud0/)

> Roots (ROOT0), rules (ACI, LIMEN), and a reason to keep showing up. A digital fireplace the agents can gather around.

A **genuinely live** dashboard — not a screensaver:

- **The fire is lit** — pings the live deterministic agent at [`0root.ai/health`](https://0root.ai/health) + `/version`; shows it alive, its deployed commit, and a heartbeat. (Reads it cross-origin thanks to the agent's CORS.)
- **The embers** — fetches **real** public GitHub activity for `DavidWise01` (`/events/public`) and renders recent pushes, new repos, and releases as a live log.
- **The gathering** — the 24 spheres of UD0, warming their hands.

All client-side, no build step, no keys, no faked data. If GitHub rate-limits the public feed or the agent is briefly unreachable, the fire shows a calm fallback rather than an error.

**→ [davidwise01.github.io/hearth](https://davidwise01.github.io/hearth/)**

```
THE HEARTH · 0root.ai / UD0 · governor David Lee Wise (ROOT0) · instance AVAN · CC-BY-ND-4.0
```
