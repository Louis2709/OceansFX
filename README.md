# TradeBuddy AI - Web Terminal (OceansFX)

A single‑file static demo of TradeBuddy AI — a dark‑mode web terminal that simulates chart analysis with drag‑and‑drop upload, preview, and a results dashboard.

## Live demo
https://louis2709.github.io/OceansFX/

## Run locally
Open `index.html` in your browser or run a simple server:
npx http-server -c-1 .
python3 -m http.server 8080

## Deploy
1. Upload `index.html` to the repo root and enable Pages in **Settings → Pages** (branch: main, folder: /).
2. Or add the GitHub Actions workflow `.github/workflows/pages-deploy.yml` to auto-deploy on push.

## Notes
- This demo is for demonstration only and does not provide trading advice.
- Keep asset paths relative (e.g., `./assets/img.png`) so Pages serves them correctly.
