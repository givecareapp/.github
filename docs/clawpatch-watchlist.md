# Clawpatch Org Profile Watchlist

Use Clawpatch as a review ledger for the GitHub organization profile, not as an
automatic fixer. This repo is intentionally tiny; findings should focus on stale
public links, repo lists, and positioning drift.

## Operating Rules

- Keep `.clawpatch/` local. Do not commit generated maps, findings, reports, or
  patch attempts.
- Review first. Do not run `clawpatch fix` until a human has triaged the
  finding and picked a scope.
- Do not use this repo to store private strategy, partner-specific claims, or
  operational status.

## Setup

```bash
clawpatch --version
clawpatch init
clawpatch map --source agent --reasoning-effort low
```

## Canonical Watchlist

| Watch item | Trigger it when changes touch | Ask Clawpatch to look for | Local verification anchors |
| --- | --- | --- | --- |
| Organization profile | `profile/README.md` | Dead or stale repo links, missing active public repos, archived repo claims that read as active, domain list drift. | Manual link check; compare root workspace `CLAUDE.md` repo inventory. |
| Agent profile notes | `CLAUDE.md`, this watchlist | Guidance that implies this repo owns product code, CI, deploys, or private operating truth. | Read `.github/CLAUDE.md`. |

## Triage

Treat findings as review input. A finding is actionable only after the public
claim, target repo, and fix scope are clear.
