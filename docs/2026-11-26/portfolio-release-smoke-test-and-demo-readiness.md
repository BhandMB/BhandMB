# Portfolio Release Smoke Test and Demo Readiness

## Purpose
Provide a repeatable pre-demo check for public portfolio repositories.

## Repository checks
- README setup steps match the current source tree.
- Required runtime and dependency versions are documented.
- No secrets, local database files, generated binaries, or personal environment files are committed.
- Main branch contains the intended demo revision.
- License and third-party asset attribution are clear.

## Functional smoke checks
For each project, identify one critical happy path and one meaningful failure path. Run the documented commands from a clean environment where practical. Record the exact revision and actual outcomes.

## Demo preparation
Prepare sample data that contains no real personal information. Reset the demo to a known state before recording. Verify screenshots and walkthrough steps against the current application.

## Interview readiness
Be prepared to explain architecture, one difficult bug, validation, error handling, persistence, authorization, and a realistic next improvement. Distinguish implemented behavior from planned enhancements.

## Sign-off
Record reviewer, date, commit reference, checks executed, failures, and known limitations. Never label a project production-ready based only on a successful local startup.
