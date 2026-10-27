TradeLog PWA installable package

Upload/replace these files in the ROOT of your GitHub repository jurnalbacot/tradelog:
- index.html (replace existing)
- manifest.webmanifest (new)
- sw.js (new)
- icon-192.png (new)
- icon-512.png (new)

Commit the changes and wait for GitHub Pages to publish. Then open https://jurnalbacot.github.io/tradelog/ in Chrome Android, refresh the page, and use menu (three dots) > Install app. If it still shows unavailable, wait a few minutes and reload once.

This package keeps the current TradeLog HTML and Google Sheets settings; it adds PWA metadata, icons, service worker, and mobile header layout. Keep a backup of index.html and your local journal data before replacing files. Do not upload Kode.gs or expose new secrets in the repository.
