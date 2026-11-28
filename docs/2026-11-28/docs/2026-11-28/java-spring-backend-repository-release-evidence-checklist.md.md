# Java/Spring backend repository release evidence checklist

## Purpose
Create a concise evidence trail before presenting a backend portfolio project or tagging a release.

## Repository hygiene
Check that secrets, local databases, generated build output, personal IDE state, and temporary files are excluded. Confirm README setup instructions match the actual build files and supported Java version.

## Build and test evidence
Record the exact clean-build and test commands, tool versions, date, and result. Separate tests that were run from tests that are merely planned. Include database prerequisites and identify any tests requiring external services.

## API and security review
Verify endpoint examples, validation/error behavior, authentication setup, role restrictions, and negative authorization cases. Do not describe a security control as implemented unless code and tests support it.

## Release notes
Summarize user-visible changes, known limitations, migration requirements, and rollback considerations. Link to the relevant commits and workflow evidence.

## Interview accuracy
Keep claims about Docker, CI/CD, deployment, microservices, messaging, and test coverage proportional to repository evidence. A reproducible modest project is stronger than unsupported production-readiness claims.
