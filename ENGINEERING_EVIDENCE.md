# Engineering Evidence

This repository is the profile index for the BhandMB project portfolio.

## What the projects demonstrate

| Repository | Evidence |
| --- | --- |
| employee-management-system | Spring Boot, REST APIs, JPA/Hibernate, MySQL, RBAC, tests, Docker, GitHub Actions |
| book-library-api | REST API design, validation, exception handling, OpenAPI, MockMvc testing, GitHub Actions |
| book-library-app | Spring Boot MVC, Thymeleaf, server-side rendering, application testing, GitHub Actions |
| MiniATM | Core Java, OOP, validation, transaction-state handling, GitHub Actions compilation checks |
| LogoGuessApp | Android gameplay, UI interaction, accessibility and regression documentation |

## CI evidence

The Java projects with automated workflows use repository-local GitHub Actions definitions:

- employee-management-system: .github/workflows/ci.yml runs Maven verification and a Docker image build.
- book-library-api: .github/workflows/ci.yml runs the Maven verification lifecycle on Java 17.
- book-library-app: .github/workflows/ci.yml runs Maven verification on Java 17.
- MiniATM: .github/workflows/ci.yml compiles the Core Java application with Java 17.

The workflows use read-only repository permissions and cancel superseded runs on the same branch or pull request, keeping CI feedback focused on the latest change.

## Review standard

Portfolio changes should provide at least one concrete engineering signal: executable code, automated tests, CI/CD configuration, dependency hygiene, reproducible documentation, or a clearly scoped quality improvement.

Avoid empty commits, duplicate checklists, and changes that do not improve the project's maintainability or evidence of engineering practice.
