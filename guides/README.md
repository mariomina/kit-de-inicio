# Guías de uso

Este índice agrupa las guías por rol para usar la plantilla según la responsabilidad de cada persona.

## Cómo usar esta guía

- Si vas a construir software, ve a [DEVELOPER_GUIDE.md](./DEVELOPER_GUIDE.md).
- Si vas a validar calidad, ve a [QA_GUIDE.md](./QA_GUIDE.md).
- Si vas a decidir alcance o prioridad, ve a [PRODUCT_GUIDE.md](./PRODUCT_GUIDE.md).
- Si vas a aprobar cambios o destrabar trabajo, ve a [TI_MANAGER_GUIDE.md](./TI_MANAGER_GUIDE.md).
- Si vas a tomar decisiones técnicas de diseño, ve a [ARCHITECT_GUIDE.md](./ARCHITECT_GUIDE.md).
- Si vas a preparar una publicación, ve a [RELEASE_GUIDE.md](./RELEASE_GUIDE.md).
- Si vas a revisar riesgos o excepciones de seguridad, ve a [SECURITY_REVIEW_GUIDE.md](./SECURITY_REVIEW_GUIDE.md).

## Antes de empezar

1. Crea el repositorio nuevo desde esta plantilla.
2. Cambia el nombre, la descripción y la visibilidad del repositorio.
3. Revisa los labels y ajusta los que no apliquen a tu contexto.
4. Activa la protección de `main` en GitHub.
5. Verifica que `CODEOWNERS` siga apuntando a los responsables correctos.

## Qué debe configurar cada proyecto

- [`README.md`](../README.md) con el contexto del producto
- [`docs/README.md`](../docs/README.md) para entrar a la documentación operativa
- [`docs/process/LABELS.md`](../docs/process/LABELS.md) con los labels que sí vas a usar
- [`docs/process/BRANCHING.md`](../docs/process/BRANCHING.md) con la política de ramas
- [`docs/process/WORKFLOW.md`](../docs/process/WORKFLOW.md) con el flujo de trabajo
- [`docs/process/QA.md`](../docs/process/QA.md) con el flujo de validación
- [`SECURITY.md`](../SECURITY.md) con el canal de reporte de seguridad
- [`.github/CODEOWNERS`](../.github/CODEOWNERS) con los responsables reales
- [`docs/process/BRANCH_PROTECTION.md`](../docs/process/BRANCH_PROTECTION.md) con la política recomendada para `main`

## Regla práctica

- Si un proyecto no necesita una guía, elimínala.
- Si sí la necesita, ajústala al contexto del proyecto antes de empezar a trabajar.
