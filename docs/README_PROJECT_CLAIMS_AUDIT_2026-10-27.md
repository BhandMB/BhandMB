# README Project Claims Audit Checklist

**Date:** 2026-10-27  
**Purpose:** Keep portfolio descriptions accurate, consistent, and interview-defensible.

## Claim-by-claim audit

For every feature or technology named in a README, confirm:

- [ ] The dependency/configuration exists in the repository, if claimed as integrated.
- [ ] The feature can be demonstrated or its behavior is covered by tests.
- [ ] The setup instructions reflect the current branch and supported runtime.
- [ ] Version numbers match build files and lockfiles where applicable.
- [ ] “Implemented,” “in progress,” and “planned” are clearly distinguished.
- [ ] Performance/security claims include a reproducible method or are removed.
- [ ] Demo credentials, if provided for a local demo, are clearly marked as disposable and not reused anywhere.
- [ ] No secrets or personally identifying operational details appear in examples.

## Java backend interview readiness

Be ready to explain one design decision, one validation rule, one failure-handling path, one persistence interaction, and one test for each major project. If a technology is only a learning goal, list it under learning rather than presenting it as production experience.

## Maintenance cadence

Revisit this checklist after substantial feature changes, dependency upgrades, or README rewrites. Update the evidence links at the same time as the claims.