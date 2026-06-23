# Estado del proyecto
## Tesis: "Análisis de derecho ambiental ecuatoriano: Revisión crítica de proyectos de ley de apertura al sector minero privado."

**Fecha de actualización:** 23 de junio de 2026

---

## 1. Resumen ejecutivo

El proyecto completó la Fase 3 (análisis por lotes): las 24 fuentes disponibles han sido convertidas en fichas documentales y las 5 matrices de análisis por categoría están pobladas. El proyecto está listo para iniciar la Fase 4 (redacción de capítulos). Antes de redactar el Capítulo I se recomienda completar la **matriz CDIU**. Antes del Capítulo IV, la **matriz de compatibilidad constitucional y ambiental**.

---

## 2. Estructura de carpetas

| Carpeta | Estado | Observación |
|---|---|---|
| `00_instrucciones/` | ✅ Completo | 11 archivos presentes |
| `01_fuentes_pdf_originales/` | ✅ Completo | 24 PDFs en 5 subcarpetas activas |
| `02_fuentes_md/` | ✅ Completo | 24 archivos .md en 5 subcarpetas activas |
| `03_fichas/` | ✅ Completo | 24 fichas en 5 subcarpetas |
| `04_matrices/` | ⚠️ Parcial | 14 archivos; 5 matrices analíticas completas; 3 pendientes |
| `05_capitulos/` | ⚠️ Esqueleto | 8 archivos .tex; `preliminares.tex` con contenido; resto vacíos |
| `06_tablas/` | ⚠️ Esqueleto | 5 archivos .tex sin contenido académico |
| `07_anexos/` | ⚠️ Esqueleto | `anexos.tex` existe |
| `08_build/` | ✅ Compilado | `main.pdf` del esqueleto |
| `.claude/agents/` | ⚠️ Parcial | 7 de 8 agentes; falta `legislative-analyst.md` |
| `.claude/commands/` | ✅ Completo | 9 commands presentes |
| `.claude/skills/` | ⚠️ Parcial | 2 de 4 skills (`redactar-capitulo`, `revisar-tesis`) |
| `scripts/` | ✅ Completo | `compilar_latex.ps1`, `limpiar_build.ps1` |

---

## 3. Fuentes PDF originales (`01_fuentes_pdf_originales/`)

**Total: 24 PDFs**

| Subcarpeta | Documentos | Estado |
|---|---|---|
| `normativa/` | 10 PDFs | ✅ Completo |
| `jurisprudencia/` | 2 PDFs | ✅ Completo |
| `internacional/` | 3 PDFs | ✅ Completo |
| `institucional/` | 4 PDFs | ✅ Completo |
| `doctrina/` | 5 PDFs | ✅ Completo |
| `reformas_legislativas/` | 0 PDFs | ❌ Sin fuentes incorporadas |
| `prensa/` | 0 PDFs | ❌ Sin fuentes incorporadas |

---

## 4. Fuentes Markdown (`02_fuentes_md/`)

**Total: 24 archivos .md — correspondencia 1:1 con PDFs originales**

| Subcarpeta | Documentos | Estado |
|---|---|---|
| `normativa/` | 10 .md | ✅ Completo |
| `jurisprudencia/` | 2 .md | ✅ Completo |
| `internacional/` | 3 .md | ✅ Completo |
| `institucional/` | 4 .md | ✅ Completo |
| `doctrina/` | 5 .md | ✅ Completo |
| `reformas_legislativas/` | 0 .md | ❌ Sin fuentes |
| `prensa/` | 0 .md | ❌ Sin fuentes |

---

## 5. Fichas documentales (`03_fichas/`)

**Total: 24 fichas — análisis por lotes completado**

| Subcarpeta | Fichas | Estado |
|---|---|---|
| `fichas_normativas/` | 10 fichas | ✅ Completo |
| `fichas_jurisprudenciales/` | 2 fichas | ✅ Completo |
| `fichas_internacionales/` | 3 fichas | ✅ Completo |
| `fichas_institucionales/` | 4 fichas | ✅ Completo |
| `fichas_doctrina/` | 5 fichas | ✅ Completo |
| `fichas_reformas_legislativas/` | 0 fichas | ❌ Sin fuentes aún |
| `fichas_prensa/` | 0 fichas | ❌ Sin fuentes aún |

### Fichas normativas (10)

| Ficha | Prioridad |
|---|---|
| `constitucion_2008_ficha.md` | Alta |
| `codigo_organico_ambiente_ficha.md` | Alta |
| `reglamento_codigo_organico_ambiente_ficha.md` | Media |
| `coip_ficha.md` | Media |
| `ley_mineria_vigente_ficha.md` | Alta |
| `reglamento_general_ley_mineria_ficha.md` | Media |
| `instructivo_exploracion_explotacion_concesiones_mineras_ficha.md` | Media |
| `reforma_reglamento_general_ley_mineria_2025_ficha.md` | Alta |
| `registro_oficial_No_37_ley_reformatoria_a_la_ley_mineria_2013_ficha.md` | Alta |
| `ley_organica_fortalecimiento_sectores_estrategicos_mineria_energia_ficha.md` | Alta |

### Fichas jurisprudenciales (2)

| Ficha | Prioridad |
|---|---|
| `cce_1149_19_jp_21_los_cedros_ficha.md` | Alta |
| `cce_consulta_ambiental_ficha.md` | Alta |

*Nota: ambas fichas corresponden al mismo documento (Sentencia CCE No. 1149-19-JP/21), con enfoques diferenciados.*

### Fichas internacionales (3)

| Ficha | Prioridad |
|---|---|
| `acuerdo_escazu_ficha.md` | Alta |
| `cepal_ruta_implementacion_escazu_ecuador_2023_ficha.md` | Alta |
| `corte_idh_oc_23_17_medio_ambiente_ficha.md` | Alta |

### Fichas institucionales (4)

| Ficha | Prioridad |
|---|---|
| `plan_nacional_sector_minero_2020_2030_ficha.md` | Alta |
| `politica_minera_ecuador_ficha.md` | Alta |
| `arcom_agencia_regulacion_control_minero_ficha.md` | Alta |
| `borrador_informe_actualizacion_tasa_supervision_control_minero_ficha.md` | Media |

*Nota: `arcom_agencia_regulacion_control_minero_ficha.md` contiene la Resolución ARCOM-2025-0029-R de reapertura del Catastro Minero Nacional (8 julio 2025). `borrador_...` es borrador no aprobado, usar con cautela.*

### Fichas doctrinales (5)

| Ficha | Autor | Año | Prioridad |
|---|---|---|---|
| `derechos_naturaleza_extractivismo_minero_2021_carla_grefa_ficha.md` | Grefa Valencia, C. | 2021 | Alta |
| `mineria_ilegal_ecuador_analisis_juridico_2025_bryan_robalino_y_karina_cardenas_ficha.md` | Robalino & Cárdenas | 2025 | Media |
| `explotacion_minera_y_derecho_naturaleza_napo_2024_katherin_pillajo_ficha.md` | Pillajo Portero, K. | 2024 | Media |
| `responsabilidad_funcionario_para_autorizacion_concesion_minera_2012_angel_bustamante_ficha.md` | Bustamante Armijos, Á. | 2012 | Media-Baja |
| `delitos_ambientales_mineria_ilegal_2022_yanez_cevallos_y_sebastian_alejandro_ficha.md` | Yánez Cevallos, S. | 2022 | Media |

*Nota: Documentos 2, 3 y 5 tratan minería ilegal, no minería privada legal. Documento 4 es anterior al COIP (2014).*

---

## 6. Matrices (`04_matrices/`)

### Matrices analíticas por lote — completadas

| Matriz | Estado | Observación |
|---|---|---|
| `matriz_normativa.md` | ✅ Completa | 10 instrumentos; 3 tablas; observaciones sobre tendencia simplificadora y Ley 2026 |
| `matriz_jurisprudencial.md` | ✅ Completa | 1 sentencia (2 fichas); Sentencia CCE 1149-19-JP/21 |
| `matriz_internacional.md` | ✅ Completa | 3 documentos; Acuerdo de Escazú, CEPAL, OC-23/17 |
| `matriz_institucional.md` | ✅ Completa | 4 documentos; Resolución reapertura catastro 2025, Plan Minero 2020-2030 |
| `matriz_doctrina.md` | ✅ Completa | 5 documentos; vacíos doctrinales identificados |

### Matrices de análisis transversal — pendientes

| Matriz | Estado | Observación |
|---|---|---|
| `matriz_fuentes.md` | ❌ Vacía | Consolidación general de todas las fuentes; puede crearse ahora |
| `matriz_cdiu.md` | ❌ Vacía | Categorías, Dimensiones, Instrumentos y Unidades de análisis; necesaria para Cap. I |
| `matriz_compatibilidad_constitucional_ambiental.md` | ❌ Vacía | Propuesta central del Cap. IV; necesaria antes de redactar Cap. IV |

### Matrices de fuentes sin contenido aún

| Matriz | Estado | Observación |
|---|---|---|
| `matriz_reformas_legislativas.md` | ❌ Vacía | Sin fuentes legislativas incorporadas |
| `matriz_prensa_contextual.md` | ❌ Vacía | Sin fuentes de prensa incorporadas |

### Reportes — pendientes

| Reporte | Estado |
|---|---|
| `reporte_revision_citas.md` | ❌ Vacío — se ejecuta con `/revisar-citas` |
| `reporte_coherencia_metodologica.md` | ❌ Vacío — se ejecuta con `/revisar-coherencia` |
| `reporte_compilacion_latex.md` | ❌ Vacío — se ejecuta con `/compilar` |

---

## 7. Capítulos LaTeX (`05_capitulos/`)

| Archivo | Estado | Contenido actual |
|---|---|---|
| `preliminares.tex` | ✅ Con contenido | Portada (Universidad de Guayaquil, Autora: Angie Samantha Rivera Vega), dedicatoria, agradecimiento, resumen, abstract — esqueleto con secciones definidas |
| `introduccion.tex` | ❌ Vacío | Solo encabezado |
| `capitulo_1_problema.tex` | ❌ Vacío | Solo `\chapter{El problema de investigación}` |
| `capitulo_2_marco_referencial.tex` | ❌ Vacío | Solo `\chapter{Marco referencial}` |
| `capitulo_3_metodologia.tex` | ❌ Vacío | Solo `\chapter{Marco metodológico}` |
| `capitulo_4_propuesta.tex` | ❌ Vacío | Solo `\chapter{Propuesta}` |
| `conclusiones.tex` | ❌ Vacío | Solo encabezado |
| `recomendaciones.tex` | ❌ Vacío | Solo encabezado |

---

## 8. Tablas LaTeX (`06_tablas/`)

| Archivo | Estado |
|---|---|
| `tabla_cdiu.tex` | ❌ Sin contenido académico |
| `matriz_reformas_legislativas.tex` | ❌ Sin contenido académico |
| `matriz_normativa.tex` | ❌ Sin contenido académico |
| `matriz_jurisprudencial.tex` | ❌ Sin contenido académico |
| `matriz_compatibilidad.tex` | ❌ Sin contenido académico |

---

## 9. Archivo principal y bibliografía

| Archivo | Estado |
|---|---|
| `main.tex` | ✅ Completo — estructura LaTeX lista |
| `referencias.bib` | ❌ Vacío — solo comentario inicial |

---

## 10. Hallazgos importantes de los análisis por lotes

### Hallazgos normativos
- El archivo `reforma_reglamento_general_ley_mineria_2025.md` tiene nombre incorrecto: contiene el texto consolidado de la Ley de Minería hasta agosto de 2025, no una reforma al Reglamento General.
- Existe una **Ley Orgánica para el Fortalecimiento de los Sectores Estratégicos de Minería y Energía (R.O. Quinto Suplemento No. 234, 2 de marzo de 2026)** — la más reciente del sector minero, incorporada en `ley_organica_fortalecimiento_sectores_estrategicos_mineria_energia.md`. Es el objeto central del análisis crítico de la tesis.
- La Ley Reformatoria de 2013 (R.O. 37) introdujo el silencio positivo de 6 meses con destitución del funcionario para licencias ambientales — antecedente de la simplificación normativa.
- La Ley de 2026 subordinó la ARCOM al Ministerio Sectorial, amplió la exploración a 15 años con transición automática entre subfases, y creó las Áreas Mineras con Protección de Seguridad Estratégica.

### Hallazgos jurisprudenciales
- Los dos archivos en `02_fuentes_md/jurisprudencia/` contienen el **mismo documento** (Sentencia CCE No. 1149-19-JP/21). Se recomienda incorporar sentencias adicionales (CCE No. 22-18-IN/21, CCE No. 1185-20-JP/21).
- La Sentencia 1149-19-JP/21 establece que el silencio positivo del Estado no suple la consulta ambiental obligatoria y que su omisión determina inejecutabilidad y nulidad del acto administrativo.

### Hallazgos institucionales
- La **Resolución ARCOM-2025-0029-R** (8 julio 2025) reabrió el Catastro Minero Nacional después de ~7 años de cierre (desde enero 2018). Apertura gradual: inicia solo con pequeña minería no metálica.
- El borrador del informe ARCOM 2026 revela que la propuesta de actualización de la tasa reduciría la recaudación de $ 221.755.348,68 a $ 44.044.113,98 (19,86% del valor actual), excluyendo fases exploratorias para incentivar la inversión privada.

### Hallazgos internacionales
- El **Acuerdo de Escazú** está vigente para Ecuador desde el 22 de abril de 2021 — es instrumento vinculante que incluye el principio de no regresión (art. 3.c).
- El caso **Llurimagua**: la Corte Provincial de Imbabura revocó una licencia ambiental minera de 2014 por falta de consulta ambiental (sentencia de 29 de marzo de 2023, documentada en el informe CEPAL).

### Vacíos doctrinales identificados
- No hay doctrina que analice directamente la **seguridad jurídica como principio para el sector minero privado**.
- No hay doctrina sobre el **principio de no regresividad ambiental** como límite a reformas legislativas.
- No hay doctrina que analice el **licenciamiento ambiental como procedimiento administrativo integral** en el sector minero.
- Ningún documento doctrinal analiza directamente **proyectos de ley de apertura minera privada**.

---

## 11. Acciones pendientes antes y durante la redacción

### Previas a la redacción (recomendadas)

| Acción | Comando | Estado |
|---|---|---|
| Completar `matriz_cdiu.md` | Manual o agente | ❌ Pendiente |
| Completar `matriz_fuentes.md` (consolidación) | Manual o agente | ❌ Pendiente |
| Buscar fuentes legislativas verificables (proyectos de ley) | `/buscar-fuente` | ❌ Pendiente |
| Buscar doctrina sobre no regresividad y seguridad jurídica minera | `/buscar-fuente` | ❌ Pendiente |

### Redacción de capítulos (orden recomendado)

| Capítulo | Comando | Estado |
|---|---|---|
| Capítulo I (El problema de investigación) | `/redactar-capitulo capitulo_1_problema` | ❌ Pendiente |
| Capítulo III (Marco metodológico) | `/redactar-capitulo capitulo_3_metodologia` | ❌ Pendiente |
| Capítulo II (Marco referencial) | `/redactar-capitulo capitulo_2_marco_referencial` | ❌ Pendiente |
| Capítulo IV (Propuesta + Matriz de compatibilidad) | `/redactar-capitulo capitulo_4_propuesta` | ❌ Pendiente |
| Conclusiones | `/redactar-capitulo conclusiones` | ❌ Pendiente |
| Recomendaciones | `/redactar-capitulo recomendaciones` | ❌ Pendiente |
| Introducción (al final) | `/redactar-capitulo introduccion` | ❌ Pendiente |

### Revisión y compilación final

| Acción | Comando | Estado |
|---|---|---|
| Revisión de coherencia | `/revisar-coherencia` | ❌ Pendiente |
| Revisión de citas y bibliografía | `/revisar-citas` | ❌ Pendiente |
| Revisión integral | `/revisar-tesis` | ❌ Pendiente |
| Compilación LaTeX | `/compilar` | ❌ Pendiente |

---

## 12. Síntesis de avance

| Fase | Estado |
|---|---|
| Fase 1 — Inicio: estructura y configuración | ✅ Completa |
| Fase 2 — Estado: verificación inicial | ✅ Completa |
| Fase 3 — Análisis por lotes | ✅ Completa (24 fichas / 5 matrices) |
| Fase 4 — Redacción de capítulos | ❌ Pendiente |
| Fase 5 — Revisión | ❌ Pendiente |
| Fase 6 — Compilación final | ❌ Pendiente |

**Fase actual del proyecto: inicio de Fase 4 — Redacción**

**Próximo comando recomendado:**

```
/redactar-capitulo capitulo_1_problema
```
