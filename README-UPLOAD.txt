JUICE PRODUCTION TRACKER — PWA FILES

Upload these files into the ROOT of your GitHub repository:
  manifest.json
  service-worker.js
  icons/icon-192.png
  icons/icon-512.png

IMPORTANT: Your latest Firebase-enabled app is currently named:
  index (4).html

GitHub Pages opens index.html by default. Before uploading:
1. Open index (4).html in your GitHub repository.
2. Use the pencil/Edit button, select all its contents and copy.
3. Open index.html, select all old contents, paste the copied latest contents.
4. Commit the change. Keep the filename exactly index.html.
5. Do not delete index (4).html or change Firebase settings.

The latest index (4).html already contains:
  <link rel="manifest" href="./manifest.json">
and service-worker registration for ./service-worker.js.
The manifest and service worker in this ZIP use the GitHub Pages project path:
  /Juice-production/

After upload:
1. Wait until GitHub Pages finishes deploying.
2. Open https://salmanulfarisv-oss.github.io/Juice-production/ in Chrome.
3. Refresh the page. If Chrome still shows the old install status, clear the site's cached data
   in Chrome and reopen the site.
4. Open Chrome menu (⋮). Look for Install app. If Install is still unavailable,
   use Chrome DevTools/Lighthouse or send a screenshot of the page and menu.

DATA SAFETY:
- These files do not modify Firestore or Firebase data.
- Keep the Firebase project configuration in the latest index file unchanged.
- The service worker caches only the app shell; Firebase requests remain network requests.
