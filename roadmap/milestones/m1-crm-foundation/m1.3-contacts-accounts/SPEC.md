# MVP 1.3: Contacts + Accounts

Status: Planned  
Milestone: Milestone 1: CRM Foundation

## Goal

Define and ship the smallest standalone version of **Contacts + Accounts** that can be reviewed independently before milestone integration.

## Problem

TODO: Describe the user/business problem this MVP solves.

## Scope

Included:

- TODO

Excluded:

- TODO

## User Stories

- As a user, TODO.

## App Path

Standalone MVP app path:

```txt
apps/mvps/m1.3-contacts-accounts/
```

Milestone integration path:

```txt
apps/milestones/m1-crm-foundation/
```

## Data Model

TODO: Add tables/entities/fields needed by this MVP. Link durable architecture notes in `docs/architecture/` when the model becomes shared across MVPs.

## Acceptance Criteria

- [ ] Standalone MVP app exists under `apps/mvps/`
- [ ] MVP can be run or previewed independently
- [ ] MVP-specific user flow works end-to-end
- [ ] Empty/loading/error states are covered where relevant
- [ ] Build/validation command passes
- [ ] README/docs updated

## Implementation Notes

- Keep this MVP standalone first.
- Do not couple to later MVPs unless the dependency is explicitly documented.
- When complete, update the parent milestone README status table.
