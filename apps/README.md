# Apps

Smart CRM uses app workspaces to keep experimental MVP work separate from milestone integration and production.

## Structure

```txt
apps/
├── mvps/        # Standalone MVP apps
└── milestones/  # Integrated milestone apps
```

## Flow

1. Build each MVP independently under `apps/mvps/<mvp>/`.
2. Merge completed MVPs for a milestone into `apps/milestones/<milestone>/`.
3. Merge the completed milestone into the production app at the repo root.

The repo root currently hosts the production static preview deployed to Vercel.
