# Conventions

This file defines the shared rules all agents must follow in this project.

## Specs output convention

All planning, design, and investigation output MUST be written to `specs/` at the project root. The `specs/` directory is the persistent memory of the project. It contains:

| File | Purpose |
|------|---------|
| `CONTEXT.md` | Domain model, project state, architecture decisions |
| `UBIQUITOUS_LANGUAGE.md` | Glossary of domain terms |
| `SCOPE.md` | Scope definition (in/out) |
| `TASKS.md` | Task breakdown |
| `RELEASE-PLAN.md` | Implementation plan with verify steps |
| `REFACTOR.md` | Refactoring plan |
| `bugs/BUG-*.md` | Bug investigations |
| `bugs/BUG-LOG.md` | Bug log |
| `adr/` | Architecture Decision Records |

## Workflow

1. Read specs/ before any code change.
2. Use the appropriate bigpowers skill for each phase.
3. Write tests first (TDD) where applicable.
4. Verify every change before declaring done.
5. Commit using Conventional Commits format.

## Code quality

- Functions: 4–20 lines. Files: under 300 lines.
- Names must be grep-able (unique, specific).
- Tests verify behavior through public interfaces.
- Boy Scout Rule: leave files cleaner than you found them.

## Project-specific conventions

- Stack-specific README files named `{stack}-README.md` (e.g. `swift-README.md`)
- All guides follow the 15-section Kickass README template
- Markdown formatting: standard GitHub Flavored Markdown

## Never-do

- Never write code without a corresponding plan in specs/
- Never push directly to main or master
- Never refactor, rename, or reorganize outside the explicit task scope
- Never skip verification (tests, lint, typecheck)
- Never add dependencies without explicit approval
- Never write tests that depend on external services or network
- Never commit secrets, API keys, or credentials
- Never use force-push
- Never modify CI/CD configuration without separate approval

## Defensive code categories

None — this is a Markdown-only documentation project with no runtime code.
