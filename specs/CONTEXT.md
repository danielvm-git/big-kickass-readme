# Context — big-kickass-readme

## Domain

Stack-specific README writing guides based on the 15-section Kickass README template by Akash.

## Project State

| Area | Status |
|------|--------|
| Bootstrap | ✅ CONVENTIONS.md, CLAUDE.md, AGENTS.md, GEMINI.md created |
| Git | ✅ Initialized on `main` |
| specs/ | ✅ Created |
| Prior Art | ✅ Researched (see below) |
| SCOPE.md | ❌ Not yet defined |
| RELEASE-PLAN.md | ❌ Not yet created |
| Content files | ❌ Not yet written |

## Prior Art

### Source Template

| Candidate | Verdict | Notes |
|-----------|---------|-------|
| [Akash's Kickass README gist](https://gist.github.com/akashnimare/7b065c12d9750578de8e705fb4771d2f) | **adopt** | The 15-section template is the foundation. We use this as the base structure. |
| [Akash's Medium article](https://meakaakka.medium.com/a-beginners-guide-to-writing-a-kickass-readme-7ac01da88ab3) | **adopt** | Context and motivation for the template. |

### README Templates (General)

| Candidate | Verdict | Notes |
|-----------|---------|-------|
| [othneildrew/Best-README-Template](https://github.com/othneildrew/Best-README-Template) (16k stars) | **compose** | Different structure (fewer sections). Borrow badge styling and image layout patterns. |
| [dbader/readme-template](https://github.com/dbader/readme-template) | **compose** | Simpler template. Notable for its clean format. |
| [GitHub README Template Guide 2026](https://gingiris.tools/blog/2026/04/02/github-readme-template-guide/) | **compose** | Modern best practices (hero image, quick-start, demo GIF, FAQ). Good section additions. |
| [README Template Generator](https://devpane.tools/markdown/readme-template) | **compose** | Badge patterns and installation section structure. |

### Stack-Specific READMEs

| Candidate | Verdict | Notes |
|-----------|---------|-------|
| Swift | **build** | 3 repos in portfolio. Cover CocoaPods, SPM, Xcode specifics. |
| TypeScript | **build** | 8 repos in portfolio. Cover Node/services, npm, TS config. |
| Vue | **build** | 2 repos in portfolio. Cover Vite, SFC, Vue Router/Pinia. |
| SvelteKit | **build** | 0 repos in portfolio but requested. Cover SvelteKit project structure, adapters. |
| Astro | **build** | 2 repos in portfolio. Cover Astro islands, content collections, adapters. |
| Go | **compose** | 1 repo in portfolio. Reference golang-standards/project-layout. |
| Python | **build** | 2 repos in portfolio. Cover pip, venv, project structure. |
| Shell | **build** | 3 repos in portfolio. Cover script structure, argument parsing. |

**Overall verdict: build** — No existing resource provides per-stack README guides based on the 15-section Kickass template.
