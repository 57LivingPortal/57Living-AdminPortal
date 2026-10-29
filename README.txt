57LIVING MOBILE HOME-SCREEN ICON (GitHub Pages)

Files included:
- index.html: landing page with an Open Admin Portal button
- manifest.json: PWA metadata and icon sizes
- service-worker.js: caches the public app shell only
- icon-192.png / icon-512.png / apple-touch-icon.png / favicon-32.png: small logo assets

IMPORTANT BEFORE PUBLISHING:
1. Open index.html and replace the href value:
   https://script.google.com/macros/s/REPLACE_WITH_YOUR_DEPLOYMENT_ID/exec
   with your existing full Apps Script /exec URL.
2. Do not add passwords, tenant data, Admin_Users data, or Apps Script source code to this public repository.
3. Enable GitHub Pages in the repository settings (Deploy from branch: main, folder: /(root)).
4. Wait for the Pages URL to be published, open that URL on Android Chrome, then use Chrome menu > Add to Home screen.
5. The home-screen icon opens this landing page; tap Open Admin Portal to reach the existing Apps Script portal. This avoids claiming that GitHub Pages can host or replace the Apps Script backend.

This is a static launcher/icon shell, not a replacement backend. It does not add push notifications or change existing authentication.
