# Labels

This starter kit uses a small, reusable label set that works across most serious projects.

## Core workflow

- `epic` - large body of work that spans multiple stories
- `story` - user-facing slice of work
- `task` - internal implementation task
- `bug` - something is broken
- `enhancement` - net-new capability or improvement
- `refactor` - internal change without expected behavior change
- `docs` - documentation only
- `test` - test coverage or test harness work
- `ci` - continuous integration and automation changes

## Triage

- `blocked` - work cannot proceed yet
- `needs-triage` - more context is required before the work is scoped
- `priority: high` - urgent or strategically important
- `priority: medium` - normal priority
- `priority: low` - can wait without risk
- `needs-review` - ready for review
- `ready` - ready to start
- `blocked` - work cannot proceed yet

## Special cases

- `security` - security-sensitive change or vulnerability
- `research` - needs investigation before implementation
- `design` - UX or visual exploration

## Release policy

- `v0.1.0` is the first usable release tag
- every user-visible release should update `CHANGELOG.md`
- tags should follow Semantic Versioning
- keep release work labeled `release`
