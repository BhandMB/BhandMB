# Java Spring Boot Repository Review Checklist

**Date:** 2026-10-29  
**Purpose:** Review a Java backend repository for reproducibility, maintainability, and interview readiness.

## Build and runtime

- [ ] Java version agrees across build files, README, and CI.
- [ ] Wrapper or setup instructions work from a clean checkout.
- [ ] Required environment variables are documented with safe examples.
- [ ] Build failures are distinguishable from application startup failures.

## Code and API

- [ ] Controllers delegate business logic to services.
- [ ] DTOs prevent accidental exposure or modification of internal fields.
- [ ] Validation and exception responses are consistent.
- [ ] Database constraints support important invariants.
- [ ] Security rules cover both routes and resource ownership where needed.

## Testing and delivery

- [ ] Unit and integration tests cover meaningful business behavior.
- [ ] CI runs the documented build and test commands.
- [ ] Logs and sample configuration contain no secrets.
- [ ] README accurately distinguishes implemented features from planned work.
- [ ] Deployment claims have reproducible evidence.

## Review output

For each finding, record severity, evidence path, reproduction steps, and a practical next action. Do not label an item fixed until the change has been verified.