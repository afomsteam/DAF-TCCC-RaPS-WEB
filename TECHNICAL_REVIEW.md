# v2.20 Technical Review Notes

## Product role
Android remains optimized for field collection. The web/PWA can provide local class analytics and program-management views, while planned DAF backend services should own enterprise aggregation and authoritative records.

## Measurement choices
- Criterion gaps use failure rate among tested observations, not raw fail counts.
- NT is separately reported as scenario/assessment coverage.
- First-attempt qualification is kept distinct from final qualification after remediation.
- Student comparison is competency/domain oriented rather than a leaderboard.
- Evaluator metrics are explicitly descriptive; they are not presented as inter-rater reliability without double-scored observations.

## Human-factors choices
- PASS remains one tap.
- Noncritical FAIL remains one tap; structured classification can occur during Review Mode.
- Critical FAIL requires classification at the moment of failure because it is a high-consequence event.
- Field Mode collapses documentation/provenance to preserve evaluator attention.

## Enterprise readiness boundary
v2.20 adds analysis-ready identifiers and exports but deliberately does not create a parallel enterprise system of record. Authentication, RBAC, retention, sync, record integrity, and enterprise comparisons should be implemented in the approved DAF backend architecture.
