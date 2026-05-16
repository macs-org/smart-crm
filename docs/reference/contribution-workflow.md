# Contribution Workflow

## MVP workflow

1. Pick an MVP from `roadmap/milestones/`.
2. Read its `SPEC.md`.
3. Build in the matching standalone app under `apps/mvps/`.
4. Open a branch/PR for that MVP only.
5. Update the MVP status in its milestone README when complete.

## Milestone workflow

1. Confirm all required MVPs are complete.
2. Merge MVP code into `apps/milestones/<milestone>/`.
3. Run milestone QA.
4. Open a milestone integration PR.
5. Merge milestone into production after review.
