# TCCC Evaluation Suite — Web/PWA v2.21.0-web.1

This is the complete static GitHub Pages/PWA repository synchronized to the Android APK **v2.21.0** evaluator/data model.

## Synchronized capabilities

- Identical Tier 1–4 checklist data to APK v2.21.0
- Structured failure-mode/root-cause capture
- Critical-failure RCA completion safeguard
- Remediation reason/action and first-pass vs final-pass analytics
- Field Mode / Review Mode
- Roster filters and competency heat map
- MAJCOM / command catalog
- Home installation vs training-location separation
- Supported command vs installation host-command distinction
- Legacy installation alias migration
- Multi-class management filters: MAJCOM, installation, tier, course type
- MAJCOM and installation rollups
- RCA by command / installation
- Normalized criterion failure rates
- Data-quality indicators for missing command/base/RCA metadata
- Analytics-ready enterprise-detail export schema
- Contact: John Garcia only

## Platform-specific web behavior

The web version uses browser-local storage and an offline-capable service worker. It does not use Android, Capacitor, Gradle, npm, or a GitHub Actions build.

## GitHub Pages deployment

This repository is intentionally a static site.

1. Upload the repository contents directly to the root of `DAF-TCCC-WEB`.
2. Delete any obsolete `.github/workflows/pages.yml` or Android/APK workflows if they still exist in GitHub.
3. GitHub → **Settings → Pages**.
4. **Source:** Deploy from a branch.
5. **Branch:** `main`.
6. **Folder:** `/(root)`.
7. Save.

The repository includes `.nojekyll` so GitHub Pages serves the static files directly.

Expected visible version: **2.21.0-web.1**.
