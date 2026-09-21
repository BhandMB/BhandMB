# Portfolio Change Review

Use this checklist before merging a change into any portfolio repository.

## Evidence

- [ ] The change improves behavior, reliability, maintainability, or documentation.
- [ ] The README and setup instructions still match the implementation.
- [ ] Any new dependency, command, environment variable, or endpoint is documented.
- [ ] The change can be demonstrated in an interview with a concrete example.

## Validation

- [ ] A focused test or repeatable manual verification step exists.
- [ ] Failure behavior is described, not only the happy path.
- [ ] No secrets, local paths, generated binaries, or machine-specific files were committed.
- [ ] The commit message explains the user-visible or engineering value.

## Review outcome

Record the repository, file(s), validation performed, and follow-up work before considering the change complete.
