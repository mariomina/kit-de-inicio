# Guía de uso

Esta página es el índice de entrada para usar la plantilla según el rol que tengas en el proyecto.

## Cómo usar esta guía

- Si vas a construir software, ve a `DEVELOPER_GUIDE.md`.
- Si vas a validar calidad, ve a `QA_GUIDE.md`.
- Si vas a decidir alcance o prioridad, ve a `PRODUCT_GUIDE.md`.
- Si vas a aprobar cambios o destrabar trabajo, ve a `TI_MANAGER_GUIDE.md`.
- Si vas a tomar decisiones técnicas de diseño, ve a `ARCHITECT_GUIDE.md`.
- Si vas a preparar una publicación, ve a `RELEASE_GUIDE.md`.
- Si vas a revisar riesgos o excepciones de seguridad, ve a `SECURITY_REVIEW_GUIDE.md`.

## Antes de empezar

1. Crea el repositorio nuevo desde esta plantilla.
2. Cambia el nombre, la descripción y la visibilidad del repositorio.
3. Revisa los labels y ajusta los que no apliquen a tu contexto.
4. Activa la protección de `main` en GitHub.
5. Verifica que `CODEOWNERS` siga apuntando a los responsables correctos.

## Qué debe configurar cada proyecto

- `README.md` con el contexto del producto
- `LABELS.md` con los labels que sí vas a usar
- `BRANCHING.md` con la política de ramas
- `WORKFLOW.md` con el flujo de trabajo
- `QA.md` con el flujo de validación
- `SECURITY.md` con el canal de reporte de seguridad
- `CODEOWNERS` con los responsables reales
- `BRANCH_PROTECTION.md` con la política recomendada para `main`

## Regla práctica

- Si un proyecto no necesita una guía, elimínala.
- Si sí la necesita, ajústala al contexto del proyecto antes de empezar a trabajar.
