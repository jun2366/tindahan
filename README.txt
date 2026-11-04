TINDAHAN TRACKER - sari-sari store app (PWA)

Files: index.html, manifest.json, sw.js, icons. Keep them together in one folder.

HOW TO PUT IT ON YOUR PHONE
1. Host the folder on any HTTPS site (needed for install + offline). Easiest free options:
   - Netlify Drop: go to app.netlify.com/drop and drag this whole folder in. You get a link.
   - GitHub Pages: push the folder to a repo, Settings > Pages > deploy from main branch.
2. Open the link on your phone.
   - Android (Chrome): menu (3 dots) > Install app / Add to Home screen
   - iPhone (Safari): Share > Add to Home Screen
3. Done. It opens like a normal app and works even without internet after the first load.

IMPORTANT
- Data is saved on the phone itself (browser storage). It does not sync between phones.
- Use Backup tab > Download backup every week. Restore backup to move data to a new phone.
- Uninstalling the app or clearing Chrome site data can erase it, so keep backups.

UPDATING
- Edit index.html, then change VERSION in sw.js (e.g. tindahan-v2) and re-upload.
