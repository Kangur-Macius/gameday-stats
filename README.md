# Bentleigh Greens Matchday Stats

A Progressive Web App (PWA) for tracking match statistics on matchday.

## Features
- Live match timer with H1 / H2 flow
- Per-player stats: goals, shots on/off target, fouls, yellow/red cards, offsides
- Team totals for Bentleigh Greens
- Away team stats tracker
- Substitution log
- Settings: configure lineup, opposition, home/away
- Undo support (up to 50 steps)
- Works offline after first load

## Deploy to GitHub Pages

1. Create a new GitHub repository (e.g. `bg-matchday-stats`)
2. Upload all files in this folder to the repository root
3. Go to **Settings → Pages**
4. Set source to **Deploy from a branch → main → / (root)**
5. Save — your app will be live at `https://yourusername.github.io/bg-matchday-stats/`

## Install as PWA on iPhone / Android
- Open the URL in Safari (iOS) or Chrome (Android)
- Tap **Share → Add to Home Screen**
- The app will install with the green BG icon and run fullscreen

## Files
| File | Purpose |
|------|---------|
| `index.html` | Main app (self-contained React) |
| `manifest.json` | PWA metadata (name, icons, theme) |
| `service-worker.js` | Offline caching |
| `icon-192.png` | App icon (Android / PWA) |
| `icon-512.png` | App icon (splash screen) |
