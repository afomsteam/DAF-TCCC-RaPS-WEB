# TCCC Evaluation Suite — Web/PWA

**Release:** v2.20.0-web.1  
**Role:** Installable/offline-capable web evaluator plus local class analytics/management surface

This repository is a plain static GitHub Pages application. It intentionally contains **one workflow only** (`.github/workflows/pages.yml`) and requires no npm, Node build, Capacitor, Java, Gradle, or Android project.

## Synchronized with APK v2.20.0
The evaluator/data model is synchronized with the Android v2.20.0 baseline, with platform-specific PWA/service-worker behavior only.

### v2.20 evaluator improvements
- Field Mode / Review Mode progressive disclosure.
- Critical FAIL requires structured failure mode + primary contributor.
- Noncritical FAIL remains one-tap and can be classified during review.
- A2 remediation reason and corrective action.
- Collapsible evaluator header.
- Roster search and operational filters.
- Existing modal fix, grading-state colors, Next Unresolved, NT justification, timer recovery, and finalization safeguards retained.

### Performance intelligence
- First-attempt vs final qualification.
- Remediation rate/success and repeat failure.
- Critical-failure rate and median attempts to proficiency.
- Normalized criterion failure rate: `FAIL / (PASS + FAIL)`.
- Scenario coverage and high-NT criteria.
- Root-cause / failure-mode distributions.
- Student competency heat map and descriptive comparison.
- Descriptive evaluator pattern signals (not inter-rater agreement).
- Performance Analytics CSV for DAF backend/analytics ingestion.

## GitHub Pages deployment
Push to `main`. The `pages.yml` workflow validates the static release, stages only the web files, and deploys directly to GitHub Pages.

The service worker uses a release-specific cache (`2.20.0-web.1`) so previous shells are replaced when the new service worker activates.

## Intentionally deferred to the DAF backend
The PWA does not pretend to provide enterprise authoritative records, MAJCOM/USAF aggregation, RBAC, identity assurance, server-side integrity, cross-device synchronization, or longitudinal enterprise readiness. The v2.20 schema/exports are designed to support those capabilities when the DAF backend is connected.

## Clinical/content note
The approved tourniquet-conversion criterion uses **“Wound could be closely monitored.”** Existing source provenance remains visible in Review Mode. Formal standards supersession/version governance should be controlled by the responsible program authority rather than silently inferred by this app.

**Contact: John Garcia**
