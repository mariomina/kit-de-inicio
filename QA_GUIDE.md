# Guía para QA

Esta guía es para quien valida calidad, regresiones y cumplimiento de aceptación.

## Tu objetivo

- Confirmar que el comportamiento real coincide con lo esperado.
- Encontrar fallas con evidencia útil.
- Evitar que un bug se cierre sin validación real.

## Flujo de trabajo

1. Lee la `story`, `epic`, `task` o PR que vas a validar.
2. Ejecuta la prueba manual o automatizada.
3. Compara el resultado real contra el esperado.
4. Si falla algo, registra un `bug` o `regression`.
5. Adjunta evidencia: capturas, logs, video o request ids.
6. Si falta una decisión o dependencia, marca el trabajo como `blocked`.
7. Vuelve a validar el fix antes de cerrar.

## Qué debes cuidar

- Usa `qa test case` cuando quieras formalizar la validación.
- Usa `regression` cuando algo ya funcionaba y dejó de funcionar.
- Responde en el mismo issue o PR para no perder trazabilidad.

## Qué no debes hacer

- No abras bugs vagos sin pasos de reproducción.
- No mezcles varios problemas en un solo issue si no comparten causa.
- No cierres un caso sin evidencia de que quedó resuelto.
