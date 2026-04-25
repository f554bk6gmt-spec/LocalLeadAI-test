# LocalLead AI — Accessible Login v3

New in this version:
- Better mobile-first design
- More accessible labels, focus states and larger tap targets
- Dark mode
- Local PIN login
- Staff labels
- Business analysis and same-category comparison
- Monthly updates through Analysis month selector
- Export/import backup
- Force refresh button for iPhone PWA cache

## Important login note

This GitHub Pages version uses a local PIN stored on the device/browser. It is useful for demos and preventing casual access on the same phone, but it is not a real secure cloud login.

For real accounts across multiple staff/devices, connect a backend authentication system such as Firebase Auth or Supabase Auth and store leads in a cloud database.

## Upload

Upload these files to the root of your GitHub repository:
- index.html
- manifest.json
- service-worker.js
- icon-192.png
- icon-512.png
- README.md

Then use Settings → Pages → Deploy from a branch → main / root.
