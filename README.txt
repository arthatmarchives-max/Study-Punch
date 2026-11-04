STUDY PUNCH — GitHub Pages PWA

Files:
- index.html: your Study Punch app
- manifest.json: installable app details
- sw.js: offline caching service worker
- icons/: app icons made from your supplied image

Publish:
1. Create a new public GitHub repository named study-punch (or your preferred name).
2. Upload the CONTENTS of this folder to the repository root. Make sure index.html is at the top level, not inside another folder.
3. In Settings → Pages, choose Deploy from a branch → main → /(root) → Save.
4. Wait for the Pages deployment, then open the published URL in Chrome.
5. On Android Chrome, use the browser menu → Install app (or Add to Home screen).

Notes:
- Keep the app and its supporting files together in the repository root.
- The service worker and manifest use relative paths, so they work under a GitHub Pages project URL.
- Google Fonts still need an internet connection. The app shell and files are cached after the first successful visit.
- Study data uses this browser's localStorage; it does not automatically sync between devices.
