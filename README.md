# AdV Skills

Repositorio de skills propias de AdV para ChatGPT.

## Alcance

Este repositorio contiene únicamente skills reutilizables de AdV y sus recursos asociados. No contiene datos de clientes, expedientes, documentos cerrados ni material de TRC.

## Estructura

- `skills/`: una carpeta por skill.
- `docs/`: criterios de gobierno del repositorio.
- Cada skill debe incluir obligatoriamente `SKILL.md` y `agents/openai.yaml`.
- Los recursos opcionales de una skill viven dentro de su propia carpeta: `references/`, `scripts/` y `assets/`.

## Regla de diseño

Una skill debe corresponder a un flujo acotado y repetible. Las reglas generales de AdV OS no se duplican aquí; se mantienen en sus fuentes normativas. El estado de proyectos o casos tampoco vive en una skill.

## Separación

- AdV: este repositorio.
- Delta Phi: `DeltaPhi-Skills`.
- TRC: fuera de este entorno.
- Código y aplicaciones: repositorios de desarrollo específicos, no este repositorio.

## Flujo

1. Definir entrada, salida, reglas, excepciones, fuentes y criterio de calidad.
2. Crear la skill.
3. Validarla y probarla.
4. Versionar los cambios en GitHub.
5. Publicarla o instalarla en ChatGPT cuando corresponda.
