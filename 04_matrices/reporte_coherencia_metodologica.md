# Reporte de coherencia metodológica y jurídica
## Tesis: "Análisis de derecho ambiental ecuatoriano: Revisión crítica de proyectos de ley de apertura al sector minero privado."

**Fecha:** 24 de junio de 2026
**Revisión realizada por:** agente consistency-reviewer

---

## 1. Resumen general del estado de coherencia

El proyecto presenta un nivel de coherencia metodológica y jurídica alto en su componente documental y matricial. El título es exacto, el alcance es nacional, el problema de investigación está correctamente formulado, la sistematización responde a los objetivos específicos, y las matrices analíticas (normativa, jurisprudencial, internacional, institucional, doctrina, prensa, reformas legislativas, CDIU y compatibilidad constitucional) están articuladas de manera coherente con los cuatro objetivos específicos. No se detectan confusiones entre minería privada legal y minería ilegal, ni se tratan proyectos de ley como leyes vigentes sin Registro Oficial verificado.

Sin embargo, el proyecto entra en Fase 4 (redacción) con todos los capítulos LaTeX vacíos. Los problemas de coherencia verificables actualmente son de naturaleza estructural y anticipatoria. Los puntos críticos que deben resolverse antes de redactar son: (a) una inconsistencia entre el nombre de las columnas de la tabla CDIU y el esquema de cuatro columnas del anteproyecto; (b) un vacío de regulación de la consulta previa libre e informada que la propuesta debe abordar explícitamente; (c) el riesgo de que la tesis trate la Ley de Fortalecimiento 2026 como definitivamente vigente sin reconocer su estado de cuestionamiento constitucional; (d) la presencia de una fuente doctrinal con delimitación provincial; (e) la ausencia del expediente legislativo completo de la Ley de 2026; y (f) todas las tablas LaTeX vacías.

El proyecto puede iniciar la redacción del Capítulo I con las matrices disponibles. Los problemas identificados son corregibles durante la redacción y no invalidan el diseño metodológico.

---

## 2. Problemas encontrados

### Problema 1: Discrepancia entre el esquema CDIU de cuatro columnas y la tabla interna de nueve columnas
- **Gravedad:** baja
- **Archivo:** `04_matrices/matriz_cdiu.md`
- **Sección afectada:** Tabla principal de la CDIU; sección 1.9 del Capítulo I por redactar
- **Descripción:** El acrónimo CDIU corresponde a Categorías, Dimensiones, Instrumentos y Unidades de análisis. El anteproyecto (sección 11) y la estructura de capítulos (sección 1.9) definen cuatro columnas: Categorías, Dimensiones, Instrumentos, Unidades de análisis. La tabla interna en `matriz_cdiu.md` tiene nueve columnas: N°, Categoría, Dimensión, Indicadores/Aspectos de análisis, Instrumento, Unidad de análisis, Fuente principal en el repositorio, Objetivo específico, Capítulo. La tercera columna se denomina "Indicadores/Aspectos de análisis" en lugar de simplemente "Instrumentos", y hay una columna separada de "Instrumento". Esto genera una discrepancia entre la versión del instrumento declarada en el diseño y la versión desarrollada internamente.
- **Recomendación:** Antes de redactar la sección 1.9 del Capítulo I y crear `06_tablas/tabla_cdiu.tex`, decidir qué versión se presentará al lector: la simplificada de cuatro columnas conforme al anteproyecto, o la ampliada de nueve columnas de la matriz interna. Si se presenta la ampliada, actualizar el texto del Capítulo I para explicar el enriquecimiento del esquema. La tabla interna sigue siendo válida como soporte metodológico independientemente de la decisión.
- **Prioridad:** antes de redactar el Capítulo I

---

### Problema 2: Fuente Pillajo (2024) tiene delimitación provincial explícita en el título
- **Gravedad:** media
- **Archivo:** `04_matrices/matriz_doctrina.md`, entrada N° 3
- **Sección afectada:** Capítulos II y III donde se cite esta fuente
- **Descripción:** La fuente "La explotación minera y el derecho de la naturaleza en la provincia de Napo" (Pillajo Portero, 2024, UNACH, Riobamba) tiene delimitación espacial provincial explícita en el título. Su uso es admisible conforme a CLAUDE.md (referencias territoriales como ejemplos ilustrativos), pero si se cita sin advertencia puede generar la impresión de que la tesis se apoya en un estudio territorial como eje analítico, contradiciendo el alcance nacional declarado.
- **Recomendación:** Al citar a Pillajo (2024) en cualquier capítulo, indicar explícitamente que se trata de un estudio de caso territorial utilizado como ilustración del problema nacional. No usar esta fuente para afirmar conclusiones de alcance nacional. Verificar que la ficha documental de esta fuente incluya advertencia de uso.
- **Prioridad:** antes de redactar las secciones que la citen

---

### Problema 3: Estado procesal de la Ley de Fortalecimiento 2026 ante la CCE debe mantenerse visible en toda la tesis
- **Gravedad:** media
- **Archivo:** `04_matrices/matriz_cdiu.md` (fila 24); `04_matrices/matriz_compatibilidad_constitucional_ambiental.md` (nota metodológica); `05_capitulos/capitulo_3_metodologia.tex` (vacío); `05_capitulos/capitulo_4_propuesta.tex` (vacío)
- **Sección afectada:** Capítulos III, IV, Conclusiones y Recomendaciones
- **Descripción:** Las matrices documentan correctamente que existen al menos 11 demandas de inconstitucionalidad contra la Ley de Fortalecimiento 2026 ante la Corte Constitucional del Ecuador (al 5 de abril de 2026). Sin embargo, cuando los capítulos sean redactados, existe el riesgo de que el texto trate la ley como definitivamente vigente e inatacable. Si la CCE suspende o declara inconstitucional alguna disposición antes de cerrar la redacción, secciones enteras quedarían metodológicamente comprometidas.
- **Recomendación:** Al inicio de cada sección de los capítulos III y IV que analice la Ley de 2026, incluir advertencia metodológica explícita sobre el estado procesal ante la CCE. Las conclusiones y recomendaciones deben condicionar afirmaciones sobre efectos jurídicos de la ley a su subsistencia constitucional. Se recomienda nota a pie de página cada vez que se citen disposiciones de la Ley de 2026. Verificar el estado del proceso constitucional antes de cerrar la redacción.
- **Prioridad:** inmediata (antes de iniciar la redacción de los capítulos III y IV)

---

### Problema 4: El vacío de regulación de la CPLI no está señalado como problema de investigación en el planteamiento del Capítulo I, aunque sí está documentado en las matrices
- **Gravedad:** media
- **Archivo:** `00_instrucciones/anteproyecto.md`, sección 1.1; `04_matrices/matriz_compatibilidad_constitucional_ambiental.md`, criterio 7; `04_matrices/matriz_cdiu.md`, fila 26
- **Sección afectada:** Capítulo I (planteamiento del problema, sección 1.1), Capítulo IV (propuesta, sección 4.2.3)
- **Descripción:** El planteamiento del problema en el anteproyecto no identifica explícitamente como problema de investigación el vacío legislativo sobre la consulta previa libre e informada (CPLI) en el sector minero, derivado de la Sentencia 22-18-IN/21 (que declaró inconstitucionales los arts. 462 y 463 del RCOAM por regular la CPLI a nivel reglamentario sin que exista ley orgánica que la regule). Las matrices sí documentan el problema (fila 26 CDIU, criterio 7 Matriz de Compatibilidad), pero el planteamiento del problema y las preguntas de sistematización no lo hacen visible con la misma claridad.
- **Recomendación:** Al redactar la sección 1.1 del Capítulo I, incluir párrafo que señale el vacío de regulación de la CPLI como problema jurídico específico derivado de la Sentencia 22-18-IN/21 y no resuelto por la Ley de Fortalecimiento 2026. Al redactar la sección 4.2.3 del Capítulo IV, incluir como lineamiento jurídico la recomendación de expedición de una ley orgánica que regule la CPLI en el sector minero. Esto es coherente con el objetivo específico 4 y con el criterio 7 de la Matriz de Compatibilidad.
- **Prioridad:** antes de redactar el Capítulo I

---

### Problema 5: El repositorio no cuenta con el expediente legislativo completo de la Ley de Fortalecimiento 2026 ni con los proyectos AN-2018 y AN-2019 priorizados en el anteproyecto
- **Gravedad:** media
- **Archivo:** `04_matrices/matriz_reformas_legislativas.md`, observaciones 1 y 5; `00_instrucciones/anteproyecto.md`, sección 7
- **Sección afectada:** Capítulo II (sección 2.1.4 antecedentes legislativos), Capítulo III (secciones 3.6 y 3.8.3)
- **Descripción:** El anteproyecto (sección 7) identifica como fuentes prioritarias los proyectos AN-2020-1922, AN-2019-1639, AN-2019-1586, AN-2018-1436, AN-2018-1385 y AN-2018-1320, que no han sido descargados ni incorporados al repositorio. La matriz de reformas legislativas solo cuenta con una noticia institucional de la Sala de Prensa de la Asamblea Nacional (24 de febrero de 2026) sobre el informe de segundo debate. Para el expediente de la Ley de 2026, faltan el proyecto original, informe de primer debate, informe oficial de segundo debate, texto aprobado por el Pleno y eventuales documentos de objeción ejecutiva.
- **Recomendación:** Antes de redactar la sección 2.1.4 del Capítulo II y la sección 3.8.3 del Capítulo III, incorporar al repositorio los documentos del expediente legislativo de la Ley de 2026 disponibles en el portal de la Asamblea Nacional. Si no se incorporan antes de la redacción, declarar explícitamente en el Capítulo II que el análisis del proceso legislativo está basado en la ley publicada y en la noticia institucional disponible, señalando la limitación documental.
- **Prioridad:** antes de redactar el Capítulo II

---

### Problema 6: Todas las tablas LaTeX en `06_tablas/` están vacías
- **Gravedad:** media
- **Archivo:** `06_tablas/tabla_cdiu.tex`, `06_tablas/matriz_compatibilidad.tex`, `06_tablas/matriz_normativa.tex`, `06_tablas/matriz_jurisprudencial.tex`, `06_tablas/matriz_reformas_legislativas.tex`
- **Sección afectada:** Capítulos I, III, IV; Anexos
- **Descripción:** Todos los archivos `.tex` de tablas contienen una sola línea y están prácticamente vacíos. Las matrices en `04_matrices/` tienen contenido extenso y coherente, pero no ha sido trasladado a formato LaTeX. La Matriz de Compatibilidad tiene 16 criterios y 8 columnas, lo que requiere formato especial en LaTeX (longtable o landscape).
- **Recomendación:** Al redactar cada capítulo, crear simultáneamente la tabla LaTeX correspondiente en `06_tablas/`. Para `tabla_cdiu.tex`, esperar a resolver el Problema 1. Para `matriz_compatibilidad.tex`, usar `longtable` con rotación de página. Toda tabla debe cumplir CLAUDE.md regla 15: número, título, nota y análisis posterior en el texto del capítulo.
- **Prioridad:** antes de compilación (decisión estructural antes de redactar)

---

### Problema 7: `reporte_revision_citas.md` y `reporte_compilacion_latex.md` están vacíos
- **Gravedad:** baja (esperado en esta etapa)
- **Archivo:** `04_matrices/reporte_revision_citas.md`, `04_matrices/reporte_compilacion_latex.md`
- **Sección afectada:** Fases 5 y 6
- **Descripción:** Ambos archivos están vacíos porque el proyecto no ha iniciado la redacción. Esto es coherente con el estado actual (Fase 4 por iniciar). La ausencia del reporte de citas impide confirmar que las referencias de las matrices serán correctamente trasladadas a APA 7, pero no impide iniciar la redacción.
- **Recomendación:** Al completar la redacción de cada capítulo, ejecutar `/project:revisar-citas`. El reporte de compilación solo puede generarse en la Fase 6.
- **Prioridad:** antes de compilación

---

### Problema 8: El uso de las 16 fuentes de prensa requiere control estricto para evitar que sustituyan fuentes primarias en el texto
- **Gravedad:** baja
- **Archivo:** `04_matrices/matriz_prensa_contextual.md`; `00_instrucciones/estructura_capitulos.md`, sección 2.4.7
- **Sección afectada:** Capítulo II, sección 2.4.7; Capítulo III donde se contextualice la Ley de 2026
- **Descripción:** Hay 16 fuentes de prensa incorporadas. Su uso es admisible para contextualizar debates públicos, posiciones de actores y conflictividad socioambiental. El riesgo es que al redactar se use prensa para afirmar hechos que solo pueden sustentarse con fuentes primarias (por ejemplo: que la CCE ha admitido o resuelto una demanda).
- **Recomendación:** Usar las fuentes de prensa únicamente para describir el debate público y posiciones de actores. Cada vez que la prensa mencione un dato normativo, institucional o jurisprudencial, verificar si existe la fuente primaria en el repositorio antes de incorporarlo al texto. Aplicar APA 7 conforme a CLAUDE.md sección 27, criterio 13.
- **Prioridad:** antes de redactar el Capítulo II

---

### Problema 9: El título en la portada de `preliminares.tex` no incluye el punto final exigido por CLAUDE.md
- **Gravedad:** baja
- **Archivo:** `05_capitulos/preliminares.tex`
- **Sección afectada:** Portada del documento final
- **Descripción:** CLAUDE.md (sección 1) establece el título con punto al final. En `preliminares.tex` el título aparece sin punto al final. CLAUDE.md establece que el título debe mantenerse exactamente igual en todo el proyecto.
- **Recomendación:** Agregar el punto final al título en `preliminares.tex`. Verificar que el título con punto aparezca también en `main.tex`, en el resumen, en el abstract y en cualquier otra parte donde se mencione el título completo.
- **Prioridad:** antes de compilación

---

### Problema 10: El Capítulo III debe articular el enfoque "legislativo" de la metodología con la disponibilidad parcial de documentos legislativos
- **Gravedad:** media
- **Archivo:** `00_instrucciones/estructura_capitulos.md`, sección Capítulo III; `04_matrices/matriz_reformas_legislativas.md`; `05_capitulos/capitulo_3_metodologia.tex` (vacío)
- **Sección afectada:** Capítulo III, secciones 3.6 y 3.8.3
- **Descripción:** CLAUDE.md (sección 4) declara el enfoque "legislativo". La estructura de capítulos incluye secciones de análisis documental y legislativo (3.6 y 3.8.3). El repositorio legislativo es parcial: solo una noticia institucional y la ley publicada. Si el Capítulo III incluye la Matriz de análisis documental y legislativo sin declarar esta limitación, la presentación metodológica será incompleta.
- **Recomendación:** Al redactar la sección 3.6, indicar qué documentos legislativos están disponibles y cuáles están pendientes. Declarar que la tesis analiza el texto normativo publicado (Ley de Fortalecimiento 2026, R.O. 234-5S) y que el proceso legislativo previo se describe con base en la noticia institucional disponible.
- **Prioridad:** antes de redactar el Capítulo III

---

### Problema 11: El Comunicado CCE agosto 2025 se refiere a leyes ajenas al sector minero; su uso debe ser estrictamente limitado al aspecto procesal
- **Gravedad:** baja
- **Archivo:** `04_matrices/matriz_jurisprudencial.md`, entrada N° 2; `04_matrices/matriz_cdiu.md`, fila 24
- **Sección afectada:** Secciones de los capítulos I o III que expliquen el mecanismo de control constitucional
- **Descripción:** El Comunicado CCE de agosto 2025 (autos de admisión de los casos 60-25-IN, 86-25-IN, 57-25-IN) se refiere a demandas contra la Ley Orgánica de Integridad Pública, la Ley Orgánica de Inteligencia y la Ley Orgánica de Solidaridad Nacional, no al sector minero ni ambiental. El riesgo es que al redactar se presente este comunicado como evidencia del control constitucional sobre la Ley de Fortalecimiento 2026, lo que sería factualmente incorrecto.
- **Recomendación:** Usar el Comunicado CCE de agosto 2025 únicamente para explicar el procedimiento general de admisión de acciones de inconstitucionalidad y suspensión provisional de normas, dejando claro que las leyes impugnadas en ese comunicado no son las leyes mineras. Para el estado de las demandas contra la Ley de 2026, citar únicamente las fuentes de prensa (fichas 13 y 15) con la advertencia de que son fuentes contextuales.
- **Prioridad:** antes de redactar las secciones que mencionen control constitucional

---

### Problema 12: La bibliografía preliminar del anteproyecto incluye la fuente Trujillo Cárdenas (2021) que no ha sido incorporada al repositorio ni tiene ficha documental
- **Gravedad:** baja
- **Archivo:** `00_instrucciones/anteproyecto.md`, sección 12 (bibliografía preliminar)
- **Sección afectada:** `referencias.bib` (actualmente vacío)
- **Descripción:** La sección 12 del anteproyecto lista como referencia a Trujillo Cárdenas (2021), USFQ Law Review. Esta fuente no aparece en la matriz de doctrina ni tiene ficha en `03_fichas/`. CLAUDE.md reglas 1 y 12 prohíben inventar fuentes y agregar bibliografía no revisada.
- **Recomendación:** No incorporar a `referencias.bib` ni citar en el texto a Trujillo Cárdenas ni ninguna otra fuente de la bibliografía preliminar del anteproyecto que no tenga ficha en `03_fichas/` y registro en las matrices. Si se desea incorporarla, primero debe descargarse, convertirse a `.md`, ficharse y registrarse en `04_matrices/matriz_doctrina.md`.
- **Prioridad:** antes de redactar cualquier capítulo

---

## 3. Aspectos con coherencia confirmada

1. **Título exacto:** Aparece correctamente en el anteproyecto, estructura de capítulos, CLAUDE.md, encabezado de todas las matrices y `preliminares.tex` (salvo el punto final, Problema 9). Sin reformulaciones ni variaciones sustantivas.

2. **Alcance nacional sin delimitación territorial:** El anteproyecto, la estructura de capítulos y CLAUDE.md establecen con claridad que el alcance es nacional. Las matrices no delimitan el análisis a ningún territorio específico. La única fuente con delimitación provincial (Pillajo, 2024) ha sido identificada como riesgo manejable (Problema 2).

3. **Formulación del problema:** Idéntica en CLAUDE.md (sección 23), anteproyecto (sección 1.2) y estructura de capítulos (sección 1.2). Sin variaciones.

4. **Sistematización del problema:** Las cuatro preguntas son idénticas en CLAUDE.md (sección 24), anteproyecto (sección 1.3) y estructura de capítulos (sección 1.3). Cada pregunta se corresponde con un objetivo específico.

5. **Objetivo general:** Idéntico en CLAUDE.md (sección 21), anteproyecto (sección 2.1) y estructura de capítulos (sección 1.4.1). Sin variaciones.

6. **Objetivos específicos:** Idénticos en CLAUDE.md (sección 22), anteproyecto (sección 2.2) y estructura de capítulos (sección 1.4.2). Cada objetivo articula directamente con una pregunta de sistematización.

7. **Premisa o idea a defender:** Idéntica en CLAUDE.md (sección 25) y anteproyecto (sección 5). No asume oposición absoluta a la minería privada ni aceptación acrítica de la apertura.

8. **Articulación CDIU con objetivos específicos:** Las 35 filas cubren los cuatro objetivos: OE1 (20 filas), OE2 (7 filas), OE3 (17 filas), OE4 (7 filas). Varias filas apuntan a más de un objetivo, lo que es metodológicamente correcto.

9. **Articulación Matriz de Compatibilidad con objetivos y capítulos:** Señala correctamente que la Tabla principal se usa en Capítulos I y IV, y la Tabla ilustrativa en el Capítulo III. El OE4 articula directamente con la propuesta (criterios 33-35 CDIU). Coherencia confirmada.

10. **No confusión entre minería privada legal y minería ilegal:** La diferenciación está tratada en la fila 13 de la CDIU, el criterio 15 de la Matriz de Compatibilidad, el planteamiento del problema del anteproyecto y la advertencia transversal 1 de la CDIU. Las fuentes que analizan minería ilegal están correctamente clasificadas para la distinción jurídica.

11. **No confusión entre proyecto de ley y ley vigente:** La Ley de Fortalecimiento 2026 está correctamente identificada como ley publicada con Registro Oficial verificado (R.O. Quinto Suplemento No. 234, 2 de marzo de 2026). La noticia institucional de segundo debate es tratada como fuente contextual, no normativa.

12. **Diferenciación de tipos de documentos legislativos:** La nota metodológica de `matriz_reformas_legislativas.md` diferencia con precisión: proyecto de ley, informe de primer debate, informe de segundo debate, texto aprobado, noticia institucional y ley vigente con Registro Oficial.

13. **Enfoque cualitativo, documental y jurídico-crítico:** El anteproyecto (sección 6) describe correctamente los cuatro métodos y los instrumentos. La nota metodológica de la CDIU confirma que la investigación no es estadística ni cuantitativa.

14. **Marco normativo coherente y verificado:** La matriz normativa registra 10 instrumentos con Registro Oficial verificado, articulados jerárquicamente. No se detectan instrumentos inventados ni referencias sin datos de publicación oficial.

15. **Corpus jurisprudencial verificable:** Tres sentencias vinculantes con texto completo (1149-19-JP/21, 32-17-IN/21, 22-18-IN/21) y la Guía CEDEC 2023. El Comunicado CCE agosto 2025 está correctamente clasificado como documento procesal sin valor jurisprudencial vinculante sobre el sector minero.

16. **Fuentes internacionales verificadas:** Acuerdo de Escazú (tratado vinculante), OC-23/17 (opinión consultiva con valor interpretativo autorizado, no vinculante como sentencia contenciosa), CEPAL Ruta Escazú Ecuador 2023 (documento técnico no vinculante). Todos correctamente clasificados.

17. **Fuentes doctrinales con identificación completa:** Las 12 fuentes doctrinales tienen referencia APA 7 completa con DOI o identificación institucional verificable. No se detectan fuentes sin identificación verificable.

18. **Fuentes institucionales con diferenciación de estado:** Plan Nacional 2020-2030 y Política Pública Minera 2019 son documentos oficiales aprobados. Resolución ARCOM-2025-0029-R es resolución vigente. El Borrador Informe TSCM 2026 está identificado como borrador no aprobado. El Informe ARCOM 2024 es documento oficial publicado.

19. **Propuesta del Capítulo IV articulada con el análisis:** La Matriz de Verificación tiene 16 criterios que derivan directamente de normas, jurisprudencia, doctrina y fuentes institucionales verificadas. No hay criterios sin fundamento verificable.

20. **Estructura LaTeX correcta:** Los archivos de capítulos en `05_capitulos/` existen con estructura correcta. `preliminares.tex` tiene contenido correcto de portada con palabras clave coherentes con la investigación.

---

## 4. Lista de cambios sugeridos

| Archivo | Sección | Cambio sugerido | Prioridad |
|---|---|---|---|
| `05_capitulos/preliminares.tex` | Portada, línea del título | Agregar punto al final del título | Antes de compilación |
| `05_capitulos/capitulo_1_problema.tex` | Sección 1.1 | Incluir párrafo sobre el vacío de regulación de la CPLI derivado de la Sentencia 22-18-IN/21 | Antes de redactar Cap. I |
| `05_capitulos/capitulo_1_problema.tex` | Sección 1.9 (CDIU) | Decidir versión de 4 o 9 columnas para la tabla CDIU y crear `tabla_cdiu.tex` acorde | Antes de redactar Cap. I |
| `05_capitulos/capitulo_2_marco_referencial.tex` | Sección 2.1.4 | Declarar explícitamente qué documentos legislativos están disponibles y cuáles están pendientes | Antes de redactar Cap. II |
| `05_capitulos/capitulo_2_marco_referencial.tex` | Sección 2.4.7 | Usar prensa solo para debate público y posiciones de actores; no para afirmar hechos normativos o jurisprudenciales | Antes de redactar Cap. II |
| `05_capitulos/capitulo_3_metodologia.tex` | Sección 3.6 | Declarar el estado de la documentación legislativa disponible y su limitación | Antes de redactar Cap. III |
| `05_capitulos/capitulo_3_metodologia.tex` | Sección 3.8.3 | Advertir que el análisis se centra en la Ley de 2026 publicada en R.O. | Antes de redactar Cap. III |
| `05_capitulos/capitulo_3_metodologia.tex` y `capitulo_4_propuesta.tex` | Toda sección que analice la Ley de 2026 | Incluir advertencia metodológica sobre estado procesal ante la CCE (al menos 11 demandas al 5 de abril de 2026) | Inmediata |
| `05_capitulos/capitulo_4_propuesta.tex` | Sección 4.2.3 | Incluir como lineamiento jurídico la recomendación de expedir ley orgánica que regule la CPLI en el sector minero | Antes de redactar Cap. IV |
| `05_capitulos/conclusiones.tex` | Todo el capítulo | Condicionar afirmaciones sobre la Ley de 2026 a su estado de constitucionalidad; articular cada conclusión con un objetivo específico | Antes de redactar Conclusiones |
| `05_capitulos/recomendaciones.tex` | Todo el capítulo | Dirigir recomendaciones a actores concretos derivadas de hallazgos; no redactar recomendaciones genéricas | Antes de redactar Recomendaciones |
| `06_tablas/tabla_cdiu.tex` | Tabla vacía | Crear tabla completa una vez decidida la estructura de columnas (ver Problema 1) | Antes de compilación |
| `06_tablas/matriz_compatibilidad.tex` | Tabla vacía | Crear tabla completa con 16 criterios; usar `longtable` o `landscape`; incluir nota y análisis posterior | Antes de compilación |
| `06_tablas/matriz_normativa.tex` | Tabla vacía | Crear tabla con los 10 instrumentos normativos; incluir nota y análisis posterior | Antes de compilación |
| `06_tablas/matriz_jurisprudencial.tex` | Tabla vacía | Crear tabla con documentos jurisprudenciales; incluir nota y análisis posterior | Antes de compilación |
| `referencias.bib` | Archivo vacío | Poblar únicamente con fuentes que tienen ficha en `03_fichas/`; no incluir Trujillo Cárdenas (2021) ni otras fuentes del anteproyecto sin ficha | Antes de compilación |

---

## 5. Conclusión

El proyecto no está listo para revisar citas ni compilar en este momento porque ningún capítulo tiene contenido redactado. Sin embargo, el corpus documental, las matrices analíticas y el diseño metodológico están en condiciones de sustentar el inicio inmediato de la redacción del Capítulo I.

Los elementos que deben resolverse **antes de iniciar la redacción del Capítulo I** son: (a) decidir el formato definitivo de la tabla CDIU (Problema 1); (b) planificar la inclusión del vacío de regulación de la CPLI en el planteamiento del problema (Problema 4).

El **problema de mayor urgencia transversal** es el relacionado con el estado procesal de la Ley de Fortalecimiento 2026 ante la Corte Constitucional (Problema 3). Cada capítulo que analice esa ley debe incluir una advertencia metodológica explícita desde la primera versión, no como corrección posterior.

El orden de redacción recomendado en CLAUDE.md sección 29 (Capítulo I → III → II → IV → Conclusiones → Recomendaciones → Introducción) es coherente con la disponibilidad de las matrices. No existe impedimento metodológico para iniciar la redacción con el comando `/project:redactar-capitulo capitulo_1_problema`.

---

## Archivos revisados para elaborar este reporte

- `CLAUDE.md`
- `00_instrucciones/anteproyecto.md`
- `00_instrucciones/estructura_capitulos.md`
- `00_instrucciones/criterios_reformas_legislativas.md`
- `04_matrices/estado_del_proyecto.md`
- `04_matrices/matriz_cdiu.md`
- `04_matrices/matriz_compatibilidad_constitucional_ambiental.md`
- `04_matrices/matriz_normativa.md`
- `04_matrices/matriz_jurisprudencial.md`
- `04_matrices/matriz_reformas_legislativas.md`
- `04_matrices/matriz_doctrina.md`
- `04_matrices/matriz_institucional.md`
- `04_matrices/matriz_internacional.md`
- `04_matrices/matriz_prensa_contextual.md`
- `04_matrices/matriz_fuentes.md`
- `05_capitulos/preliminares.tex`
- `05_capitulos/introduccion.tex`
- `05_capitulos/capitulo_1_problema.tex`
- `05_capitulos/capitulo_2_marco_referencial.tex`
- `05_capitulos/capitulo_3_metodologia.tex`
- `05_capitulos/capitulo_4_propuesta.tex`
- `05_capitulos/conclusiones.tex`
- `05_capitulos/recomendaciones.tex`
- `06_tablas/tabla_cdiu.tex`
- `06_tablas/matriz_compatibilidad.tex`
- `06_tablas/matriz_normativa.tex`
- `06_tablas/matriz_jurisprudencial.tex`
- `07_anexos/anexos.tex`
