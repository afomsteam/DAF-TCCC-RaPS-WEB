# APK 2.21.0 ↔ Web 2.21.0-web.1 Synchronization Report

The web build is generated from the APK v2.21.0 `www` evaluator bundle, with only web/PWA-specific adaptations layered on top.

## Files intended to match APK evaluator logic/content

- `tiers.js` — identical
- `styles.css` — identical
- `branding.js` — identical
- `installations.js` — identical

## `app.js` difference

The web copy contains the same APK evaluator/data logic plus a small web-only bootstrap that registers `sw.js` and requests persistent browser storage.

## `index.html` differences

Only platform presentation/deployment differences are intentional:

- Web/PWA wording instead of Android wording.
- Browser-local-storage warning instead of Android app-data warning.
- Version query strings on CSS/JS assets.
- `installations.js` is versioned and loaded before `app.js`.

## Web-only files/behavior

- `sw.js` — offline PWA cache.
- `.nojekyll` — direct GitHub Pages static serving.
- Branch-based GitHub Pages deployment; no Android/Capacitor/Gradle workflow.

## Version mapping

- Android: `2.21.0`, versionCode `22100`
- Web/PWA: `2.21.0-web.1`, versionCode `22100`
