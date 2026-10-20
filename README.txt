MY WATCHLIST — OFFLINE APP PACKAGE

This package contains your 97-title watchlist as an installable Progressive Web App (PWA).

IMPORTANT: This ZIP is not an Android APK. Android Chrome requires the app to be served from an HTTPS website for the Install / Add to Home screen feature and offline service worker to work. After it is installed and opened once, the app shell can work offline. Your watch status is saved in that browser on that device.

Files:
- index.html: the watchlist app
- manifest.webmanifest: installable app details
- service-worker.js: offline caching
- icon.svg: home-screen icon

Setup: Upload the contents of this folder to an HTTPS static host (for example, GitHub Pages or Netlify), open the resulting HTTPS address in Chrome on your Android phone, then use Chrome menu (⋮) > Install app or Add to Home screen. Open the app once while online before using it offline.

For a truly standalone APK, this bundle would need to be wrapped and built with Android tooling; that build environment is not available in this chat.
