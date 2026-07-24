# GameGuide AI — Boss Assist MVP

A functional prototype of GameGuide AI's in-game boss-assist experience, built for Assignment 6 (AI for UX Designers).

## Features
- **Real voice recognition** (Web Speech API) — tap the mic and ask a question out loud
- **Text fallback** if voice isn't available or permission is denied
- **Boss state tied to fight progress** — the background image changes from healthy → damaged → defeated as you interact with GameGuide AI
- **Victory state** with rewards summary and a replay button

## Running locally
Just open `index.html` directly in Chrome (voice recognition requires a Chromium-based browser and mic permission).

## Hosting on GitHub Pages
1. Push this folder (`index.html` + `images/`) to a GitHub repo
2. Repo Settings → Pages → set source to your main branch, root folder
3. Your live link will be `https://<username>.github.io/<repo-name>/`

## Notes
- Boss images are original AI-generated/stock assets, licensed for this use
- Voice recognition requires HTTPS or localhost — GitHub Pages serves over HTTPS, so it will work there; if testing locally via a plain `file://` path, some browsers may block the mic prompt (see in-app note if that happens)
