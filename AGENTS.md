# big-kickass-readme — OpenCode

Read CONVENTIONS.md before any GitHub or git operation.

## Project
Personal reference repository with stack-specific README writing guides, based on the Kickass README template from Akash.
Stack: Markdown only, no runtime

## Commands
| Action | Command |
|--------|---------|
| Run    | `n/a` |
| Test   | `n/a` |
| Build  | `n/a` |
| Lint   | `n/a` |

## Architecture
Stack-specific README guides (Swift, Vue/Vite/TypeScript, SvelteKit, Astro, Go) organized as one file per stack at root level. Each guide follows the 15-section template: Project title, Motivation, Build status, Code style, Screenshots, Tech/framework, Features, Code Example, Installation, API Reference, Tests, How to use, Contribute, Credits, License.

## Conventions
- Files named `{stack}-README.md` (e.g. `swift-README.md`, `vue-README.md`)
- All planning output lives in `specs/`
- Test everything. Show evidence before declaring done.

## Never
- Never write code without a plan in specs/
- Never push directly to main/master
- Never refactor or reorganize outside the task scope
- Never skip verification steps

## Agent Rules
- **Workflow Mandate:** You MUST use the bigpowers skills (e.g. `plan-work`, `develop-tdd`, `orchestrate-project`) to perform tasks. DO NOT write code directly in response to a user prompt like "build this feature".
- Read specs/ before writing code.
- All planning and specifications MUST be written to `specs/` (e.g. `specs/PLAN.md`) before any code is generated.
- Write the minimum code that solves the stated problem. Nothing extra.
- Never refactor, rename, or reorganize code outside the task scope.
- Run tests after every change. Show evidence before declaring done.
- One clarifying question beats a wrong assumption baked into 200 lines.
