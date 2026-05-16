# Smart CRM Roadmap

Smart CRM is planned as a sequence of milestones. Each milestone contains multiple MVPs. Each MVP has a standalone `SPEC.md` and should be built first as a standalone app before it is merged into its parent milestone and then into production.

## Workflow

```txt
MVP SPEC
  -> standalone MVP app in apps/mvps/<mvp>/
  -> MVP review + completion
  -> merge into apps/milestones/<milestone>/
  -> milestone review + release
  -> merge into production app
```

## Milestones

| Milestone | Name | Status | Notes |
|-----------|------|--------|-------|
| M1 | CRM Foundation | In Progress | Product shell, auth, workspaces, contacts, accounts, pipeline, tasks |
| M2 | Agent-Assisted CRM | Planned | Command bar, smart follow-ups, relationship memory, daily brief |
| M3 | Integrations | Planned | Email, calendar, chat ingest, import/export |
| M4 | Team + Agent Collaboration | Planned | Shared workspaces, roles, comments, agent work queue |

## Status values

Use these statuses in milestone and MVP tables:

- `Planned` — accepted into roadmap, not started
- `In Progress` — actively being built
- `Review` — implementation complete, needs review/QA
- `Blocked` — cannot progress without an external decision/dependency
- `Complete` — MVP implementation merged into its standalone app path
- `Shipped` — integrated into production and deployed

## Directories

- [`milestones/`](milestones/) — milestone READMEs and MVP specs
- [`../apps/mvps/`](../apps/mvps/) — standalone MVP app workspaces
- [`../apps/milestones/`](../apps/milestones/) — milestone integration workspaces
- [`../docs/`](../docs/) — architecture and reference docs
