# Guía de uso

Esta guía explica cómo usar esta plantilla para iniciar un proyecto nuevo con un flujo profesional.

## Para quién es

- Personas que van a crear un proyecto nuevo desde esta plantilla.
- Equipos que quieren trazabilidad, QA, control de cambios y revisiones formales.
- Usuarios que quieren una base simple pero seria para trabajo empresarial.

## Antes de empezar

1. Crea el repositorio nuevo desde esta plantilla.
2. Cambia el nombre, la descripción y la visibilidad del repositorio.
3. Revisa los labels y ajusta los que no apliquen a tu contexto.
4. Activa la protección de `main` en GitHub.
5. Verifica que `CODEOWNERS` siga apuntando a los responsables correctos.

## Primer día de uso

1. Escribe el contexto del proyecto en `README.md`.
2. Define las reglas de trabajo en `BRANCHING.md` y `WORKFLOW.md`.
3. Confirma cómo se van a registrar bugs, regresiones y casos de QA.
4. Si el proyecto necesita aprobaciones, usa los formularios ya incluidos.
5. Si vas a publicar, define la primera versión en `VERSIONING.md` y `CHANGELOG.md`.

## Flujo normal

1. Crea un `epic`, `story` o `task` según el tamaño del trabajo.
2. Trabaja en una rama corta desde `main`.
3. Abre un PR usando la plantilla.
4. Adjunta evidencia si hay QA, bug, regresión o aprobación requerida.
5. Espera revisión, correcciones y aprobación.
6. Haz merge a `main` cuando todo esté verde.
7. Corta el release cuando corresponda.

## Qué debe configurar cada proyecto

- `README.md` con el contexto del producto
- `LABELS.md` con los labels que sí vas a usar
- `BRANCHING.md` con la política de ramas
- `QA.md` con el flujo de validación
- `SECURITY.md` con el canal de reporte de seguridad
- `CODEOWNERS` con los responsables reales
- `BRANCH_PROTECTION.md` con la política recomendada para `main`

## Qué no debes cambiar sin razón

- La idea de usar PR como punto de control
- La regla de dejar trazabilidad en issues
- La práctica de usar branches cortas
- La disciplina de versionar con tags y changelog

## Regla práctica

- Si un proyecto no necesita un formulario o label, elimínalo.
- Si sí lo necesita, ajústalo al contexto del proyecto antes de empezar a trabajar.
