# GiveCare GitHub Profile Charter

This charter is an evaluation document, not an operating manual. For the shared
GiveCare North Star, see `~/agents/wiki/givecare-system.md`.

## Purpose

This repo owns GiveCare's public GitHub organization profile. It is the public
open-source front door for people who discover GiveCare through GitHub.

## Role In GiveCare

The `.github` repo belongs to the open-source credibility and public-surface
edge of GiveCare. It should make the public repos legible, link to deployed
public surfaces, and communicate the open-source posture without duplicating
product docs or private strategy.

## Product / System Promise

The repo should help a technical reader quickly understand what GiveCare has made
public, where to start, and how the open-source projects relate to the broader
caregiving mission.

## What This Repo Owns

- `profile/README.md`, the GitHub organization profile shown on
  `github.com/givecareapp`.
- Public-safe summaries of open-source repos and deployed public domains.
- Links that route readers to canonical public surfaces and repo READMEs.

## What This Repo Does Not Own

- Product runtime docs, internal operations, private strategy, customer data, or
  unreleased roadmap. Those belong outside this public profile repo.
- Detailed docs for `../gc-sms`, `../gc-web`, `../gc-wiki`, `../gc-benefits`,
  `../gc-bench`, `../givecare-evals`, `../givecare-tools`, or `../gc-tune`.
- Public methodology and evidence pages. Those belong in `../gc-wiki`.
- Marketing-site implementation. That belongs in `../gc-web`.

## Inputs

- Public repo READMEs, releases, and licenses.
- Public GiveCare domains and deployed surfaces.
- Public-safe positioning from the GiveCare wiki and web surfaces.

## Outputs

- GitHub organization profile copy and links.
- A clean public entry point into GiveCare's open-source credibility layer.

## Core Invariants

- Content must be public-safe and open-source focused.
- Link to canonical docs rather than duplicating them.
- Avoid private runtime details, operations, metrics, partner data, and unreleased
  strategy.
- Keep the profile short enough to scan.

## Evaluation Questions

- Does this change help a GitHub reader understand the public repos faster?
- Are all links public, current, and canonical?
- Does it strengthen open-source credibility without leaking private product or
  operating context?
- Would this profile still make sense if read without access to private GiveCare
  systems?

## Anti-Patterns

- Turning the org profile into a product manual.
- Listing private repos, internal tools, private metrics, or partner-sensitive
  details.
- Copying long-form content from wiki/web pages instead of linking.
- Letting stale deployed-domain lists linger after public surface changes.

## Related Documents

- `CLAUDE.md`
- `profile/README.md`
- `../gc-bench/CHARTER.md`
- `../givecare-evals/CHARTER.md`
- `../givecare-tools/CHARTER.md`
- `~/agents/wiki/givecare-system.md`
