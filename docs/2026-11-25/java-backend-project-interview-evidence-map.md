# Java Backend Project Interview Evidence Map

## Purpose
Prepare a consistent, evidence-backed explanation of the portfolio projects for Java backend interviews.

## Core project narrative
For each project, explain the user problem, architecture, key domain entities, API boundaries, persistence model, validation strategy, and the most important engineering trade-off.

## Evidence to prepare
- Repository and setup instructions
- Java and Spring Boot versions actually used
- Representative controller, service, repository, and DTO examples
- Database schema and relationship explanation
- Authentication and authorization behavior
- Exception handling and API response examples
- Tests that can be run and their actual results
- Known limitations and next improvements

## Interview prompts
1. Why was the project structured into layers?
2. How does a request move from controller to database?
3. Where is validation performed and why?
4. How are transactions and failures handled?
5. How are roles and permissions enforced?
6. How would the application handle concurrent updates?
7. What would change when moving from a monolith to services?
8. Which design decision would you revisit and why?

## Accuracy rules
Distinguish implemented features from design proposals and planned work. Do not claim production deployment, performance results, test coverage, or technologies that cannot be demonstrated from the current repository.

## Practice routine
Give a two-minute project overview, then demonstrate one API flow and one failure path. Practice explaining the code without reading the README verbatim.
