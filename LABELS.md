# Etiquetas

Este starter kit usa un conjunto pequeño y reutilizable de labels que funciona bien en la mayoría de proyectos serios.

## Flujo principal

- `epic` - bloque grande de trabajo que abarca varias stories
- `story` - parte del trabajo visible para el usuario
- `task` - tarea interna de implementación
- `bug` - algo está roto
- `enhancement` - capacidad nueva o mejora
- `refactor` - cambio interno sin cambio esperado de comportamiento
- `docs` - solo documentación
- `test` - cobertura de pruebas o trabajo de harness
- `ci` - cambios de integración continua y automatización

## Triage

- `blocked` - el trabajo no puede avanzar todavía
- `needs-triage` - hace falta más contexto antes de definir el alcance
- `priority: high` - urgente o estratégicamente importante
- `priority: medium` - prioridad normal
- `priority: low` - puede esperar sin riesgo
- `needs-review` - listo para revisión
- `ready` - listo para empezar

## Casos especiales

- `security` - cambio sensible de seguridad o vulnerabilidad
- `research` - requiere investigación antes de implementar
- `design` - exploración UX o visual

## Política de releases

- `v0.1.0` es el primer tag usable
- cada release visible para usuarios debe actualizar `CHANGELOG.md`
- los tags deben seguir versionado semántico
- el trabajo de release debe ir etiquetado como `release`
