# Dinner Club

A free website for a friend group's monthly dinner. It splits the check **by what each person ordered**, and splits tax and tip **in proportion** to each person's food.

Live site (after GitHub Pages is on): `https://nickschug-coder.github.io/dinner-club/`

## Team
| Person | Owns |
|---|---|
| Nick | Itemized math (items → subtotal → proportional tax and tip), testing |
| Friend 1 | Page design (phone-first) — *receipt video is on hold* |
| Friend 2 | Saving data, who-owes-who, "paid back" |

## First-time setup (for each teammate)
1. Get a free GitHub account and accept Nick's collaborator invite (check your email).
2. Install Git: https://git-scm.com/downloads
3. Clone the repo:
   ```bash
   git clone https://github.com/nickschug-coder/dinner-club.git
   ```
4. Open the `dinner-club` folder in Claude Code. Claude reads `CLAUDE.md` for the project rules automatically.

## Every time you work
```bash
git pull
```
Do your part, then:
```bash
git add .
git commit -m "Short note on what you changed"
git push
```
If `git push` says you're behind, run `git pull` first, then push again.

## Files
- `index.html` — the website
- `docs/requirements.md` — what the client asked for
- `CLAUDE.md` — rules every teammate's Claude follows
