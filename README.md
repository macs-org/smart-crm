# Smart CRM

CRM project for Emily's Lab / `#smart-crm`.

- Repository: <https://github.com/macs-org/smart-crm>
- Production: <https://smart-crm-navy.vercel.app/>
- Vercel project: `smart-crm`

## Current state

This repo currently contains a static template site:

- `index.html` — landing page + CRM dashboard preview
- `vercel.json` — minimal Vercel config for static hosting

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
PATH="$HOME/.nvm/versions/node/v22.22.0/bin:$PATH" \
  vercel deploy --prod --yes --token "$VERCEL_TOKEN" --scope "$VERCEL_SCOPE"
```
