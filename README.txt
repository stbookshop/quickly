ST BOOKSHOP - PWA dashboard

Files
  index.html            the dashboard
  manifest.webmanifest  makes it installable
  sw.js                 offline support
  icons/                app icons
  apps/                 put your html web apps here

How it works
  A PWA can only be installed when it is opened from https:// (for example GitHub Pages)
  or from http://localhost. Double-clicking index.html will NOT install it.

Option A: GitHub Pages (works on phone and PC, but the files are public)
  1. Create a GitHub repo, upload everything in this folder (keep the apps folder).
  2. Repo > Settings > Pages > Branch: main > Save.
  3. Open https://YOURNAME.github.io/REPO/ in Chrome, Edge or Brave.
  4. Settings > Install app (or the install icon in the address bar).

Option B: only on this PC (private)
  1. Install Python, open a terminal in this folder and run:  python -m http.server 8080
  2. Open http://localhost:8080 in Brave and install it.
  The terminal must be running whenever you use the dashboard.

Adding apps
  Open Settings (password is created the first time), + Add app, type only the file name,
  for example billing.html. The Apps folder is already set to "apps".

Data note
  The data an app saves lives in the browser of the device where it was used, per web address.
  A new address (for example github.io) starts empty. Back up with each app's export.
  Anything you upload to a public repo can be read by anyone, including the dashboard code.
