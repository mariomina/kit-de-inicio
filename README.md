# Kit de Inicio

Plantilla base para arrancar proyectos con disciplina de equipo desde el día 1.

## Qué incluye

- `README.md`
- `CONTRIBUTING.md`
- `BRANCHING.md`
- `WORKFLOW.md`
- `QA.md`
- `VERSIONING.md`
- `LABELS.md`
- `SECURITY.md`
- `CHANGELOG.md`
- `LICENSE`
- `.gitignore`
- `.editorconfig`
- `.github/pull_request_template.md`
- `.github/ISSUE_TEMPLATE/*`

## Cómo usarlo

1. Crea un proyecto nuevo desde esta plantilla.
2. Ajusta nombre, dominio, labels y reglas de release.
3. Abre el trabajo como `epic`, `story` o `task`, no como texto suelto.
4. Trabaja en ramas cortas y abre PRs con contexto, validación y riesgo.
5. Versiona con `main`, tags semánticos y `CHANGELOG.md`.

## Convenciones base

- Ramas: `main`, `feature/*`, `fix/*`, `chore/*`, `refactor/*`, `release/*`
- Seguimiento: labels de GitHub + formularios de issue + template de pull request
- Releases: versionado semántico con tags como `v0.1.0`
- Control de calidad: issue vinculado, validación, revisión, changelog y nota de release cuando aplique
- QA: bug, regresión y casos de prueba formales
- Aprobaciones: solicitudes formales para decisiones de TI, gerencia o seguridad
- Decisiones especializadas: seguridad, arquitectura y release
