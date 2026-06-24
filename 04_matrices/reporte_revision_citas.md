# Reporte de revisión de citas y bibliografía
## Tesis: "Análisis de derecho ambiental ecuatoriano: Revisión crítica de proyectos de ley de apertura al sector minero privado."

**Fecha de revisión:** 24 de junio de 2026
**Revisión número:** Segunda (la primera fue tras crear los 25 BibTeX; esta cubre Cap. III completo con `\parencite{}` y `\textcite{}` directos)
**Agente:** citation-auditor
**Archivos revisados:** `05_capitulos/capitulo_1_problema.tex`, `05_capitulos/capitulo_3_metodologia.tex`, `06_tablas/tabla_cdiu.tex`, `06_tablas/tabla_analisis_documental.tex`, `referencias.bib`, `04_matrices/reporte_revision_citas.md` (anterior), matrices y fichas seleccionadas de `03_fichas/` y `04_matrices/`

---

## 1. Resumen general

| Indicador | Resultado |
|---|---|
| Entradas en `referencias.bib` | 25 |
| Claves usadas con `\parencite{}` o `\textcite{}` en Cap. III | 22 claves distintas |
| Claves usadas con `\nocite{}` en Cap. I | 21 (originales) + 2 correcciones = 23 |
| Claves en `.bib` sin citación activa al iniciar la revisión | 2 (`coip_2014`, `reglamento_general_ley_mineria_2009`) |
| Claves corregidas con `\nocite{}` en esta revisión | 2 → ✅ corregidas |
| Claves citadas en Cap. III sin entrada en `.bib` | 0 |
| Fuentes inventadas detectadas | 0 |
| Problemas de formato APA 7 | 4 (P-APA-01 a P-APA-04) |
| Problemas de fuentes jurídicas | 2 (P-JUR-01, P-JUR-02) |
| Problemas de tablas | 1 menor (P-TAB-01) |
| Estado general del Cap. I | Listo para Fase 5 (conversión a `\parencite{}` pendiente) |
| Estado general del Cap. III | ✅ Listo. Patrón de citación correcto. Sin claves rotas. |
| Estado general de `referencias.bib` | ✅ Completo — todas las 25 entradas tienen citación activa |

---

## 2. Citas correctas

### 2.1 Claves de Cap. III verificadas contra `referencias.bib`

Todas las claves usadas con `\parencite{}` en Cap. III tienen entrada exacta en `referencias.bib`. No se detectó ninguna clave rota.

| Clave BibTeX | Usada en Cap. III | Tipo | Verificación local |
|---|---|---|---|
| `grefa_valencia_2021` | Sí | `@thesis` | `fichas_doctrina/`; `matriz_doctrina.md` N.1 |
| `villacis_calvas_2022` | Sí | `@thesis` | `fichas_doctrina/`; `matriz_doctrina.md` N.6 |
| `lozano_espinosa_2023` | Sí | `@article` | `fichas_doctrina/`; `matriz_doctrina.md` N.8 |
| `cce_1149_19_jp_21` | Sí | `@misc` | `fichas_jurisprudenciales/`; `matriz_jurisprudencial.md` N.1 |
| `cce_32_17_in_21` | Sí | `@misc` | `fichas_jurisprudenciales/`; `matriz_jurisprudencial.md` N.4 |
| `cce_22_18_in_21` | Sí | `@misc` | `fichas_jurisprudenciales/`; `matriz_jurisprudencial.md` N.5 |
| `ley_fortalecimiento_2026` | Sí | `@misc` | `fichas_normativas/`; `matriz_normativa.md` N.10 |
| `coa_2017` | Sí | `@misc` | `fichas_normativas/`; `matriz_normativa.md` N.2 |
| `cre_2008` | Sí | `@misc` | `fichas_normativas/`; `matriz_normativa.md` N.1 |
| `reglamento_coa_2019` | Sí | `@misc` | `fichas_normativas/`; `matriz_normativa.md` N.3 |
| `ley_mineria_2009` | Sí | `@misc` | `fichas_normativas/`; `matriz_normativa.md` N.5 |
| `ley_mineria_2025` | Sí | `@misc` | `fichas_normativas/`; `matriz_normativa.md` N.8 |
| `ley_reformatoria_mineria_2013` | Sí | `@misc` | `fichas_normativas/`; `matriz_normativa.md` N.9 |
| `acuerdo_escazu_2018` | Sí | `@misc` | `fichas_internacionales/`; `matriz_internacional.md` N.1 |
| `cedec_guia_2023` | Sí | `@misc` | `fichas_jurisprudenciales/`; `matriz_jurisprudencial.md` N.3 |
| `ochoa_jimenez_2024` | Sí | `@article` | `fichas_doctrina/`; `matriz_doctrina.md` N.9 |
| `peck_et_al_2024` | Sí | `@article` | `fichas_doctrina/`; `matriz_doctrina.md` N.10 |
| `sanchez_romero_et_al_2026` | Sí | `@article` | `fichas_doctrina/`; `matriz_doctrina.md` N.11 |
| `medina_garcia_2026` | Sí | `@article` | `fichas_doctrina/`; `matriz_doctrina.md` N.12 |
| `arcom_rendicion_cuentas_2024` | Sí | `@misc` | `fichas_institucionales/`; `matriz_institucional.md` N.5 |
| `primicias_demandas_2026` | Sí | `@misc` | `fichas_prensa/`; `matriz_prensa_contextual.md` N.15 |
| `cepal_ruta_escazu_2023` | Solo `\nocite{}` en Cap. I | `@misc` | `fichas_internacionales/`; `matriz_internacional.md` N.2 |

### 2.2 Mecanismo `\nocite{}` en Cap. I

El bloque `\nocite{}` al final de `capitulo_1_problema.tex` es un mecanismo transitorio aprobado. Tras las correcciones NC-01 y NC-02 de esta revisión, el bloque contiene 23 claves, todas verificadas en `referencias.bib`. No existe ninguna clave rota.

### 2.3 Ley vigente impugnada — diferenciación correcta

La Ley de Fortalecimiento 2026 es identificada en ambos capítulos como norma vigente con Registro Oficial (R.O. Quinto Suplemento No. 234, 2-mar-2026) con advertencia simultánea de demandas de inconstitucionalidad en curso. Esta diferenciación es correcta conforme a CLAUDE.md, reglas 2 y 3. La ley no es tratada como proyecto de ley ni como norma ya declarada inconstitucional.

---

## 3. Citas con observaciones menores

### OBS-01 — `cepal_ruta_escazu_2023` en `\nocite{}` pero no en `\parencite{}`

Presente en `\nocite{}` de Cap. I (garantiza inclusión en bibliografía). No citada con `\parencite{}` en Cap. III, lo cual es apropiado dado que el capítulo es metodológico. Citar con `\parencite{}` al desarrollar el Cap. II o análisis de Escazú en Cap. IV.

Prioridad: baja — acción al redactar Cap. II o IV.

### OBS-02 — `cce_comunicado_agosto2025` solo en `\nocite{}`

Aparece en `\nocite{}` de Cap. I y en texto plano como nota al pie. No citado con `\parencite{}` en Cap. III. La `matriz_jurisprudencial.md` confirma utilidad "baja-media, solo procesal." La ausencia de `\parencite{}` es apropiada. La inclusión en `\nocite{}` garantiza su aparición en la bibliografía.

Prioridad: ninguna.

---

## 4. Referencias faltantes — claves en texto sin entrada en `.bib`

**Resultado: ninguna.** Todas las claves usadas en `\parencite{}`, `\textcite{}` o `\nocite{}` tienen entrada exacta en `referencias.bib`. No existe ninguna clave rota que pueda generar error de compilación de Biber.

---

## 5. Entradas BibTeX sin citación activa — resueltas en esta revisión

### NC-01 — `coip_2014` ✅ Corregida

| Campo | Detalle |
|---|---|
| Entrada | Código Orgánico Integral Penal, 2014 (R.O. Suplemento 180, 10-feb-2014) |
| Causa de la ausencia | Arts. 260-261 COIP mencionados en tabla CDIU y Cap. III en texto descriptivo, sin clave BibTeX |
| Verificación local | Ficha: `fichas_normativas/coip_ficha.md`; `matriz_normativa.md` N.4 — fuente real y verificada |
| Corrección aplicada | `\nocite{coip_2014}` agregado al bloque `\nocite{}` de Cap. I |
| Recomendación adicional | Agregar `\parencite{coip_2014}` en Cap. II o III cuando se cite el art. 260 COIP en el análisis de la distinción legal/ilegal del sector minero |

### NC-02 — `reglamento_general_ley_mineria_2009` ✅ Corregida

| Campo | Detalle |
|---|---|
| Entrada | Reglamento General a la Ley de Minería, 2009 (R.O. Suplemento 67, 16-nov-2009) |
| Causa de la ausencia | Mencionado en tabla CDIU en texto descriptivo, sin clave BibTeX |
| Verificación local | Ficha: `fichas_normativas/reglamento_general_ley_mineria_ficha.md`; `matriz_normativa.md` N.6 — fuente real y verificada |
| Corrección aplicada | `\nocite{reglamento_general_ley_mineria_2009}` agregado al bloque `\nocite{}` de Cap. I |
| Recomendación adicional | Agregar `\parencite{reglamento_general_ley_mineria_2009}` en Cap. II cuando se analice la estructura institucional del ciclo minero (arts. 7-8 del Reglamento) |

---

## 6. Posibles fuentes inventadas o sin verificación local

**Resultado: ninguna fuente inventada detectada.** Las 25 entradas de `referencias.bib` tienen correspondencia verificada en fichas, matrices o ambas.

**Advertencias menores sin acción urgente:**

- `sanchez_romero_et_al_2026`: sin DOI en ficha ni en `.bib`. La fuente es real según la ficha y la `matriz_doctrina.md`. Dato no identificado localmente para DOI.
- `cedec_guia_2023`: sin URL verificable en ficha ni en `.bib`. La e-ISBN (978-9942-8887-7-8) y los autores están verificados en la ficha.

---

## 7. Problemas de formato APA 7

### P-APA-01 — Citas en texto plano en Cap. I (pendiente Fase 5)

Las citas del Cap. I están escritas como texto plano en lugar de `\parencite{}` o `\textcite{}`. No es un error en la etapa actual: el bloque `\nocite{}` garantiza la inclusión en la bibliografía. La conversión es obligatoria en Fase 5.

Estado: pendiente Fase 5. Prioridad: alta para Fase 5.

### P-APA-02 — Localizador de párrafo en citas textuales de sentencias (preventiva)

Las citas actuales de sentencias en Cap. III son paráfrasis de holdings generales, para las cuales APA 7 acepta la cita de la sentencia completa. Sin embargo, cuando en Cap. II y IV se realicen citas textuales, deberá incluirse el párrafo o numeral específico de la afirmación.

Estado: observación preventiva. Implementar al redactar Cap. II y IV. Prioridad: media.

### P-APA-03 — Nombre institucional abreviado en texto plano de Cap. I

Las citas en texto plano de Cap. I usan "Asamblea Constituyente, 2008" en lugar de "Asamblea Constituyente del Ecuador, 2008". Se resolverá automáticamente al convertir a `\parencite{cre_2008}` en Fase 5.

Estado: se resolverá en Fase 5. Prioridad: baja.

### P-APA-04 — Orden en citas múltiples con misma institución y año

`\parencite{cce_1149_19_jp_21,cce_32_17_in_21,cce_22_18_in_21}`: las tres son de la misma institución y año (2021). El orden cronológico de los fallos es: 32-17-IN/21 (junio), 22-18-IN/21 (septiembre), 1149-19-JP/21 (noviembre). El orden actual es inverso. ⚠️ Revisar en Fase 5.

Estado: revisión menor pendiente Fase 5. Prioridad: baja.

---

## 8. Problemas con fuentes jurídicas

### P-JUR-01 — `ley_mineria_2025`: campo `year = {2009}` en entrada de texto consolidado 2025

La entrada `ley_mineria_2025` tiene `year = {2009}` (año del texto original). En la presentación APA 7, el año que aparecerá en la cita será "2009", aunque el texto utilizado es la versión consolidada hasta agosto de 2025. La `nota` del `.bib` aclara esto, pero puede generar confusión.

Recomendación: mantener la nota aclaratoria. Evaluar antes de la entrega final si el reglamento de titulación requiere indicar el año de la versión utilizada explícitamente.

Prioridad: media. No urgente para compilación.

### P-JUR-02 — `reglamento_coa_2019` con `\parencite{}` en Cap. III pero sin `\nocite{}` en Cap. I

La clave tiene `\parencite{}` en Cap. III, lo que garantiza su procesamiento por Biber en la compilación actual. Se puede agregar `\nocite{reglamento_coa_2019}` al bloque de Cap. I como resguardo adicional.

Prioridad: baja. Opcional.

---

## 9. Estado de las tablas LaTeX

### Tabla 1 — `tabla_cdiu.tex`

| Elemento | Estado |
|---|---|
| `\caption{}` | ✅ Presente |
| `\label{tab:cdiu}` | ✅ Presente |
| Nota al pie | ✅ Dentro de la tabla con `\multicolumn` |
| Referencia `\ref{tab:cdiu}` en texto | ✅ Presente en Cap. I |
| Análisis posterior | ✅ Dos párrafos explícitos en Cap. I |
| Estado | ✅ Conforme |

### Tabla 2 — `tabla_analisis_documental.tex`

| Elemento | Estado |
|---|---|
| `\caption{}` | ✅ Presente |
| `\label{tab:analisis_documental}` | ✅ Presente |
| Nota al pie | ✅ Presente como `\noindent\textit{Nota.}` después del `\endgroup` |
| Referencia `\ref{tab:analisis_documental}` en texto | ✅ Presente en Cap. III |
| Análisis posterior | ✅ Dos párrafos explícitos en Cap. III |
| Estado | ✅ Conforme con observación cosmética P-TAB-01 |

### P-TAB-01 — Nota de Tabla 2 fuera del entorno `longtable` (cosmético)

La nota de `tabla_analisis_documental.tex` está fuera del entorno `longtable`, a diferencia de la Tabla 1. Ambas formas son técnicamente correctas y cumplen APA 7. La diferencia es solo de uniformidad de formato.

Prioridad: muy baja. Solo si lo exige el formato de titulación.

---

## 10. Recomendaciones concretas de corrección

| Prioridad | Código | Recomendación | Archivo | Estado |
|---|---|---|---|---|
| ✅ Resuelta | NC-01 | `\nocite{coip_2014}` agregado al bloque de Cap. I | `capitulo_1_problema.tex` | ✅ Aplicada |
| ✅ Resuelta | NC-02 | `\nocite{reglamento_general_ley_mineria_2009}` agregado al bloque de Cap. I | `capitulo_1_problema.tex` | ✅ Aplicada |
| Alta (Fase 5) | P-APA-01 | Convertir citas en texto plano del Cap. I a `\parencite{}` y `\textcite{}` | `capitulo_1_problema.tex` | Pendiente Fase 5 |
| Media | P-JUR-01 | Evaluar campo `year` de `ley_mineria_2025` antes de entrega final | `referencias.bib` | Pendiente evaluación |
| Media (Cap. II/IV) | P-APA-02 | En citas textuales de sentencias en Cap. II y IV, incluir párrafo o numeral específico | Cap. II y IV (pendientes) | Implementar al redactar |
| Baja (Fase 5) | P-APA-04 | Verificar orden cronológico en `\parencite{cce_1149_19_jp_21,cce_32_17_in_21,cce_22_18_in_21}` | `capitulo_3_metodologia.tex` | Pendiente Fase 5 |
| Baja | OBS-01 | Citar `\parencite{cepal_ruta_escazu_2023}` en Cap. II o IV al analizar brechas normativas de Escazú | Cap. II o IV | Pendiente al redactar |
| Baja | P-JUR-02 | Evaluar agregar `\nocite{reglamento_coa_2019}` en Cap. I como resguardo | `capitulo_1_problema.tex` | Opcional |
| Muy baja | P-TAB-01 | Uniformidad de formato de nota entre Tabla 1 y Tabla 2 | `tabla_analisis_documental.tex` | Solo si lo exige el formato |

---

## 11. Conclusión — ¿El documento está listo para la revisión final?

**El documento NO tiene fuentes inventadas, autores ficticios, sentencias inexistentes ni referencias sin respaldo documental local.**

**El Capítulo III está listo en términos de citación.** Las 22 claves usadas con `\parencite{}` existen en `referencias.bib` y están verificadas en fichas o matrices. Las paráfrasis tienen autor y año conforme a APA 7. No hay citas textuales en Cap. III (capítulo metodológico); no aplica exigencia de análisis posterior a cita textual.

**El Capítulo I está en estado transitorio aprobado.** El bloque `\nocite{}` ahora contiene 23 claves (21 originales + 2 correctivas). Todas verificadas. La conversión a `\parencite{}` se realizará en Fase 5.

**`referencias.bib` está completo y funcional.** Las 25 entradas tienen citación activa: 22 con `\parencite{}`/`\textcite{}` en Cap. III, 3 adicionales con `\nocite{}` en Cap. I. Las tablas cumplen todos los requisitos APA 7.

**El documento está en condición de continuar con la redacción del Capítulo II.** Tras completar los Caps. II y IV, proceder a Fase 5 con conversión total de citas transitorias a `\parencite{}`.
