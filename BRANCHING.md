# Branching

Use a simple branch model that scales without creating process noise.

## Branch types

- `main` - always releasable
- `feature/*` - new user-facing capability
- `fix/*` - bug fix
- `chore/*` - maintenance work
- `refactor/*` - internal change with no intended behavior change
- `release/*` - stabilization or release prep when coordination needs it

## Rules

- Branch from `main`.
- Keep branches short-lived.
- One branch should map to one intent.
- Merge back through pull requests only.
- Delete branches after merge unless there is a concrete reason to keep them.

## Naming

- Use lowercase names with hyphens.
- Prefer `feature/add-login-flow` over vague names like `my-branch`.
- Include the work item when it helps traceability.
