# GitHub Portfolio Evidence Plan

**Date:** 2026-10-27  
**Purpose:** Help reviewers verify project claims quickly and honestly.

## Evidence to provide per project

- A concise problem statement and intended users.
- Architecture overview and main technology choices.
- Setup steps that work from a clean checkout.
- Configuration instructions using placeholders, never real secrets.
- Screenshots or a short demo showing the core user journey.
- API examples or a documented interface contract where relevant.
- Test command and the actual result from a recent run.
- Known limitations and next improvements.

## Quality rules

1. Separate implemented features from planned features.
2. Never label a test as passing unless it was run and the result was checked.
3. Remove local machine paths, personal tokens, credentials, and environment-specific assumptions.
4. Prefer a small reproducible demo over a long feature list with no proof.
5. Keep links to source folders, API docs, and test reports close to the relevant claims.

## Review order

Start with the README, then verify setup, core code, tests, and the latest meaningful change. Make sure repository descriptions and pinned repositories reflect the Java/Spring Boot backend direction without hiding other genuine work.