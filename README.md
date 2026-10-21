# Warsh Mushaf · Al-Fatiha & Al-Baqarah

An installable, offline-capable PWA of the Warsh mushaf (single self-contained `index.html`).

## Hosting
Serve over HTTPS (required for install). With GitHub Pages: Settings → Pages → deploy from branch, root folder.

## Install on Android
Open the Pages URL in Chrome → menu (⋮) → **Install app** / **Add to Home screen**.

## Features
- Page images are separate files in `pages/` (HTML is ~35 KB) and are saved on the device after the first visit for full offline reading.
- Day / Warm / Night reading tones plus a dim slider (`N` key cycles tone).
- Update prompt when a new version is deployed (bump `SHELL` in `sw.js` to ship one).
- Install button, home-screen shortcuts (Al-Fatiha, Al-Baqarah, Bookmarks), keep-screen-on, orientation lock.
