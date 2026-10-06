# Adrian's FAANG Data Prep

A GitHub-style tracker for a 50-session SQL + Python plan (1 hour/day, Monday–Friday only).
Tick tasks, rate your confidence and write notes. Every session has study and practice links.

**Open it:** https://dhavalkodrani.github.io/Adrian_faang_prep/

- **Schedule:** starts Monday Oct 12, 2026 (weekends and Thanksgiving skipped). Want to start today instead?
  Tap **↺ Reset / restart → Restart from today**. Use the same button any time you fall behind.
- **Phases:** SQL Mastery (10) · Python Basics (10) · Python Extended (30)
- Progress is saved to [`progress.json`](progress.json) in this repo, so it syncs across laptop, iPad and phone.

## Saving progress

Anyone can view the page. To tick tasks and have them saved, tap **⚙︎ Sync** and paste a GitHub token
that can write to this repo (Contents: Read and write, this repo only). The token is stored only in that
browser, on that device.

## Want your own copy instead?

Click **Use this template → Create a new repository** on GitHub, then enable
**Settings → Pages → Deploy from branch → main**. Your site will be at `https://<you>.github.io/<repo>/`
and you can create your own token for it.

## Files

| File | What it is |
|---|---|
| `plan.json` | The curriculum: start date, skipped dates, each day's tasks and links. |
| `progress.json` | Progress database (written by the site). |
| `index.html`, `app.js`, `style.css` | The site. No build step. |
