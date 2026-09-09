# Validation Report — v2.21.0-web.1

**Result: 69/69 checks passed.**

## APK synchronization

- `tiers.js`: byte-for-byte identical to APK 2.21.0
- `styles.css`: byte-for-byte identical
- `branding.js`: byte-for-byte identical
- `installations.js`: byte-for-byte identical
- `app.js`: same evaluator/data logic; web adds only service-worker registration and persistent-storage request.

## Catalog/content counts

- Installation records: **73** active-duty records across **11** command categories.
- Tier 1: **33 criteria / 17 critical / 2 timers**
- Tier 2: **71 / 16 / 2**
- Tier 3: **124 / 28 / 7**
- Tier 4: **124 / 30 / 9**

## Release checks

- [x] required file: index.html
- [x] required file: app.js
- [x] required file: styles.css
- [x] required file: tiers.js
- [x] required file: branding.js
- [x] required file: installations.js
- [x] required file: version.js
- [x] required file: sw.js
- [x] required file: manifest.webmanifest
- [x] required file: .nojekyll
- [x] required file: README.md
- [x] required file: DEPLOYMENT.md
- [x] HTML reference exists: app.js
- [x] HTML reference exists: assets/app-icon.png
- [x] HTML reference exists: assets/icon-192.png
- [x] HTML reference exists: branding.js
- [x] HTML reference exists: installations.js
- [x] HTML reference exists: styles.css
- [x] HTML reference exists: tiers.js
- [x] HTML reference exists: version.js
- [x] HTML id present: managementMajcom
- [x] HTML id present: managementInstallation
- [x] HTML id present: managementTier
- [x] HTML id present: managementCourseType
- [x] HTML id present: managementKpis
- [x] HTML id present: managementMajcomTable
- [x] HTML id present: managementInstallationTable
- [x] HTML id present: managementDataQuality
- [x] HTML id present: enterpriseAnalyticsCsvBtn
- [x] HTML id present: newClassBtn
- [x] HTML id present: rosterSearch
- [x] HTML id present: nextUnresolvedBtn
- [x] HTML id present: nextUnresolvedBottomBtn
- [x] visible web platform
- [x] versioned installations.js
- [x] versioned app.js
- [x] web version 2.21.0-web.1
- [x] web target marker
- [x] SW version aligned
- [x] SW cache aligned
- [x] SW caches installations.js
- [x] no .github directory
- [x] no package.json
- [x] no capacitor config
- [x] MAJCOM management
- [x] Installation management
- [x] RCA completeness
- [x] Data quality
- [x] Normalized gap
- [x] Remediation success
- [x] Enterprise detail export
- [x] Field/Review mode
- [x] Critical failure RCA requirement
- [x] Legacy installation inference
- [x] John Garcia contact configured
- [x] no mailto
- [x] no tel links
- [x] APK parity: tiers.js
- [x] APK parity: styles.css
- [x] APK parity: branding.js
- [x] APK parity: installations.js
- [x] app.js evaluator logic parity
- [x] JS syntax: app.js
- [x] JS syntax: tiers.js
- [x] JS syntax: branding.js
- [x] JS syntax: installations.js
- [x] JS syntax: version.js
- [x] JS syntax: sw.js
- [x] installation catalog present
