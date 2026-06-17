# .github

GitHub org profile for givecareapp. Single file: `profile/README.md`.

Keep the domain list and repo list current when surfaces are added or removed.
Because the profile is a public credibility surface, link, badge, repo-list,
license, contact, partner, and press-claim edits are owner-gated. Maintainer
work may clarify local operating docs and prepare decision cards, but should not
change `profile/README.md` public claims without explicit owner approval.

## Validation

```bash
git diff --check
clawpatch status --json
# manually check every public URL touched in profile/README.md
```

## Clawpatch Review

Use `docs/clawpatch-watchlist.md` for profile-surface review passes. The repo
config is `clawpatch.config.json`; generated `.clawpatch/` state stays local and
ignored. Do not use Clawpatch as an automatic fixer here.
