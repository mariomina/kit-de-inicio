# Versionado

Este starter kit usa versionado semántico para los releases:

- `v0.1.0` para el primer release usable
- `v0.1.1`, `v0.1.2` para correcciones pequeñas
- `v0.2.0` para mejoras compatibles hacia atrás
- `v1.0.0` cuando el kit ya sea estable para uso repetido

Flujo recomendado de release:

1. Haz merge de los cambios a `main`.
2. Actualiza `CHANGELOG.md`.
3. Crea un tag de git como `v0.1.0`.
4. Opcionalmente publica un GitHub Release.

## Reglas de release

- Todo cambio publicado debe tener un tag.
- Usa ramas de release solo cuando haga falta coordinación o estabilización.
- Mantén explícitos los tags de prerelease cuando los necesites, por ejemplo `v1.2.0-rc.1`.
- No cortes un release desde una rama no revisada.

## Regla del changelog

- Los cambios visibles para usuarios van en `CHANGELOG.md`.
- La limpieza interna puede quedarse fuera si no afecta a usuarios.
- Las notas de release deben resumir impacto, no solo listar nombres de archivos.
