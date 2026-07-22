# Versioning

This starter kit uses semantic versioning for releases:

- `v0.1.0` for the first usable release
- `v0.1.1`, `v0.1.2` for small fixes
- `v0.2.0` for backward-compatible additions
- `v1.0.0` when the kit is stable enough for repeated use

Recommended release flow:

1. Merge changes into `main`.
2. Update `CHANGELOG.md`.
3. Create a git tag like `v0.1.0`.
4. Optionally publish a GitHub Release.

## Release rules

- Every shipped change should have a tag.
- Use release branches only when coordination or stabilization needs it.
- Keep prerelease tags explicit when you need them, for example `v1.2.0-rc.1`.
- Do not cut a release from an unreviewed branch.

## Changelog rule

- User-visible changes go into `CHANGELOG.md`.
- Internal-only cleanup can stay unlogged if it does not affect users.
- Release notes should summarize impact, not just list file names.
