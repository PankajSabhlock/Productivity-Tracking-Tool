# GoalDash

GoalDash is a modern, client-side personal goals dashboard built as a single HTML app.

This repository is structured so you can:
- run it locally with one command, or
- deploy it to GitHub Pages.

## Repo layout

- `index.html` — the app entry point (open this in a browser)
- `app/goals_dashboard-0.9.3.html` — original versioned single-file build
- `docs/` — project docs (`CHANGELOG.md`, `CONTRIBUTING.md`)
- `assets/` — screenshots and static assets

## Run locally

### Option A: Just open it

Open `index.html` directly in your browser.

### Option B: One-command local server (recommended)

```bash
npm install
npm run dev
```

Then open:
- http://localhost:8000

## Deploy to GitHub Pages

1. Push this repo to GitHub.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**:
   - Source: **Deploy from a branch**
   - Branch: `main` (or `master`) / root
4. Save.

GitHub Pages will serve `index.html` automatically.

## Notes

- No backend. Data is stored in **LocalStorage** in the browser.
- External dependencies are loaded via CDN (Tailwind + FullCalendar).

## License

MIT — see `LICENSE`.
