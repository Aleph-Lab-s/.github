# Contributing to Aleph Labs

Aleph Labs values deliberate engineering over uncontrolled change.

## Before proposing work

Understand:

1. the repository's purpose
2. its architectural boundaries
3. its source of truth
4. its security requirements
5. its current maturity

Do not introduce a new repository, integration, service, or dependency merely because it is convenient.

## Changes

Changes should be:

- scoped
- reviewable
- tested
- documented where appropriate
- compatible with repository architecture
- explicit about security and operational consequences

## Security-sensitive work

Security-sensitive changes require additional review and must not weaken existing security boundaries for convenience.

## Source of truth

Do not create competing implementations or undocumented alternate sources of truth.

If an architectural source of truth exists, changes must respect it.

## Pull requests

Pull requests should explain:

- what changed
- why it changed
- what was tested
- known limitations
- security implications
- operational implications

Large architectural changes should be discussed before implementation.

## Maturity

Do not describe functionality as production-ready without appropriate evidence.

Use explicit maturity language such as:

`PLANNED` → `SKELETON` → `IMPLEMENTED` → `TESTED` → `VALIDATED` → `PRODUCTION-READY` → `INDEPENDENTLY-REVIEWED`
