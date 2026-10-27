THE IRISH EXIT — INSTALLATION

1. Create a free GitHub account if needed.
2. Create a PUBLIC repository named the-irish-exit.
3. Upload the contents of this ZIP to the repository ROOT (not a nested folder).
4. In repository Settings > Pages, choose Deploy from a branch, main, /(root), Save.
5. Wait for GitHub to publish: https://YOURUSERNAME.github.io/the-irish-exit/
6. On the Galaxy Tab A7 Lite, open that HTTPS URL in Chrome while connected to Wi-Fi.
7. In Chrome menu, choose Add to Home screen / Install app (wording varies).
8. Open from the new icon. After a full online load, turn on Airplane Mode and test browsing.

To update inventory: edit drinks.json, commit changes, reconnect tablet, and reload online.
If a device still displays an old version, change the CACHE value in sw.js from irish-exit-v1 to irish-exit-v2 before publishing.

PHOTOS (v2): Each drink can show a photo. See PHOTO-LIST.txt for the exact file name for every drink.
Upload photos to the repository root (next to index.html). Drinks without a photo keep their symbol.
Photos are saved for offline use after the tablet loads the menu once while online.
If you REPLACE a photo using the same file name, bump the CACHE value in sw.js (e.g. irish-exit-v3) so tablets pick it up.

NOTE: No guest-facing recipes or measurements are included. Fonts fall back to local fonts offline.
GitHub Pages public repositories are publicly visible; don't include personal information.
