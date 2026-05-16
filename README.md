# Smart CRM

CRM project for Emily's Lab / `#smart-crm`.

- Repository: <https://github.com/macs-org/smart-crm>
- Production: <https://smart-crm-navy.vercel.app/>
- Vercel project: `smart-crm`

## Current state

This repo currently contains a static production preview at the repo root:

- `index.html` — landing page + CRM dashboard preview
- `vercel.json` — minimal Vercel config for static hosting

## Planning + build structure

Smart CRM uses a milestone/MVP workflow:

1. Draft each MVP as a `SPEC.md` under `roadmap/milestones/<milestone>/<mvp>/`.
2. Build each MVP first as a standalone app under `apps/mvps/<mvp>/`.
3. When every MVP in a milestone is complete, merge them into `apps/milestones/<milestone>/`.
4. When a milestone is ready, merge the milestone into the main production app.
5. Deploy production to the existing Vercel project.

Key directories:

```txt
roadmap/              # Delivery plan: milestones and MVP specs
apps/mvps/            # Standalone MVP apps before integration
apps/milestones/      # Integrated milestone apps before production merge
docs/                 # Durable architecture/reference docs
```

See [`roadmap/README.md`](roadmap/README.md) for the milestone plan.

## Local development

Open `index.html` directly in a browser, or serve the repo root with any static server:

```bash
python3 -m http.server 3000
```

## Deployment

This checkout is linked locally to the existing Vercel project via `.vercel/project.json` (ignored by git).

Uses the existing Vercel credentials in `~/.hermes/.env`:

- `VERCEL_TOKEN`
- `VERCEL_SCOPE`

Deploy from this repo with:

```bash
PATH="$HOME/.nvm/versions/node/v22.22.0/bin:$PATH"   vercel deploy --prod --yes --token "$VERCEL_TOKEN" --scope "$VERCEL_SCOPE"
```
