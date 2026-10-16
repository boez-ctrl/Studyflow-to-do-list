# StudyFlow PWA starter — icon and offline fix

Upload every file in this folder to the ROOT of your existing GitHub repository, replacing files with the same names and adding `icon-192.png` and `icon-512.png`.

Files: `index.html`, `manifest.json`, `sw.js`, `icon.svg`, `icon-192.png`, `icon-512.png`, `README.md`.

Then wait for GitHub Pages to redeploy. Open the GitHub Pages URL in Chrome while online and leave it open briefly so the service worker can cache the app. Test offline by turning on Airplane mode and reopening StudyFlow.

If an old home-screen shortcut still shows the G icon, remove that shortcut and add StudyFlow to the home screen again from Chrome after the new version loads. Browser caching may delay the new icon. The app's tasks are stored in that browser/device, so they do not automatically sync between devices. Offline availability requires the app to have been loaded once while online.
