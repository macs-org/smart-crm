# Milestone 4: Team + Agent Collaboration

Enable multiple humans and agents to collaborate safely in shared CRM workspaces.

**Status:** Planned

## MVPs

| MVP | Name | Status | Notes |
|-----|------|--------|-------|
| 4.1 | Shared Workspaces | Planned | Multi-user CRM spaces |
| 4.2 | Roles + Permissions | Planned | Owner/admin/member roles |
| 4.3 | Activity + Comments | Planned | Team notes and audit log |
| 4.4 | Agent Work Queue | Planned | Assign CRM work to agents |

## Build Strategy

Each MVP is built as a standalone app in `apps/mvps/` first. When every MVP in this milestone is complete, merge the MVPs into the milestone integration app at:

```txt
apps/milestones/m4-team-agent-collaboration/
```

After milestone QA, merge the milestone into the main production app.

## Milestone Ship Criteria

- [ ] Workspace sharing works for at least two users
- [ ] Permissions protect destructive operations
- [ ] Activity log captures key changes
- [ ] Agent work queue has clear ownership/status
- [ ] M4 integrated app deploy is verified
