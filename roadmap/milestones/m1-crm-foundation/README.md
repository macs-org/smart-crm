# Milestone 1: CRM Foundation

Core CRM foundation: users can access the product, manage contacts/accounts, track deals, and create follow-up tasks.

**Status:** In Progress

## MVPs

| MVP | Name | Status | Notes |
|-----|------|--------|-------|
| 1.1 | Product Shell | ✅ Complete | Static Vercel landing/dashboard preview |
| 1.2 | Auth + Workspaces | Planned | Login and workspace model |
| 1.3 | Contacts + Accounts | Planned | Core CRM records |
| 1.4 | Pipeline + Deals | Planned | Kanban-style deal tracking |
| 1.5 | Tasks + Follow-ups | Planned | Next actions, reminders, due dates |

## Build Strategy

Each MVP is built as a standalone app in `apps/mvps/` first. When every MVP in this milestone is complete, merge the MVPs into the milestone integration app at:

```txt
apps/milestones/m1-crm-foundation/
```

After milestone QA, merge the milestone into the main production app.

## Milestone Ship Criteria

- [ ] All M1 MVPs are complete
- [ ] Integrated M1 app build passes
- [ ] Production Vercel deploy verified
- [ ] Data model documented
- [ ] Known issues documented
