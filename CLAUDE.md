# CLAUDE.md

## 1. Proyecto

Trabajo de titulación en Derecho:

**“Análisis de derecho ambiental ecuatoriano: Revisión crítica de proyectos de ley de apertura al sector minero privado.”**

El título debe mantenerse exactamente igual durante todo el proyecto. No debe ser reformulado, resumido ni reemplazado.

---

## 2. Objetivo general del repositorio

Este repositorio organiza el proceso completo de investigación, análisis documental, redacción académica y compilación en LaTeX del trabajo de titulación.

Flujo general:

```text
PDF original
→ conversión a Markdown
→ ficha documental
→ matriz de análisis
→ redacción en LaTeX
→ revisión de citas
→ revisión de coherencia
→ compilación del PDF final
```

Los PDFs originales funcionan como respaldo verificable.

Los archivos `.md` funcionan como versión liviana para lectura y análisis.

Las fichas y matrices funcionan como base de control para reducir tokens, evitar duplicación de lectura, impedir fuentes inventadas y mantener coherencia entre capítulos.

Los capítulos finales se redactan en LaTeX.

---

## 3. Alcance de la investigación

El alcance de la investigación es **nacional**.

El análisis se centra en:

- Ecuador;
- ordenamiento jurídico ecuatoriano;
- derecho ambiental ecuatoriano;
- sector minero privado ecuatoriano;
- proyectos de ley o reformas relacionadas con apertura minera privada;
- seguridad jurídica;
- control estatal;
- derechos de la naturaleza;
- licenciamiento ambiental;
- consulta ambiental;
- consulta previa cuando corresponda;
- responsabilidad ambiental;
- reparación integral.

No delimitar la investigación a una provincia, ciudad, cantón o caso territorial específico.

Los casos territoriales, conflictos concretos o ejemplos provinciales solo pueden utilizarse como referencias ilustrativas o antecedentes contextuales, pero no como delimitación formal ni eje principal de la investigación.

---

## 4. Enfoque metodológico

La investigación tiene enfoque:

- cualitativo;
- documental;
- jurídico-crítico;
- normativo;
- jurisprudencial;
- legislativo;
- descriptivo;
- analítico.

No se trata de una investigación cuantitativa ni estadística.

El análisis debe interpretar normas, reformas, proyectos de ley verificables, jurisprudencia, doctrina académica, documentos institucionales, fuentes internacionales y prensa contextual cuando corresponda.

---

## 5. Idea central de la investigación

La investigación no debe plantearse como una oposición absoluta a la minería privada.

La tesis debe analizar críticamente si la apertura del sector minero privado puede ser compatible con el derecho ambiental ecuatoriano cuando respeta:

- derechos de la naturaleza;
- prevención;
- precaución;
- no regresividad ambiental;
- in dubio pro natura;
- consulta ambiental;
- consulta previa cuando corresponda;
- participación ciudadana;
- licenciamiento ambiental;
- fiscalización estatal;
- transparencia;
- responsabilidad ambiental;
- reparación integral;
- seguridad jurídica.

La seguridad jurídica no debe entenderse como eliminación de controles ambientales, sino como existencia de reglas claras, competencias definidas, procedimientos previsibles, obligaciones precisas y control estatal efectivo.

---

## 6. Reglas obligatorias

1. No inventar fuentes, autores, sentencias, leyes, artículos, proyectos de ley, datos, citas ni referencias.

2. No tratar un proyecto de ley como ley vigente si no existe Registro Oficial o publicación oficial que confirme su vigencia.

3. Diferenciar siempre entre:

   - norma vigente;
   - reforma legal vigente;
   - Registro Oficial;
   - proyecto de ley;
   - informe técnico legislativo;
   - informe de primer debate;
   - informe de segundo debate;
   - texto aprobado;
   - objeción del Ejecutivo;
   - respuesta de la Corte Constitucional;
   - documento archivado;
   - noticia de prensa;
   - doctrina académica;
   - documento institucional.

4. No confundir minería privada legal con minería ilegal.

5. No confundir minería artesanal, pequeña minería, mediana minería y minería a gran escala.

6. No confundir apertura al sector minero privado con permisividad frente a la minería ilegal.

7. No usar documentos archivados, no calificados, noticias o documentos no oficiales como eje principal de la investigación.

8. Los PDFs originales son respaldo documental. Los archivos `.md` son versión de lectura, no reemplazan la fuente original.

9. Si falta un dato en una fuente, escribir: **“Dato no identificado en el documento”**.

10. Toda afirmación jurídica importante debe estar respaldada por una fuente local, ficha, matriz o documento verificable.

11. No usar fuentes externas directamente en la redacción final si no han sido incorporadas al proyecto.

12. No agregar bibliografía no revisada.

13. No agregar citas textuales sin página, párrafo o ubicación verificable.

14. Toda cita textual debe ir acompañada de análisis propio posterior.

15. Toda tabla debe tener número, título, nota y análisis posterior.

16. La tesis final se redacta en LaTeX, no en Word.

---

## 7. Estructura actual de fuentes

Las fuentes locales se organizan en:

```text
01_fuentes_pdf_originales/
02_fuentes_md/
03_fichas/
04_matrices/
```

Actualmente las fuentes se clasifican así:

```text
01_fuentes_pdf_originales/
├── normativa/
├── jurisprudencia/
├── doctrina/
├── institucional/
├── internacional/
├── prensa/
└── reformas_legislativas/

02_fuentes_md/
├── normativa/
├── jurisprudencia/
├── doctrina/
├── institucional/
├── internacional/
├── prensa/
└── reformas_legislativas/
```

Si se incorporan proyectos de ley, registros oficiales, informes legislativos o documentos de Asamblea Nacional, deben guardarse preferentemente en:

```text
01_fuentes_pdf_originales/reformas_legislativas/
02_fuentes_md/reformas_legislativas/
```

---

## 8. Prioridad de consulta

Antes de leer documentos completos, revisar:

1. `04_matrices/`
2. `03_fichas/`
3. `02_fuentes_md/`
4. `01_fuentes_pdf_originales/`

No redactar capítulos extensos directamente desde PDFs o `.md` sin crear primero fichas y matrices.

No releer todos los documentos si ya existen fichas y matrices actualizadas.

---

## 9. Consulta de fuentes externas

La prioridad siempre serán las fuentes locales del proyecto.

Si una información no se encuentra en las fuentes locales, Claude puede consultar fuentes externas para localizar documentos verificables.

Fuentes externas permitidas:

- Asamblea Nacional del Ecuador;
- Registro Oficial;
- Corte Constitucional del Ecuador;
- Ministerio del Ambiente, Agua y Transición Ecológica;
- Ministerio de Energía y Minas;
- organismos de control minero;
- repositorios universitarios;
- tesis de grado o posgrado;
- artículos científicos;
- revistas académicas;
- libros;
- capítulos de libro;
- organismos internacionales oficiales;
- bases académicas verificables;
- medios de comunicación ecuatorianos, solo como contexto.

Reglas:

1. Primero buscar en fuentes locales.
2. Si no existe información suficiente, consultar fuentes externas solo para localizar documentos.
3. Reportar la fuente encontrada antes de usarla.
4. No usar fuentes externas no verificadas como base directa de redacción.
5. No citar fuentes externas que no hayan sido descargadas, revisadas y agregadas al proyecto.
6. Recomendar descarga o guardado de la fuente.
7. Recomendar conversión a `.md` cuando corresponda.
8. Solo después de incorporarla en `02_fuentes_md/`, podrá usarse para fichas, matrices, citas o redacción.
9. No inventar enlaces, autores, sentencias, proyectos, artículos ni datos.

---

## 10. Prensa ecuatoriana

La prensa ecuatoriana puede usarse como fuente contextual.

Puede servir para:

- debates públicos;
- conflictos socioambientales;
- minería ilegal;
- reformas recientes;
- declaraciones de autoridades;
- posiciones institucionales;
- identificación de fuentes primarias;
- contexto actual del sector minero.

La prensa no debe reemplazar:

- normas;
- sentencias;
- doctrina académica;
- proyectos de ley oficiales;
- informes legislativos;
- Registro Oficial;
- documentos institucionales.

Si una noticia menciona una reforma, sentencia, proyecto de ley, dato oficial o informe institucional, Claude debe buscar la fuente primaria antes de usarla como respaldo jurídico.

Las noticias incorporadas se guardan en:

```text
01_fuentes_pdf_originales/prensa/
02_fuentes_md/prensa/
03_fichas/fichas_prensa/
04_matrices/matriz_prensa_contextual.md
```

---

## 11. Reformas legislativas y proyectos de ley

El repositorio no contiene actualmente una carpeta local de Asamblea Nacional ni expedientes legislativos completos organizados por código de proyecto.

Por tanto, Claude no debe asumir que existen documentos legislativos locales disponibles.

Si se requiere analizar proyectos de ley, reformas recientes o documentos legislativos, primero debe buscar fuentes verificables mediante:

```text
/project:buscar-fuente
```

Las fuentes legislativas encontradas no deben usarse directamente en la redacción final hasta que hayan sido revisadas, descargadas e incorporadas al repositorio.

Si se incorporan, deben guardarse en:

```text
01_fuentes_pdf_originales/reformas_legislativas/
02_fuentes_md/reformas_legislativas/
03_fichas/fichas_reformas_legislativas/
04_matrices/matriz_reformas_legislativas.md
```

La investigación podrá apoyarse principalmente en:

- normativa vigente;
- jurisprudencia constitucional;
- doctrina académica;
- documentos institucionales;
- fuentes internacionales;
- prensa ecuatoriana contextual.

Esto no elimina el enfoque legislativo de la tesis. La revisión crítica de proyectos de ley o reformas de apertura minera privada se mantendrá, pero solo con fuentes verificables y útiles para el análisis.

---

## 12. Instrucciones del proyecto

Los archivos de instrucciones se encuentran en:

```text
00_instrucciones/
```

Archivos esperados:

- `anteproyecto.md`
- `formato_titulacion_referencia.md`
- `estructura_capitulos.md`
- `criterios_apa7.md`
- `criterios_fuentes.md`
- `criterios_latex.md`
- `criterios_redaccion.md`
- `criterios_reformas_legislativas.md`
- `criterios_tablas_figuras.md`
- `flujo_trabajo.md`
- `glosario_tesis.md`

Para estructura de capítulos, títulos, subtítulos y numeración, revisar siempre:

```text
00_instrucciones/estructura_capitulos.md
```

Para proyectos de ley, reformas, registros oficiales o fuentes legislativas, revisar:

```text
00_instrucciones/criterios_reformas_legislativas.md
```

Para fuentes externas, prensa y verificación, revisar:

```text
00_instrucciones/criterios_fuentes.md
```

---

## 13. Agentes disponibles

Los subagentes del proyecto están en:

```text
.claude/agents/
```

Agentes esperados:

- `source-ingestor`
- `normativa-analyst`
- `legislative-analyst`
- `jurisprudence-analyst`
- `doctrine-analyst`
- `latex-writer`
- `citation-auditor`
- `consistency-reviewer`

Uso esperado:

- `source-ingestor`: crea fichas documentales generales, institucionales, internacionales y de prensa.
- `normativa-analyst`: analiza normas vigentes y reformas publicadas.
- `legislative-analyst`: analiza proyectos de ley, reformas legislativas, registros oficiales e informes legislativos.
- `jurisprudence-analyst`: analiza sentencias y opiniones consultivas.
- `doctrine-analyst`: analiza tesis, artículos, revistas, libros, capítulos y doctrina.
- `latex-writer`: redacta capítulos en LaTeX.
- `citation-auditor`: revisa citas y bibliografía.
- `consistency-reviewer`: revisa coherencia metodológica y jurídica.

Los agentes no deben inventar información ni redactar fuera de su función.

---

## 14. Commands disponibles

Los comandos del proyecto están en:

```text
.claude/commands/
```

Commands esperados:

- `iniciar-investigacion.md`
- `estado.md`
- `buscar-fuente.md`
- `analizar-lote.md`
- `analizar-reformas-legislativas.md`
- `redactar-capitulo.md`
- `revisar-citas.md`
- `revisar-coherencia.md`
- `revisar-tesis.md`
- `compilar.md`

Uso recomendado:

```text
/project:iniciar-investigacion
/project:estado
/project:buscar-fuente tema
/project:analizar-lote normativa
/project:analizar-lote jurisprudencia
/project:analizar-lote internacional
/project:analizar-lote institucional
/project:analizar-lote doctrina
/project:analizar-lote prensa
/project:analizar-lote reformas_legislativas
/project:redactar-capitulo capitulo_1_problema
/project:revisar-citas
/project:revisar-coherencia
/project:revisar-tesis
/project:compilar
```

El comando `/project:analizar-reformas-legislativas` se mantiene solo por compatibilidad si en el futuro se incorporan expedientes legislativos específicos. Si no existe carpeta o fuente legislativa local, no debe reportarse error crítico; se debe recomendar `/project:buscar-fuente`.

---

## 15. Skills disponibles

Las skills del proyecto están en:

```text
.claude/skills/
```

Skills esperadas:

- `iniciar-investigacion`
- `analizar-lote`
- `redactar-capitulo`
- `revisar-tesis`

Los commands se usan para invocar rápido tareas específicas.

Las skills se usan para flujos más completos y reutilizables.

Los agents ejecutan tareas especializadas.

No eliminar commands ni skills. Pueden coexistir.

---

## 16. Fichas documentales

Las fichas se guardan en:

```text
03_fichas/
```

Subcarpetas esperadas:

```text
03_fichas/fichas_normativas/
03_fichas/fichas_jurisprudenciales/
03_fichas/fichas_doctrina/
03_fichas/fichas_institucionales/
03_fichas/fichas_internacionales/
03_fichas/fichas_prensa/
03_fichas/fichas_reformas_legislativas/
```

Cada ficha debe incluir, según corresponda:

- nombre del documento;
- tipo de documento;
- institución, autor o medio;
- año o fecha;
- estado jurídico;
- tema central;
- ideas relevantes;
- artículos, secciones o páginas relevantes;
- relación con la tesis;
- capítulo donde puede usarse;
- advertencias;
- prioridad;
- citas potenciales, solo si son verificables.

Las fichas no reemplazan las fuentes originales.

Las fichas sirven para ahorrar contexto y evitar que se relean documentos completos de manera innecesaria.

---

## 17. Matrices

Las matrices se guardan en:

```text
04_matrices/
```

Matrices esperadas:

- `estado_del_proyecto.md`
- `matriz_fuentes.md`
- `matriz_normativa.md`
- `matriz_jurisprudencial.md`
- `matriz_doctrina.md`
- `matriz_prensa_contextual.md`
- `matriz_reformas_legislativas.md`
- `matriz_cdiu.md`
- `matriz_compatibilidad_constitucional_ambiental.md`
- `reporte_revision_citas.md`
- `reporte_coherencia_metodologica.md`
- `reporte_compilacion_latex.md`

Si se requiere separar fuentes internacionales o institucionales, puede crearse:

- `matriz_internacional.md`
- `matriz_institucional.md`

No redactar capítulos sin revisar matrices relevantes.

---

## 18. Matriz de compatibilidad constitucional y ambiental

La propuesta central del Capítulo IV será una:

**Matriz de Verificación de Compatibilidad Constitucional y Ambiental para Proyectos de Ley de Apertura Minera Privada.**

La matriz debe evaluar:

- derechos de la naturaleza;
- principio de prevención;
- principio de precaución;
- principio de no regresividad;
- principio in dubio pro natura;
- consulta ambiental;
- consulta previa cuando corresponda;
- participación ciudadana;
- licenciamiento ambiental;
- fiscalización estatal;
- transparencia;
- responsabilidad ambiental;
- reparación integral;
- seguridad jurídica;
- incidencia en el sector minero privado.

Esta propuesta debe derivarse del análisis de normas, jurisprudencia, reformas verificables, doctrina, documentos institucionales, fuentes internacionales y, si corresponde, prensa contextual.

---

## 19. Estructura del documento final en LaTeX

Archivo principal:

```text
main.tex
```

Capítulos:

```text
05_capitulos/preliminares.tex
05_capitulos/introduccion.tex
05_capitulos/capitulo_1_problema.tex
05_capitulos/capitulo_2_marco_referencial.tex
05_capitulos/capitulo_3_metodologia.tex
05_capitulos/capitulo_4_propuesta.tex
05_capitulos/conclusiones.tex
05_capitulos/recomendaciones.tex
```

Tablas:

```text
06_tablas/tabla_cdiu.tex
06_tablas/matriz_reformas_legislativas.tex
06_tablas/matriz_normativa.tex
06_tablas/matriz_jurisprudencial.tex
06_tablas/matriz_compatibilidad.tex
```

Anexos:

```text
07_anexos/anexos.tex
```

Bibliografía:

```text
referencias.bib
```

Salida:

```text
08_build/
```

---

## 20. Estructura académica del documento

La estructura detallada está en:

```text
00_instrucciones/estructura_capitulos.md
```

Claude debe respetar títulos, subtítulos, numeración y apartados establecidos allí.

No inventar otros títulos ni subtítulos salvo que se proponga mejora justificada.

---

## 21. Objetivo general de la tesis

Analizar críticamente la compatibilidad de los proyectos de ley y reformas orientadas a la apertura del sector minero privado con los principios del derecho ambiental ecuatoriano, los derechos de la naturaleza, la seguridad jurídica y los mecanismos de control estatal aplicables al sector minero en el Ecuador.

---

## 22. Objetivos específicos

1. Examinar el marco constitucional, legal y jurisprudencial aplicable a la actividad minera privada en Ecuador, con énfasis en los derechos de la naturaleza, los principios de prevención, precaución, no regresividad, responsabilidad ambiental, consulta, participación ciudadana y control estatal.

2. Identificar los principales cambios normativos propuestos o incorporados en proyectos de ley y reformas vinculadas a la apertura del sector minero privado, valorando su incidencia en la seguridad jurídica y en los estándares de protección ambiental.

3. Evaluar los efectos jurídicos que la apertura normativa al sector minero privado podría generar sobre el licenciamiento ambiental, la fiscalización estatal, la responsabilidad de los concesionarios, la consulta y la reparación integral en el Ecuador.

4. Proponer lineamientos jurídicos orientados a armonizar la inversión minera privada con la protección ambiental, la seguridad jurídica, la consulta efectiva, la reparación integral y el respeto a los derechos de la naturaleza.

---

## 23. Formulación del problema

¿De qué manera los proyectos de ley y reformas orientadas a la apertura del sector minero privado resultan compatibles con los principios del derecho ambiental ecuatoriano, los derechos de la naturaleza, la seguridad jurídica y los mecanismos de control estatal aplicables al sector minero en el Ecuador?

---

## 24. Sistematización del problema

1. ¿Cuál es el marco constitucional, legal y jurisprudencial que regula la actividad minera privada y la protección ambiental en el Ecuador?

2. ¿Qué cambios introducen o proponen los proyectos de ley y reformas relacionados con la apertura del sector minero privado?

3. ¿Qué efectos jurídicos podrían generar dichas reformas sobre la seguridad jurídica, el licenciamiento ambiental, la fiscalización estatal, la consulta y la responsabilidad ambiental del sector minero privado?

4. ¿Qué lineamientos jurídicos permitirían armonizar la apertura al sector minero privado con la protección de los derechos de la naturaleza, el control estatal y los principios del derecho ambiental ecuatoriano?

---

## 25. Premisa o idea a defender

La apertura del sector minero privado puede ser compatible con el ordenamiento jurídico ecuatoriano únicamente si se somete a estándares reforzados de control ambiental, prevención, precaución, consulta, participación ciudadana, transparencia, fiscalización estatal, reparación integral y respeto a los derechos de la naturaleza; de lo contrario, podría generar riesgos de regresividad ambiental, conflictividad social, inseguridad jurídica e incertidumbre para el propio sector minero formal.

---

## 26. Reglas de redacción académica

Usar lenguaje formal, jurídico, claro y académico.

Evitar:

- lenguaje político o militante;
- afirmaciones absolutas no demostradas;
- frases genéricas sin contenido jurídico;
- repeticiones;
- párrafos demasiado cortos;
- párrafos demasiado extensos;
- citas sin análisis;
- tablas sin explicación;
- conclusiones genéricas.

---

## 27. Reglas APA 7

Aplicar APA séptima edición.

Reglas:

1. Cita textual corta: menos de 40 palabras, entre comillas dobles, con autor o institución, año y página o párrafo.
2. Cita textual larga: 40 palabras o más, en bloque, sin comillas, con autor o institución, año y página o párrafo.
3. Toda cita textual debe tener análisis propio posterior.
4. Paráfrasis: autor o institución y año.
5. No incluir referencias no citadas.
6. No citar fuentes no revisadas.
7. No inventar páginas.
8. En normas jurídicas, identificar institución, año, norma, Registro Oficial si corresponde y artículo.
9. En sentencias, identificar Corte, número de sentencia, año y caso.
10. En proyectos de ley, identificar Asamblea Nacional, año, título, código legislativo, proponente si corresponde, comisión y estado del trámite.
11. En informes legislativos, identificar etapa legislativa.
12. En Registro Oficial, identificar número, suplemento si corresponde y fecha.
13. En noticias, identificar medio, fecha, autor si consta y URL, y usarlas solo como contexto.

---

## 28. Reglas para LaTeX

La tesis se redacta en LaTeX.

Usar:

```latex
\chapter{}
\section{}
\subsection{}
\subsubsection{}
```

Toda tabla debe tener:

- título;
- etiqueta;
- nota;
- análisis posterior.

No modificar contenido jurídico solo para resolver errores de compilación, salvo errores menores de formato.

Al compilar, usar:

```powershell
scripts/compilar_latex.ps1
```

La salida debe ir en:

```text
08_build/
```

---

## 29. Flujo de trabajo recomendado

### Fase 1: Inicio

```text
/project:iniciar-investigacion
```

### Fase 2: Estado

```text
/project:estado
```

### Fase 3: Análisis por lotes

Ejecutar en este orden:

```text
/project:analizar-lote normativa
/project:analizar-lote jurisprudencia
/project:analizar-lote internacional
/project:analizar-lote institucional
/project:analizar-lote doctrina
```

Si se incorporan noticias:

```text
/project:analizar-lote prensa
```

Si se incorporan proyectos de ley o reformas legislativas:

```text
/project:analizar-lote reformas_legislativas
```

Para buscar fuentes externas:

```text
/project:buscar-fuente tema
```

### Fase 4: Redacción

Orden recomendado:

1. Capítulo I.
2. Capítulo III.
3. Capítulo II.
4. Capítulo IV.
5. Conclusiones.
6. Recomendaciones.
7. Introducción final.
8. Resumen y abstract.

### Fase 5: Revisión

```text
/project:revisar-coherencia
/project:revisar-citas
/project:revisar-tesis
```

### Fase 6: Compilación

```text
/project:compilar
```

---

## 30. Reglas para conclusiones

Las conclusiones deben responder directamente a los objetivos específicos.

No redactar conclusiones genéricas.

Cada conclusión debe derivarse de:

- análisis normativo;
- análisis de reformas verificables;
- análisis jurisprudencial;
- análisis doctrinal;
- matriz de compatibilidad;
- propuesta jurídica.

No introducir fuentes nuevas en conclusiones.

---

## 31. Reglas para recomendaciones

Las recomendaciones deben dirigirse a actores concretos:

- Asamblea Nacional, si se analizan reformas legislativas;
- Ministerio del Ambiente, Agua y Transición Ecológica;
- Ministerio de Energía y Minas;
- organismos de control;
- sector minero privado formal;
- academia;
- comunidades o actores sociales, si corresponde.

No redactar recomendaciones que no se deriven de hallazgos.

---

## 32. Reglas de seguridad del proyecto

No ejecutar comandos destructivos.

No eliminar carpetas.

No eliminar PDFs originales.

No borrar fichas ni matrices sin autorización.

No sobrescribir capítulos completos sin indicar qué se modificará.

No editar `referencias.bib` sin verificar la fuente.

No modificar `.gitignore`, `settings.json` o estructura de carpetas sin justificarlo.

---

## 33. Prioridad final

La prioridad del proyecto es producir una tesis:

- jurídicamente coherente;
- metodológicamente sólida;
- sustentada en fuentes verificables;
- sin referencias inventadas;
- con alcance nacional;
- redactada en LaTeX;
- con fichas y matrices que respalden cada capítulo;
- con diferenciación clara entre proyecto de ley, ley vigente, reforma vigente, fuente doctrinal, fuente institucional y prensa contextual.
