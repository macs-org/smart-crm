# Decisions

Durable product and architecture decisions.

## 2026-05-16 — Roadmap/MVP structure

Smart CRM will use a milestone/MVP delivery structure:

- Roadmap lives in `roadmap/`.
- Each milestone has MVPs.
- Each MVP has a `SPEC.md`.
- Each MVP is built first as a standalone app in `apps/mvps/`.
- Completed MVPs are merged into milestone integration apps in `apps/milestones/`.
- Completed milestones are merged into the main production app.
- `docs/` is reserved for architecture and reference material, not delivery planning.
