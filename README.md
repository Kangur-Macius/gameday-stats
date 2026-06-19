# Game Day — Bentleigh Greens FC

A Progressive Web App matchday stats tracker for Bentleigh Greens FC.

## What's included in this build
- Accurate timestamp-based match timer (fixes clock drift at half time)
- START H1 / END H1 / START H2 / END H2 flow with confirmation dialogs
- Half Time quick-summary report (auto-shown when H1 ends)
- Full Time detailed report with PDF/print export
- Player stats: goals, assists, shots on/off target, fouls, cards, offsides
- Starting XI (with formation-based position labels) + Bench
- Settings: team names, formations, opposition (dropdown), home/away venue, lineup editor
- Substitutions log with dropdown player selection
- Stats locked before kickoff, at half time, and after full time

## Deploy to GitHub Pages
1. Create a new GitHub repository (e.g. `game-day`)
2. Upload **all files** from this folder to the repository root
3. Go to **Settings → Pages → Deploy from branch → main → / (root)**
4. Save — live at `https://yourusername.github.io/game-day/`

## Install on iPhone (Safari)
Open the URL → Share → **Add to Home Screen**
Runs fullscreen, works offline after first load.

## Install on Android (Chrome)
Open the URL → ⋮ → **Add to Home Screen**

## Files
| File | Purpose |
|------|---------|
| `index.html` | Full app (self-contained React via CDN) |
| `manifest.json` | App name "Game Day", icons, theme colour |
| `service-worker.js` | Offline caching |
| `icon-192.png` | Soccer ball icon, light green background |
| `icon-512.png` | Splash screen icon |
