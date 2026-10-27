TRADE & TILL — iPHONE + MAC INSTALL PACKAGE

FILES
- index.html: the game
- manifest.json: home-screen app information
- service-worker.js: offline caching after first online visit
- icons/: home-screen icons

IMPORTANT
To install as an app on iPhone, these files must be hosted at an HTTPS website. Opening index.html directly from Files is fine for a quick test, but iOS will not offer the full Add to Home Screen app experience from a local file.

SIMPLE FREE HOSTING OPTION: GITHUB PAGES
1. Sign in or create an account at https://github.com
2. Create a new public repository, e.g. trade-and-till.
3. Upload the CONTENTS of this folder (index.html, manifest.json, service-worker.js, icons folder) to the repository root.
4. In the repository, open Settings → Pages.
5. Under Build and deployment, choose Deploy from a branch, select main and /(root), then Save.
6. Wait for GitHub Pages to provide your HTTPS website address.
7. Open that address in Safari on iPhone.
8. Tap Share → Add to Home Screen → Add.
9. Open the new Trade & Till icon from the Home Screen. After the first online load, the game shell can work offline.

On Mac, open the same HTTPS address in Safari or Chrome. Saves are stored separately in each browser/device; local saves do not automatically sync between iPhone and Mac.
