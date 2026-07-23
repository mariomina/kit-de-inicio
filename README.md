# Kit de Inicio

Plantilla base para arrancar proyectos con disciplina de equipo desde el día 1.

## Problema que resuelve

Esta plantilla evita empezar proyectos “a mano” sin estructura. Te da desde el inicio una base clara para identidad del repositorio, documentación por rol, documentación de proceso, control de cambios, revisión de seguridad y una forma consistente de escalar el proyecto como si ya fuera serio.

## Para quién es

Esta plantilla es para personas y equipos que quieren arrancar un proyecto con criterio profesional desde el primer día:

- Desarrollo individual con intención de crecer a equipo.
- Equipos pequeños que quieren orden sin burocracia innecesaria.
- Proyectos personales que quieren operar como producto serio.
- Equipos técnicos, QA, producto o liderazgo que necesitan un punto de partida común.

## Cuándo no usarla

No la uses si buscas algo improvisado o desechable. Tampoco si:

- No quieres mantener documentación mínima.
- No vas a usar ramas, PRs, issues o tags.
- Prefieres una estructura vacía sin reglas ni convenciones.
- Tu proyecto ya tiene un estándar corporativo distinto y no quieres adaptarlo.

## Qué entrega desde el día 1

La plantilla deja listo un arranque base con:

- Identidad y contexto del proyecto en la raíz.
- Guías por rol para usar la plantilla según la perspectiva de cada persona.
- Documentación de proceso para ramas, QA, labels, versionado y protección.
- Plantillas de GitHub para PRs e issues.
- Archivos de seguridad, contribución y control de cambios.

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
