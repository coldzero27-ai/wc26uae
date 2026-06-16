# FIFA World Cup 2026 — Match Schedule (UAE Time)

Interactive wall chart for the 2026 World Cup. All 104 matches in UAE time (GST, UTC+4).

- **index.html** — animated video background, full features
- **clean.html** — static background version

## Features
- Full group stage + knockout bracket
- Tap any knockout box to pick a country (with flag)
- Editable dates and scores; winner auto-highlights
- "★ Mark games" — click matches to glow gold (today's / upcoming games); legend shown top
- 16:9, auto-fullscreen on TVs (Present button)
- Save / Export / Import your state

## Publishing results to everyone
1. Open the page, enter scores, pick knockout teams, and mark today's games
2. Click **Export** → downloads `worldcup-results.json`
3. Rename it to **`results.json`**
4. Upload `results.json` to this repo (Add file → Upload files → Commit)
5. Every visitor's page loads it automatically and silently re-checks every 30 minutes

Built with Claude.
