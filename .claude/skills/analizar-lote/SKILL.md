---
name: analizar-lote
description: Analiza un lote de fuentes .md, crea fichas y actualiza matrices.
---

Analiza el lote indicado por el usuario.

Ejemplos:

- normativa
- jurisprudencia
- doctrina
- institucional
- internacional
- reformas_legislativas

Proceso:

1. Lee `CLAUDE.md`.
2. Revisa los documentos del lote en `02_fuentes_md/`.
3. Usa el subagente adecuado:
   - normativa: normativa-analyst;
   - asamblea: legislative-analyst;
   - jurisprudencia: jurisprudence-analyst;
   - doctrina: doctrine-analyst;
   - institucional o internacional: source-ingestor.
4. Crea fichas en `03_fichas/`.
5. Actualiza la matriz correspondiente en `04_matrices/`.
6. No redactes capítulos todavía.
7. No inventes información.
8. Si un dato no aparece, escribe: “Dato no identificado en el documento”.