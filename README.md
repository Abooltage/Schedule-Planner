# Daily Schedule — PWA

Plain HTML/JS/React (no build step). Fully yours, fully editable — open `index.html` in any text editor to change it.

## Get it on your phone (2 minutes, free)

A PWA needs to be served over `https://` for "Add to Home Screen" and offline mode to work properly — you can't just open the file directly on your phone. Easiest free option:

**Netlify Drop**
1. Go to https://app.netlify.com/drop on your computer
2. Drag this whole folder onto the page
3. You'll get a live link like `https://random-name-123.netlify.app`
4. Open that link on your phone in Safari (iOS) or Chrome (Android)
5. iOS: tap Share → **Add to Home Screen**. Android: Chrome will prompt **Install app** automatically (or menu → Install app)

That's it — it now behaves like a real app: own icon, own window, works offline, no browser bar.

## Editing it later

Everything lives in `index.html` — one file, plain React written with JSX. Ask me to change anything ("add a dark mode," "let me drag tasks to reorder," "sync across devices") and I'll edit the file directly. Re-upload/re-drag the updated folder to Netlify to push changes.

## Files
- `index.html` — the whole app
- `manifest.json` — app name/icon/colors for install
- `service-worker.js` — offline caching
- `icon-192.png`, `icon-512.png` — app icons

## Notes
- Data is stored in the browser's local storage on your phone — it stays even if you close the app, but it's device-specific (not synced to the cloud). If you want cross-device sync later, that's a good next step and just needs a small backend.
