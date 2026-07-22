# Ramas

Usa un modelo de ramas simple que escale sin meter ruido de proceso.

## Tipos de rama

- `main` - siempre lista para release
- `feature/*` - nueva capacidad visible para el usuario
- `fix/*` - corrección de bug
- `chore/*` - trabajo de mantenimiento
- `refactor/*` - cambio interno sin cambio de comportamiento intencional
- `release/*` - estabilización o preparación de release cuando haga falta coordinación

## Reglas

- Crea las ramas desde `main`.
- Mantén las ramas de vida corta.
- Una rama debe corresponder a una sola intención.
- Haz merge solo mediante pull request.
- Elimina las ramas después del merge salvo que haya una razón concreta para conservarlas.

## Nomenclatura

- Usa nombres en minúsculas con guiones.
- Prefiere `feature/agregar-flujo-login` antes que nombres vagos como `mi-rama`.
- Incluye el ítem de trabajo cuando ayude a la trazabilidad.
