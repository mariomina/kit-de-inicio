# Workflow

Use this flow for serious projects:

1. Open an `epic` when the work spans multiple deliverables.
2. Break the epic into `story` issues for user-facing slices.
3. Split implementation details into `task` issues when needed.
4. Use `bug`, `refactor`, `docs`, `test`, `ci`, `security`, `research`, and `design` labels to classify the work.
5. Open one PR per branch and keep it tied to a single issue or story.
6. Verify locally before asking for review.
7. Merge to `main`.
8. Tag the release and update `CHANGELOG.md`.

## Traceability

- Epic explains why the work exists.
- Story explains what the user gets.
- Task explains what must be built.
- PR explains what changed and how it was validated.

## Practical rule

- If a change is too large to describe in one PR, it is too large for one branch.
