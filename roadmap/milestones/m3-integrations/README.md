# Milestone 3: Integrations

Ingest real relationship context from email, calendar, chat, and import/export flows.

**Status:** Planned

## MVPs

| MVP | Name | Status | Notes |
|-----|------|--------|-------|
| 3.1 | Email Sync | Planned | Gmail/IMAP relationship context |
| 3.2 | Calendar Sync | Planned | Meetings as CRM events |
| 3.3 | Chat Ingest | Planned | Discord/Slack relationship signals |
| 3.4 | CSV Import/Export | Planned | Migration path and backups |

## Build Strategy

Each MVP is built as a standalone app in `apps/mvps/` first. When every MVP in this milestone is complete, merge the MVPs into the milestone integration app at:

```txt
apps/milestones/m3-integrations/
```

After milestone QA, merge the milestone into the main production app.

## Milestone Ship Criteria

- [ ] At least one external source syncs into CRM events
- [ ] Imported events link to contacts/accounts
- [ ] User can inspect sync state and errors
- [ ] CSV export provides usable backup data
- [ ] M3 integrated app deploy is verified
