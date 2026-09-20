5×15 iPad PWA – offline prototype

This package is an offline-first Progressive Web App. It stores the current game locally and caches the app for offline use after the first successful load.

IMPORTANT: Safari only allows a service worker/PWA installation from HTTPS (or localhost). Opening index.html directly from Files may display the page but will not install the offline service worker.

Easiest deployment:
1. Upload these four files to any HTTPS static host (GitHub Pages, Netlify, Cloudflare Pages, etc.).
2. Open the HTTPS address in Safari on the iPad.
3. Tap Share -> Add to Home Screen.
4. Launch from the new 5×15 icon. After the first load, it can work offline.

The game implements the core published description of 5×15: a 5×15 tableau containing five colours and values 1–15, one gap in each row, starting with the five 1s on the left; tiles are placed into gaps when they continue a same-colour ascending sequence. This is an initial digital implementation and may need refinement for the publisher's full special shift rules.
