# Milestone 2: Agent-Assisted CRM

Make Smart CRM more than a manual database: users can ask questions, get suggested next actions, and maintain relationship memory.

**Status:** Planned

## MVPs

| MVP | Name | Status | Notes |
|-----|------|--------|-------|
| 2.1 | AI Command Bar | Planned | Ask CRM questions and jump to records |
| 2.2 | Smart Follow-ups | Planned | Draft replies and next actions |
| 2.3 | Relationship Memory | Planned | Contact/account summaries and timelines |
| 2.4 | Daily Brief | Planned | Who needs attention today |
| 2.5 | Deal Risk Signals | Planned | Stale deals, missing stakeholders, next-step gaps |

## Build Strategy

Each MVP is built as a standalone app in `apps/mvps/` first. When every MVP in this milestone is complete, merge the MVPs into the milestone integration app at:

```txt
apps/milestones/m2-agent-assisted-crm/
```

After milestone QA, merge the milestone into the main production app.

## Milestone Ship Criteria

- [ ] Command bar can answer basic CRM questions
- [ ] Follow-up suggestions reference real CRM data
- [ ] Relationship memory is visible on contacts/accounts
- [ ] Daily brief is useful with sample or real data
- [ ] M2 integrated app deploy is verified
