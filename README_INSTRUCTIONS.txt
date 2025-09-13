QUICK ENTRY – iPhone install steps (PWA)
======================================
Last updated: 2025-09-13T10:18:45.016521Z

1) Download and unzip this folder somewhere in your iCloud Drive or local Files app.
2) You need to host the files over HTTPS to Add to Home Screen on iOS:
   • Easiest: GitHub Pages
     - Go to github.com in Safari → sign in (or create account).
     - Create a new repository, e.g. quickentry.
     - Tap "Add file" → "Upload files" → select index.html, manifest.webmanifest, service-worker.js, icons/.
     - Commit the changes.
     - Open Repo → Settings → Pages → "Branch: main / root" → Save.
     - Wait ~1 minute. Your URL will be: https://<yourname>.github.io/quickentry/
   • Alternative: Netlify Drop (app.netlify.com/drop) → upload the same files → it gives you a https URL.

3) Open your new URL in Safari on the iPhone.
4) Tap the Share button → "Add to Home Screen" → Add.
5) Launch from the new icon. It will load once, then work fully offline.

Notes:
- Camera input works inside the PWA.
- CSV export downloads a file to your device.
- For push notifications you’d need a server (not included).
- To change fields or branding, edit index.html.
