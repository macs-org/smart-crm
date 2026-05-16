# Deployment Architecture

Production currently deploys from the repo root to the existing Vercel project `smart-crm`.

- Production URL: <https://smart-crm-navy.vercel.app/>
- Current production app: repo root static site
- Vercel local link: `.vercel/project.json` (ignored by git)

Future milestone integration should keep production deploys stable while standalone MVP apps evolve under `apps/mvps/`.
