# Beatcraft Academy — Studio One Edition

A mobile-first music production learning app tailored for an intermediate producer who wants to work across genres in PreSonus Studio One.

## What's included
- 12 expanded, Studio One-focused lessons: routing, session setup, groove, MIDI, EQ, compression, sends/FX Channels, automation, reference tracks, low-end management, and a capstone project.
- Quick knowledge checks with explanations.
- Frequency explorer with a browser-generated test tone.
- Daily practice checklist and local progress tracking.
- Responsive dark UI suitable for Android and desktop.

## Preview
Open `index.html` in a modern browser. The test tone requires pressing Play tone and browser audio support. For reliable PWA installation, serve the app over HTTPS.

## Update an existing Beatcraft installation
1. Keep a backup of your current files and note that browser progress is stored separately in local storage.
2. Replace the old `index.html` with this version.
3. Keep `manifest.webmanifest`, `sw.js`, and `icon.svg` in the same directory.
4. If deployed using GitHub Pages, commit and push the changed files.
5. On Android Chrome, reopen the app. If the old version persists, close the installed app and refresh the website; a service worker cache may need to update. For a development deployment, change the cache name in `sw.js` (e.g. `beatcraft-v2`) before publishing.
6. Your browser-local progress should remain as long as you keep the same origin and do not clear site data. The new course has 12 lessons; old completion indices are retained, so review the new curriculum if you previously marked lessons complete.

## Install on Android
This is a PWA prototype, not an APK. Upload the folder to an HTTPS host such as GitHub Pages, open its URL in Chrome on Android, then use Chrome's menu and choose Install app or Add to Home screen (wording varies by version).

## Scope
This version is a practical educational prototype. It does not connect to Studio One or control it remotely. Menu labels and shortcut details can vary by Studio One version.
