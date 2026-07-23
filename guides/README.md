# Guías de uso

Este índice agrupa las guías por rol para usar la plantilla según la responsabilidad de cada persona.

## Cómo usar esta guía

- Si vas a construir software, ve a [developer.md](./developer.md).
- Si vas a validar calidad, ve a [qa.md](./qa.md).
- Si vas a decidir alcance o prioridad, ve a [product.md](./product.md).
- Si vas a aprobar cambios o destrabar trabajo, ve a [ti-manager.md](./ti-manager.md).
- Si vas a tomar decisiones técnicas de diseño, ve a [architect.md](./architect.md).
- Si vas a preparar una publicación, ve a [release.md](./release.md).
- Si vas a revisar riesgos o excepciones de seguridad, ve a [security-review.md](./security-review.md).

## Antes de empezar

1. Crea el repositorio nuevo desde esta plantilla.
2. Cambia el nombre, la descripción y la visibilidad del repositorio.
3. Revisa los labels y ajusta los que no apliquen a tu contexto.
4. Activa la protección de `main` en GitHub.
5. Verifica que `CODEOWNERS` siga apuntando a los responsables correctos.

## Qué debe configurar cada proyecto

- [`README.md`](../README.md) con el contexto del producto
- [`docs/README.md`](../docs/README.md) para entrar a la documentación operativa
- [`docs/process/labels.md`](../docs/process/labels.md) con los labels que sí vas a usar
- [`docs/process/branching.md`](../docs/process/branching.md) con la política de ramas
- [`docs/process/workflow.md`](../docs/process/workflow.md) con el flujo de trabajo
- [`docs/process/qa.md`](../docs/process/qa.md) con el flujo de validación
- [`SECURITY.md`](../SECURITY.md) con el canal de reporte de seguridad
- [`.github/CODEOWNERS`](../.github/CODEOWNERS) con los responsables reales
- [`docs/process/branch_protection.md`](../docs/process/branch_protection.md) con la política recomendada para `main`

## Regla práctica

- Si un proyecto no necesita una guía, elimínala.
- Si sí la necesita, ajústala al contexto del proyecto antes de empezar a trabajar.
