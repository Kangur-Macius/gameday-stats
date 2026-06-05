# Bentleigh Greens Matchday Stats — PWA

A Progressive Web App for tracking match statistics on matchday.

## Deploy to GitHub Pages

1. Create a new GitHub repository (e.g. `bg-matchday-stats`)
2. Upload **all files** from this folder to the repository root
3. Go to **Settings → Pages → Deploy from branch → main → / (root)**
4. Save — live at `https://yourusername.github.io/bg-matchday-stats/`

## Install on iPhone (Safari)
- Open the URL → tap Share → **Add to Home Screen**
- Runs fullscreen, works offline after first load

## Install on Android (Chrome)
- Open the URL → tap ⋮ → **Add to Home Screen**

## Files
| File | Purpose |
|------|---------|
| `index.html` | Full app (React via CDN, self-contained) |
| `manifest.json` | PWA name, icons, theme colour |
| `service-worker.js` | Offline caching |
| `icon-192.png` | App icon |
| `icon-512.png` | Splash screen icon |
