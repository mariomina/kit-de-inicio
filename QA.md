# QA

Este starter kit incluye un flujo de QA para equipos serios.

## Tipos de registro

- `bug` - algo falla
- `regression` - algo que funcionaba dejó de funcionar
- `qa test case` - caso de prueba formal
- `task` - trabajo interno de QA o soporte técnico

## Flujo de QA

1. Recibe contexto desde `epic`, `story`, `task` o PR.
2. Ejecuta validación manual o automatizada.
3. Compara el resultado real contra el esperado.
4. Si encuentra una falla, crea o actualiza un `bug` o `regression`.
5. Si hace falta evidencia, adjunta capturas, video, logs o request ids.
6. Si el trabajo depende de otra persona, marca el issue como `blocked` y explica por qué.
7. Responde en el mismo issue o PR para mantener la trazabilidad.
8. Verifica el fix y cierra el ciclo cuando el comportamiento ya esté correcto.

## Reglas de calidad

- Todo hallazgo importante debe quedar escrito.
- El chat sirve para coordinar; el issue sirve como fuente de verdad.
- No mezcles un bug nuevo con varios problemas distintos si no comparten la misma causa.
- Si el fallo afecta producción, seguridad o dinero, escala de inmediato con el dueño correcto.

## Escalamiento

- Usa `blocked` cuando falte una decisión.
- Usa `needs-triage` cuando falte contexto.
- Usa `needs-review` cuando ya exista fix pero falte validación.
- Menciona al responsable correcto solo cuando haga falta acción real.
