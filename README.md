# Daybook

A daily journal — calendar, mood tracking, tasks, and voice memos — as a static, installable web app.

## Files
- `index.html` — the app
- `manifest.json` — PWA manifest (enables "install to home screen")
- `service-worker.js` — caches the app shell for offline access
- `icons/` — app icons

## Deploy
This is a static site with no build step. Push these files (at the repo root) to GitHub, then import the repo into Vercel with Framework Preset set to "Other" and no build command.

## Data
Entries are saved to the browser's local storage, per device/browser. Clearing site data or switching browsers/devices will not carry entries over.
