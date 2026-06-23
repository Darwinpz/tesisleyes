# Flujo de trabajo con Claude Code

## Objetivo

Organizar el trabajo para reducir tokens, evitar fuentes inventadas, mantener coherencia metodológica y producir una tesis en LaTeX bien citada y referenciada.

---

# 1. Flujo general

```text
PDF original
→ conversión a Markdown
→ ficha documental
→ matriz de análisis
→ redacción en LaTeX
→ revisión de citas
→ revisión de coherencia
→ compilación
→ corrección final
```

---

# 2. Responsabilidad del usuario

El usuario debe:

1. Descargar PDFs oficiales, académicos, institucionales o periodísticos relevantes.
2. Convertir PDFs a `.md`.
3. Colocar PDFs en `01_fuentes_pdf_originales/`.
4. Colocar archivos `.md` en `02_fuentes_md/`.
5. Revisar resultados generados por Claude.
6. Confirmar cuando una fuente externa debe incorporarse.
7. Verificar manualmente bibliografía final.
8. Evitar incorporar documentos antiguos o confusos que no aporten al enfoque actual.

---

# 3. Responsabilidad de Claude

Claude debe:

1. Revisar estructura del proyecto.
2. Crear fichas documentales.
3. Crear matrices.
4. Clasificar fuentes.
5. Diferenciar normas, sentencias, doctrina, documentos institucionales, fuentes internacionales, prensa y fuentes legislativas.
6. Buscar fuentes externas solo cuando sea necesario.
7. Redactar capítulos en LaTeX con base en fichas y matrices.
8. Crear tablas.
9. Crear anexos.
10. Auditar citas.
11. Revisar coherencia.
12. Compilar LaTeX.
13. Corregir errores técnicos.
14. Evitar fuentes inventadas.

---

# 4. Estado actual de fuentes

Actualmente el repositorio trabaja principalmente con:

```text
02_fuentes_md/normativa/
02_fuentes_md/jurisprudencia/
02_fuentes_md/internacional/
02_fuentes_md/institucional/
02_fuentes_md/doctrina/
```

Puede incorporarse posteriormente:

```text
02_fuentes_md/prensa/
```

```text
02_fuentes_md/reformas_legislativas/
```

---

# 5. Orden de trabajo

## Fase 1: Inicio

Ejecutar:

```text
/project:iniciar-investigacion
```

Objetivo:

* revisar estructura;
* revisar agentes;
* revisar skills;
* revisar commands;
* verificar archivos base;
* crear reporte inicial.

## Fase 2: Estado

Ejecutar:

```text
/project:estado
```

Objetivo:

* ver qué fuentes existen;
* ver qué fichas existen;
* ver qué matrices existen;
* detectar qué falta;
* confirmar que no existe carpeta local de Asamblea, salvo que el usuario la incorpore después.

## Fase 3: Análisis por lotes

Ejecutar en este orden:

```text
/project:analizar-lote normativa
/project:analizar-lote jurisprudencia
/project:analizar-lote internacional
/project:analizar-lote institucional
/project:analizar-lote doctrina
```

Si se incorpora prensa:

```text
/project:analizar-lote prensa
```

Objetivo:

* crear fichas;
* actualizar matrices;
* identificar utilidad por capítulo;
* advertir vacíos;
* reducir relectura de documentos completos.

---

# 6. Fuentes legislativas y proyectos de ley

La investigación mantiene interés en proyectos de ley o reformas de apertura al sector minero privado.

Sin embargo, al no existir actualmente una carpeta local de Asamblea Nacional, Claude no debe intentar analizar expedientes legislativos locales.

Si se requieren fuentes legislativas, usar:

```text
/project:buscar-fuente proyectos de ley minería privada Ecuador Asamblea Nacional reformas Ley de Minería
```

También pueden buscarse reformas o debates recientes con años específicos:

```text
/project:buscar-fuente proyectos de ley minería privada Ecuador Asamblea Nacional 2024 2025 2026
```

Las fuentes encontradas deben reportarse y no usarse directamente hasta ser incorporadas al repositorio.

---

# 7. Análisis de prensa contextual

La prensa ecuatoriana puede usarse como contexto.

Si se incorporan noticias, deben ubicarse en:

```text
02_fuentes_md/prensa/
```

Ejecutar:

```text
/project:analizar-lote prensa
```

Las noticias sirven para:

* contexto;
* debates públicos;
* minería ilegal;
* conflictividad socioambiental;
* discusión de reformas;
* declaraciones de autoridades.

No sirven como fuente jurídica principal.

---

# 8. Redacción

Orden recomendado:

1. Capítulo I.
2. Capítulo III.
3. Capítulo II.
4. Capítulo IV.
5. Conclusiones.
6. Recomendaciones.
7. Introducción final.
8. Resumen y abstract.

Comandos:

```text
/project:redactar-capitulo capitulo_1_problema
/project:redactar-capitulo capitulo_3_metodologia
/project:redactar-capitulo capitulo_2_marco_referencial
/project:redactar-capitulo capitulo_4_propuesta
/project:redactar-capitulo conclusiones
/project:redactar-capitulo recomendaciones
/project:redactar-capitulo introduccion
```

No redactar sin fichas y matrices suficientes.

---

# 9. Revisión

Ejecutar:

```text
/project:revisar-coherencia
/project:revisar-citas
/project:revisar-tesis
```

Objetivo:

* verificar coherencia metodológica;
* verificar APA 7;
* verificar citas;
* verificar bibliografía;
* verificar relación entre objetivos, capítulos, matrices y propuesta;
* evitar confusión entre minería privada legal y minería ilegal;
* evitar confusión entre proyecto de ley y ley vigente.

---

# 10. Compilación

Ejecutar:

```text
/project:compilar
```

Objetivo:

* compilar LaTeX;
* revisar errores técnicos;
* corregir formato;
* verificar bibliografía.

---

# 11. Regla de ahorro de tokens

Antes de leer documentos completos, Claude debe revisar:

1. matrices;
2. fichas;
3. fuentes `.md`;
4. PDFs originales solo si es necesario.

No releer todos los documentos completos si ya existen fichas y matrices actualizadas.

---

# 12. Regla de control de calidad

Antes de entregar un capítulo, verificar:

* relación con título;
* relación con objetivo general;
* relación con objetivos específicos;
* fuentes verificadas;
* citas correctas;
* no confusión entre proyecto y ley vigente;
* no confusión entre minería privada legal y minería ilegal;
* alcance nacional;
* APA 7;
* LaTeX correcto;
* coherencia con matrices;
* uso prudente de prensa;
* no invención de fuentes.

---

# 13. Regla final

No pedir a Claude: “haz toda la tesis”.

Trabajar por fases y archivos.

No redactar capítulos directamente desde PDFs sin fichas y matrices.

No usar fuentes externas sin incorporarlas al repositorio.

No forzar fuentes legislativas antiguas o confusas si no aportan al enfoque actual.
