# 75 Days Tracker

A private, self-contained 75-day challenge tracker. Set your own daily tasks,
check them off, and build your streak. All data stays on your device
(localStorage) — nothing is sent anywhere.

## Files
- `index.html` — the whole app
- `manifest.json` — makes it installable as a home-screen app (PWA)
- `sw.js` — service worker, lets it work offline once installed
- `icon-192.png`, `icon-512.png` — app icons

## How to put this online with GitHub Pages (free, ~5 minutes)

1. **Create a GitHub account** if you don't have one: https://github.com/join

2. **Create a new repository**
   - Go to https://github.com/new
   - Name it something like `75-days` (the name doesn't matter much)
   - Set it to **Public**
   - Don't add a README/license here — leave it empty
   - Click **Create repository**

3. **Upload the files**
   - On the new repo's page, click **"uploading an existing file"**
   - Drag in all 5 files from this folder (`index.html`, `manifest.json`,
     `sw.js`, `icon-192.png`, `icon-512.png`)
   - Scroll down, click **Commit changes**

4. **Turn on GitHub Pages**
   - Go to the repo's **Settings** tab
   - Click **Pages** in the left sidebar
   - Under "Build and deployment" → **Source**, choose **Deploy from a branch**
   - Branch: choose **main**, folder: **/ (root)** → **Save**
   - Wait about 1 minute. Refresh the page — you'll see a banner with your
     live URL, something like:
     `https://yourusername.github.io/75-days/`

That URL is permanent and free. Anyone with the link can open it (it's a
public page, but the only data is what's stored locally in *their own*
browser — your check-ins aren't visible to anyone else, including you on
a different device, since nothing is synced to a server).

## Adding it to your phone's home screen

**iPhone (Safari):**
1. Open your GitHub Pages link in Safari
2. Tap the **Share** icon (square with an arrow) at the bottom
3. Scroll down and tap **Add to Home Screen**
4. Tap **Add**

**Android (Chrome):**
1. Open your GitHub Pages link in Chrome
2. Tap the **⋮** menu (top right)
3. Tap **Add to Home screen** (or you may see an "Install app" banner — tap that instead)
4. Tap **Add** / **Install**

Once added, it opens full-screen like a real app — no browser address bar,
own icon, works offline after the first visit.

## Notes
- Your progress is stored only in that browser on that device. If you open
  the link in a different browser or clear site data, you'll start fresh.
- If you ever want to update the app (e.g. I send you a new version), just
  upload the new files to the same GitHub repo, overwriting the old ones —
  your link stays the same.
