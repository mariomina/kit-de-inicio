# Workflow

Usa este flujo para proyectos serios:

1. Abre un `epic` cuando el trabajo abarque varios entregables.
2. Divide el epic en issues de `story` para las partes visibles para el usuario.
3. Separa los detalles de implementación en issues de `task` cuando haga falta.
4. Usa los labels `bug`, `refactor`, `docs`, `test`, `ci`, `security`, `research` y `design` para clasificar el trabajo.
5. Abre un PR por rama y mantenlo ligado a un único issue o story.
6. Verifica localmente antes de pedir revisión.
7. Haz merge a `main`.
8. Etiqueta el release y actualiza `CHANGELOG.md`.

## Trazabilidad

- El epic explica por qué existe el trabajo.
- La story explica qué recibe el usuario.
- La task explica qué se debe construir.
- El PR explica qué cambió y cómo se validó.

## Regla práctica

- Si un cambio es demasiado grande para describirse en un solo PR, también es demasiado grande para una sola rama.

## QA

- QA valida el comportamiento contra la story, el epic o el criterio de aceptación.
- Si encuentra una regresión, registra un issue de `regression` y enlaza la versión anterior y la actual.
- Si necesita formalizar la validación, crea un `qa test case`.
- El estado `blocked` se usa cuando falta una decisión, acceso, dependencia o respuesta de otra persona.
- La discusión rápida puede pasar por chat, pero la trazabilidad oficial vive en el issue o PR.

## Aprobaciones

- Usa `approval request` cuando el trabajo necesite decisión de TI, gerencia, arquitectura o seguridad.
- Marca el trabajo como `blocked` mientras esperas la decisión.
- Incluye contexto, impacto, opciones consideradas y recomendación.
- Nombra un solo aprobador principal por solicitud.
- La respuesta debe quedar escrita en el mismo issue para mantener trazabilidad.

## Decisiones especializadas

- Usa `security review request` para hallazgos, excepciones o cambios con riesgo de seguridad.
- Usa `architecture decision request` cuando el sistema necesite una decisión de diseño, componente o patrón.
- Usa `release approval request` cuando el equipo ya esté listo para publicar y falte autorización.
- Mantén un solo issue por decisión para que el historial quede limpio.
