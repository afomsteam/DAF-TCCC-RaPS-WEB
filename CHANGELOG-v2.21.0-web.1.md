# v2.21.0-web.1

Web/PWA synchronization release for Android APK v2.21.0.

## Added from the 2.21 Android baseline

- Structured MAJCOM / command and installation catalog (`installations.js`).
- MAJCOM-filtered installation selection with all-installations override.
- Separate supported/operational command and installation host-command semantics.
- Home installation, unit, training location, exercise/event, scenario profile and difficulty metadata.
- Legacy location alias migration into stable installation identifiers where possible.
- Program Management Intelligence dashboard across locally held classes.
- Filters by command, installation, tier and course type.
- Command and installation rollups for first-pass, final-pass, remediation, critical failure and RCA completeness.
- Location-aware RCA analysis and normalized competency-gap analysis.
- Data-quality indicators for missing command, home installation, custom installation and missing RCA.
- Enterprise-detail analytics export schema carrying structured location + RCA + remediation metadata.

## Preserved from v2.20

- Field / Review Mode.
- Structured failure modes and contributors.
- Required RCA for critical failures.
- Remediation analytics.
- First-pass vs final qualification.
- Competency heat map.
- Roster operational filters.
- Evaluator descriptive signals.
- Modal positioning hardening, Next Unresolved workflow and TCCC clinical criteria.

## Web-specific

- Offline PWA service worker now caches `installations.js` as part of the versioned evaluator shell.
- Browser-local-storage warning retained.
- Static branch-based GitHub Pages deployment retained; no Node/npm/Actions build required.
