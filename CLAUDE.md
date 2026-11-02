# Dinner Club — project rules

Three teammates build this site, each with their own Claude Code. Follow these rules so the work fits together.

## What we're building
A website that splits a restaurant check **itemized**: each person pays for their own items, and tax and tip are split **proportionally** to each person's share of the subtotal. See `docs/requirements.md` for the client's requirements. Don't build features the client hasn't asked for.

## Tech
- Plain HTML, CSS and JavaScript. No build step, no frameworks, so GitHub Pages can serve it as-is.
- Hosted on GitHub Pages from the `main` branch.
- Must work well on a phone first.

## Money math
- Store money as whole **cents** (integers), never floating-point dollars.
- Proportional share: `person_tax = tax * person_subtotal / subtotal` (same for tip).
- Round to cents and make sure every person's amounts add up **exactly** to the bill total; give leftover cents to the largest shares first.

## Teamwork
- Run `git pull` before starting work.
- Stay in the files for your own part when you can; ask before rewriting a teammate's code.
- Make small commits with clear messages, and push often.
- Never commit passwords, API keys or other secrets.
- On hold: receipt video. Don't build it until the client answers the open questions.
