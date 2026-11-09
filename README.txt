PRACTICE METRONOME — WORKING WEB APP

WHAT IT INCLUDES
- Working Web Audio metronome with selectable BPM 30–240, +/- tempo buttons,
  beats per bar (1–12), subdivisions (1–4), accents, tap tempo, and volume.
- Four independent timers: Timer 1 focus countdown (default 3 min),
  Timer 2 total practice stopwatch, and two unnamed optional countdown timers.
  All timer names are editable. A repeat option is available for countdowns.
- Pause All / Resume All; optional pause of metronome with session.
- Finish & save, with a label and notes.
- Practice Record with daily totals, goal ring, weekly chart, session detail,
  editing and deleting records.
- Export JSON backup, CSV, and import JSON.
- Separate metronome volume and completion-chime volume.
- Offline support as a PWA if served over HTTPS or localhost.

START USING IT
1. Open index.html in a modern browser. No installation, build step,
   account, subscription, or internet access is needed to use the single
   HTML file.
2. If opening the HTML through a phone's Files application does not allow
   interactive scripts or persistent storage, upload the whole folder to
   an HTTPS static host (for example a personal website, GitHub Pages,
   or Netlify) and open its link in Safari/Chrome. Install by choosing
   Add to Home Screen / Install App.
3. Practice data is kept locally in the browser; export backups regularly.

IMPORTANT LIMITATIONS
- This is a complete standalone WEB APP, not an Android APK/iOS App Store app.
  It does not modify or replace the source code of your existing app.
- Browsers may suspend JavaScript and/or audio when the app is in the
  background or the display turns off. Elapsed timer values are corrected
  from wall-clock times on resume, but persistent background metronome
  sound and exact timer notifications cannot be guaranteed in browsers.
- File:// browser storage behavior differs by platform. Use a secure hosted
  URL for reliable installable PWA/offline storage.
- This app has not been integrated with any external calendars or logins.

FILES
index.html - complete standalone app
manifest.webmanifest - PWA metadata
service-worker.js - offline cache for hosted mode
icon-192.png, icon-512.png - app icons

No external frameworks, tracking, network APIs, or third-party dependencies.
