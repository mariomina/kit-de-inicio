# Kit de Inicio

Plantilla base para arrancar proyectos con disciplina de equipo desde el día 1.

## Problema que resuelve

Esta plantilla evita empezar proyectos “a mano” sin estructura. Te da desde el inicio una base clara para identidad del repositorio, documentación por rol, documentación de proceso, control de cambios, revisión de seguridad y una forma consistente de escalar el proyecto como si ya fuera serio.

## Qué incluye

- `README.md`
- `CONTRIBUTING.md`
- `SECURITY.md`
- `CHANGELOG.md`
- `LICENSE`
- `.gitignore`
- `.editorconfig`
- `.github/pull_request_template.md`
- `.github/ISSUE_TEMPLATE/*`
- `[guides/](./guides/)`
- `[docs/](./docs/)`

## Cómo usarlo

1. Crea un proyecto nuevo desde esta plantilla.
2. Revisa [guides/README.md](./guides/README.md) si quieres empezar por rol o [docs/README.md](./docs/README.md) si quieres empezar por reglas.
3. Ajusta nombre, dominio, labels y configuración del repositorio.
4. Activa la protección de `main` y revisa [CODEOWNERS](./.github/CODEOWNERS).
5. Versiona con `main`, tags semánticos y `CHANGELOG.md`.

## Estructura

- [`guides/`](./guides/): guías por rol para usar la plantilla
- [`docs/`](./docs/): documentación operativa y de proceso
- `.github/`: plantillas, approvals y CODEOWNERS
- raíz: solo los archivos que GitHub y cualquier usuario esperan ver primero
