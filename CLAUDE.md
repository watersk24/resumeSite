# Project Instructions

## Current Stage

This project is starting from an idea. Do not assume the architecture, framework, database, hosting platform, or package manager until they are explicitly selected.

## Development Principles

- Start with product goals before implementation.
- Prefer an MVP before advanced features.
- Make small, reviewable changes.
- Explain major tradeoffs before choosing a direction.
- Do not introduce frameworks, services, or dependencies without explaining why.
- Keep code simple, maintainable, and testable.
- Do not create fake production readiness. Clearly label assumptions and gaps.

## Agile Workflow

For new work, follow this sequence:

1. Clarify the idea.
2. Define users and value.
3. Create user stories and acceptance criteria.
4. Propose technical design options.
5. Select an MVP architecture.
6. Scaffold the project.
7. Implement one vertical slice.
8. Add tests.
9. Review code.
10. Review security.
11. Update documentation.
12. Check release readiness.

## Definition of Done

A feature is done when:

- Acceptance criteria are satisfied.
- Relevant tests are added or updated.
- Code follows project conventions.
- Security risks have been considered.
- Documentation is updated where needed.
- Known limitations are documented.

## Safety and Security

- Never commit secrets, tokens, passwords, private keys, or credentials.
- Use environment variables for sensitive configuration.
- Validate input at trust boundaries.
- Treat authentication, authorization, payments, and user data as high-risk areas.
