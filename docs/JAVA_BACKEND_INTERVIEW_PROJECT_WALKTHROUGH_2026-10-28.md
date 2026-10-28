# Java Backend Project Walkthrough Checklist

**Date:** 2026-10-28  
**Purpose:** Prepare concise, evidence-backed explanations of portfolio projects for interviews.

## Walkthrough structure

1. **Problem:** Who needs the application and what problem does it solve?
2. **Architecture:** Explain the request path from controller through service to repository/database.
3. **Data model:** Describe entities, relationships, constraints, and key queries.
4. **Validation:** Explain where invalid input is rejected and how clients learn what to fix.
5. **Security:** Describe authentication, role permissions, and resource-level access checks where implemented.
6. **Failure handling:** Walk through one expected error and one unexpected server error.
7. **Testing:** Name a real test, what it asserts, and the last command actually run.
8. **Trade-offs:** Explain one design choice and one limitation honestly.

## Evidence checklist

- [ ] Point to the exact source files for major claims.
- [ ] Demonstrate setup from a clean checkout where possible.
- [ ] Distinguish implemented features from plans.
- [ ] Avoid claiming production scale, deployment, or test coverage without evidence.
- [ ] Prepare a two-minute overview and a deeper technical explanation.