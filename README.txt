# Deriv Digit Scanner Pro PWA

Upload the contents of this folder to the ROOT of a new GitHub repository.

Files:
- index.html
- manifest.json
- sw.js
- favicon.png
- icons/icon-192.png
- icons/icon-512.png

The scanner logic is preserved from the supplied HTML. The added PWA files make it installable from GitHub Pages as a standalone app.

Important:
- GitHub Pages must be enabled for the repository.
- The site must be opened over HTTPS.
- The PAT remains in browser localStorage as implemented by the original scanner.
- Live Deriv API/WebSocket traffic is deliberately not cached by the service worker.
