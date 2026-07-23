# Protección de Rama

Esta plantilla asume una política de protección fuerte para `main`.

## Configuración recomendada en GitHub

- Proteger `main`
- Requerir pull request antes de hacer merge
- Requerir al menos 1 aprobación
- Requerir revisión de `CODEOWNERS`
- Rechazar pushes directos
- Rechazar force pushes
- Rechazar borrado de la rama
- Descartar aprobaciones obsoletas si cambia el PR de forma sensible
- Requerir que la rama esté actualizada antes de merge si el equipo lo necesita

## Política operativa

- Nadie hace push directo a `main`
- Todo cambio entra por PR
- Todo PR relevante debe tener issue o story vinculada
- Los archivos de gobernanza requieren revisión del dueño del repositorio
- El equipo debe tratar `main` como rama siempre liberable

## Qué resuelve

- Evita cambios no revisados
- Fuerza trazabilidad
- Da un punto de control para calidad y seguridad
- Hace visible quién debe revisar cada cambio
