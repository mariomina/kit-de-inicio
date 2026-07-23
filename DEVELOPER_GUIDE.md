# Guía para desarrollo

Esta guía es para la persona que va a construir el software.

## Tu objetivo

- Entregar cambios pequeños, claros y verificables.
- Mantener la trazabilidad entre issue, rama, PR y release.
- No romper la rama principal ni saltarte el proceso.

## Flujo de trabajo

1. Toma una `story`, `task` o `bug` que ya esté triageada.
2. Crea una rama corta desde `main`.
3. Implementa el cambio más pequeño posible.
4. Verifica localmente antes de abrir el PR.
5. Abre el PR usando la plantilla.
6. Responde comentarios y ajusta lo que haga falta.
7. Haz merge solo cuando esté aprobado y validado.

## Qué debes cuidar

- Vincula siempre el issue o story.
- Mantén commits pequeños y descriptivos.
- Agrega pruebas cuando el cambio tenga riesgo.
- Documenta decisiones de implementación si afectan a otros roles.

## Qué no debes hacer

- No hagas push directo a `main`.
- No mezcles varios objetivos grandes en una sola rama.
- No cierres un issue sin dejar evidencia de la solución.
