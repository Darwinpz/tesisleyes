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

---

---

# Segunda revisión de coherencia metodológica y jurídica

**Fecha:** 24 de junio de 2026
**Agente:** consistency-reviewer
**Contexto:** El Capítulo I está redactado. `referencias.bib` tiene 25 entradas. PDF compilado: 32 páginas con bibliografía generada. 5 correcciones APA aplicadas.

---

## SR-1. Resumen comparativo con la primera revisión

| N.° | Problema (primera revisión) | Estado en esta revisión |
|---|---|---|
| P-1 | Discrepancia esquema CDIU 4 columnas vs. 9 columnas | Resuelto parcialmente: versión de 5 columnas adoptada en `tabla_cdiu.tex` con justificación en el texto del Cap. I. |
| P-2 | Fuente Pillajo (2024) con delimitación provincial | Persistente: no citada en Cap. I. Advertencia vigente para Cap. II. |
| P-3 | Estado procesal Ley 2026 ante la CCE | Resuelto en Cap. I (nota al pie 1). Persistente para Caps. III y IV por redactar. |
| P-4 | Vacío CPLI no señalado en planteamiento del problema | Resuelto: párrafo 5 de la sección 1.1 del Cap. I lo aborda con cita a la Sentencia 22-18-IN/21. |
| P-5 | Expediente legislativo incompleto | Persistente: proyectos AN-2018 y AN-2019 no incorporados. |
| P-6 | Tablas LaTeX vacías | Parcialmente resuelto: `tabla_cdiu.tex` creada y compilando. Las otras cuatro tablas siguen vacías. |
| P-7 | Reportes de citas y compilación vacíos | Resuelto: ambos reportes completados en esta sesión. |
| P-8 | Control de fuentes de prensa | Persistente: ningún capítulo II o III redactado aún. |
| P-9 | Título sin punto final en `preliminares.tex` | Persistente: línea 11 de `preliminares.tex` sigue sin punto al final. |
| P-10 | Cap. III debe declarar limitación documental legislativa | Persistente: Cap. III no redactado. |
| P-11 | Comunicado CCE agosto 2025 ajeno al sector minero | Resuelto: nota al pie 1 del Cap. I advierte explícitamente que el Comunicado se refiere a leyes distintas a la Ley Minera. |
| P-12 | Trujillo Cárdenas (2021) sin ficha incluida en bib | Resuelto: no incluida en `referencias.bib`. Las 25 entradas corresponden a fuentes con ficha verificada. |

---

## SR-2. Verificación de los 15 puntos de esta revisión

**SR-2.1 — Título exacto.** Conforme. El título aparece correctamente en todos los encabezados de matrices y reportes. En `preliminares.tex` línea 11 persiste la ausencia del punto final (P-9).

**SR-2.2 — Alcance nacional sin delimitación territorial.** Conforme. Las secciones 1.1, 1.6 y 1.8 del Cap. I mantienen el alcance nacional de manera explícita. Las referencias jurisprudenciales al Bosque Los Cedros, manglares y río Aquepi están identificadas en la sección 1.6 como "precedentes constitucionales de alcance nacional", no como delimitaciones territoriales.

**SR-2.3 — Coherencia interna del Capítulo I.** Conforme con observación menor (SR-3.4). La coherencia entre planteamiento (1.1), formulación (1.2), sistematización (1.3), objetivo general (1.4.1), objetivos específicos (1.4.2), justificación (1.5), delimitación (1.6), premisa (1.8) y CDIU (1.9) es alta.

**SR-2.4 — Problema, formulación, sistematización, objetivo general y objetivos específicos.** Plenamente conforme. Los textos son textualmente idénticos a los definidos en CLAUDE.md secciones 21-24 y en `00_instrucciones/estructura_capitulos.md`.

**SR-2.5 — Tratamiento de la Ley de Fortalecimiento 2026.** Conforme en Cap. I. La ley está identificada como vigente con R.O. verificado, cita parentética formal y nota al pie 1 con todas las advertencias metodológicas requeridas. Pendiente para Caps. III y IV.

**SR-2.6 — Sentencia 22-18-IN/21 y vacío de la CPLI.** Resuelto satisfactoriamente. El párrafo 5 de la sección 1.1 del Cap. I aborda el vacío de la CPLI con cita formal, identificación de los arts. 462 y 463 declarados inconstitucionales, persistencia del vacío y efectos sobre concesiones en territorios indígenas.

**SR-2.7 — Las 5 correcciones de citación (P-01 a P-05).** Todas verificadas y conformes con APA 7 y CLAUDE.md.

**SR-2.8 — Los 21 comandos `\nocite{}`.** Conforme. Todos tienen correspondencia en `referencias.bib`. No hay claves inexistentes.

**SR-2.9 — Entradas de `referencias.bib`.** Conforme. 25 entradas con ficha verificada. Trujillo Cárdenas (2021) no incluida. Dos advertencias documentadas (sin DOI y sin URL) correctamente registradas en el reporte de citas.

**SR-2.10 — Coherencia entre tabla CDIU LaTeX y matriz CDIU.** Conforme. Las 9 categorías coinciden en nombre y orden. La fila 8 cita correctamente a "Medina Llerena y García Erazo (2026)".

**SR-2.11 — Coherencia entre Matriz de Compatibilidad y Capítulo I.** Conforme. La Matriz de Verificación se presenta en el Cap. I únicamente como instrumento del Cap. IV, sin anticipar sus 16 criterios.

**SR-2.12 — Reporte anterior y resolución progresiva.** Progreso significativo. 5 problemas resueltos totalmente o sustancialmente; 7 permanecen abiertos por razones de secuencia de redacción.

**SR-2.13 — No confusión minería privada legal / minería ilegal en Cap. I.** Conforme. La distinción es explícita en las secciones 1.1, 1.6 y 1.8.

**SR-2.14 — No tratamiento de proyectos de ley como leyes vigentes.** Conforme. La regla 2 de CLAUDE.md se cumple en todos los documentos revisados.

**SR-2.15 — Tono del Capítulo I.** Conforme. El tono es jurídico, académico y crítico. Las afirmaciones sobre efectos jurídicos usan el modo potencial. La premisa argumenta la condición de compatibilidad sin rechazar a priori la inversión privada.

---

## SR-3. Nuevos problemas identificados en esta revisión

### SR-3.1 — Descripción de la Sentencia 32-17-IN/21 potencialmente más amplia que su holding real

- **Gravedad:** media
- **Archivo:** `capitulo_1_problema.tex`, sección 1.1, párrafo 4
- **Descripción:** El texto afirma que la sentencia "estableció el principio de reserva de ley orgánica como límite a las normas reglamentarias que pretendan regular actividades mineras con incidencia en derechos constitucionales." La `matriz_jurisprudencial.md` documenta que la sentencia declaró inconstitucionales los arts. 86 y 136 del Reglamento Ambiental para Actividades Mineras específicamente en materia de autorización de aguas. La formulación del Cap. I puede generalizar el holding más allá de esa materia. Si el alcance del principio es efectivamente general, la formulación es correcta; si se limita a la materia hídrica, requiere precisión.
- **Recomendación:** Al redactar la sección 2.5.8 del Cap. II o en la Fase 5, verificar el texto exacto del holding de la Sentencia 32-17-IN/21 y ajustar si es necesario.
- **Prioridad:** media — verificar en Fase 5

### SR-3.2 — Título sin punto final en `preliminares.tex` (persistencia del Problema 9)

- **Gravedad:** baja
- **Archivo:** `preliminares.tex`, línea 11
- **Descripción:** El título en la portada del PDF compilado aparece sin el punto final que CLAUDE.md sección 1 exige. Todos los encabezados de matrices y reportes incluyen el punto. La inconsistencia es de un solo carácter pero verificable.
- **Recomendación:** Agregar el punto final al título en la línea 11 de `preliminares.tex` antes de la compilación final.
- **Prioridad:** baja — antes de compilación final

### SR-3.3 — Citas del Cap. I en texto plano, riesgo de perpetuarse en los capítulos siguientes

- **Gravedad:** media
- **Archivo:** `capitulo_1_problema.tex`, todas las secciones
- **Descripción:** Todas las citas están escritas como texto hardcoded. Los 21 comandos `\nocite{}` son una medida transitoria para compilar la bibliografía. El riesgo es que al redactar los capítulos siguientes se replique este patrón, generando un manuscrito completo en modo transitorio que deba corregirse íntegramente en la Fase 5.
- **Recomendación:** Redactar los Caps. III, II y IV directamente con `\parencite{}` y `\textcite{}` desde la primera versión. Convertir las citas del Cap. I a `\parencite{}` al inicio de la Fase 5.
- **Prioridad:** alta — establecer el patrón correcto antes de redactar los capítulos siguientes

### SR-3.4 — Formulación "35 dimensiones" puede confundirse con "35 filas"

- **Gravedad:** baja
- **Archivo:** `capitulo_1_problema.tex`, sección 1.9
- **Descripción:** El texto dice "35 dimensiones desarrolladas" cuando la `matriz_cdiu.md` tiene 35 filas. La formulación puede generar confusión entre categorías y dimensiones.
- **Recomendación:** En la Fase 5, ajustar la frase a "35 dimensiones de análisis distribuidas en las nueve categorías antes enunciadas."
- **Prioridad:** baja — corrección de precisión terminológica en Fase 5

### SR-3.5 — `reporte_compilacion_latex.md` sección 1 muestra 29 páginas, no 32

- **Gravedad:** baja
- **Archivo:** `04_matrices/reporte_compilacion_latex.md`, sección 1
- **Descripción:** La sección 1 del reporte de compilación refleja la tercera compilación (29 páginas) pero no fue actualizada tras la cuarta compilación (32 páginas con bibliografía). El historial de compilaciones y el `estado_del_proyecto.md` registran correctamente 32 páginas.
- **Recomendación:** Actualizar la sección 1 del reporte para reflejar la cuarta compilación.
- **Prioridad:** baja — corrección documental

---

## SR-4. Problemas resueltos desde el primer reporte — confirmación formal

| Problema | Forma de resolución | Verificado en |
|---|---|---|
| P-4 (CPLI no señalada) | Párrafo 5 de la sección 1.1 del Cap. I con cita a Sentencia 22-18-IN/21 | `capitulo_1_problema.tex` |
| P-7 (reportes vacíos) | Ambos reportes completados | `reporte_revision_citas.md`; `reporte_compilacion_latex.md` |
| P-11 (Comunicado CCE mal usado) | Nota al pie 1 del Cap. I aclara que el Comunicado es ajeno al sector minero | `capitulo_1_problema.tex` |
| P-12 (Trujillo Cárdenas sin ficha) | No incluida en `referencias.bib` | `referencias.bib` |
| P-1 parcial (columnas CDIU) | Versión de 5 columnas adoptada con justificación en texto del Cap. I | `capitulo_1_problema.tex`; `tabla_cdiu.tex` |
| P-3 parcial (estado Ley 2026) | Advertencia implementada en nota al pie 1 del Cap. I | `capitulo_1_problema.tex` |
| P-6 parcial (tablas vacías) | `tabla_cdiu.tex` creada, compilando sin errores fatales | `tabla_cdiu.tex`; `reporte_compilacion_latex.md` |

---

## SR-5. Aspectos con coherencia confirmada (adicionales a los 20 del primer reporte)

21. El Capítulo I no reformula ni abrevia el título de la tesis en ninguna sección.
22. La formulación del problema en la sección 1.2 del Cap. I es textualmente idéntica a la de CLAUDE.md sección 23.
23. Las cuatro preguntas de sistematización en la sección 1.3 son textualmente idénticas a las de CLAUDE.md sección 24.
24. El objetivo general y los cuatro objetivos específicos del Cap. I son textualmente idénticos a los de CLAUDE.md secciones 21 y 22.
25. La premisa de la sección 1.8 es textualmente idéntica a la de CLAUDE.md sección 25.
26. La advertencia sobre la Ley 2026 en la nota al pie 1 diferencia correctamente vigencia formal de constitucionalidad formal y no prejudica el resultado de los procesos constitucionales en curso.
27. El vacío normativo de la CPLI está identificado como problema jurídico específico en el planteamiento del problema con cita exacta a la Sentencia 22-18-IN/21.
28. Ninguna de las 25 fuentes en `referencias.bib` ni ninguna cita del Cap. I corresponde a fuente inventada, según confirma el `reporte_revision_citas.md`.
29. Las 9 filas de `tabla_cdiu.tex` son coherentes con la `matriz_cdiu.md` en su versión simplificada.
30. La Matriz de Verificación de Compatibilidad Constitucional y Ambiental es presentada en el Cap. I únicamente como instrumento del Cap. IV, sin anticipar sus criterios detallados.

---

## SR-6. Lista de cambios sugeridos pendientes (actualizada)

| Prioridad | Archivo | Cambio | Estado |
|---|---|---|---|
| Alta | Caps. III, II, IV | Redactar con `\parencite{}` y `\textcite{}` desde la primera versión (no replicar modo transitorio de Cap. I) | Pendiente — durante redacción Fase 4 |
| Alta | `capitulo_3_metodologia.tex` | Redactar con advertencia Ley 2026 y declaración de limitación documental legislativa | Pendiente — Fase 4 |
| Alta | `capitulo_2_marco_referencial.tex` | Redactar con control de prensa y advertencia sobre expediente legislativo incompleto | Pendiente — Fase 4 |
| Alta | `capitulo_4_propuesta.tex` | Redactar con Matriz de Verificación, lineamiento CPLI y advertencia Ley 2026 | Pendiente — Fase 4 |
| Media | `capitulo_1_problema.tex` | Convertir citas texto plano a `\parencite{}` y `\textcite{}` | Pendiente — Fase 5 |
| Media | `capitulo_1_problema.tex`, sec. 1.1 par. 4 | Verificar alcance exacto del holding de la Sentencia 32-17-IN/21 (SR-3.1) | Pendiente — Fase 5 |
| Media | `reporte_compilacion_latex.md`, sec. 1 | Actualizar número de páginas de 29 a 32 (SR-3.5) | Pendiente — corrección documental |
| Baja | `preliminares.tex`, línea 11 | Agregar punto final al título (P-9 y SR-3.2) | Pendiente — antes de compilación final |
| Baja | `capitulo_1_problema.tex`, sección 1.9 | Ajustar "35 dimensiones" a "35 dimensiones de análisis distribuidas en las nueve categorías" (SR-3.4) | Pendiente — Fase 5 |
| Baja | `06_tablas/matriz_compatibilidad.tex` | Crear tabla LaTeX al redactar Cap. IV | Pendiente — Fase 4 |
| Baja | `06_tablas/matriz_normativa.tex` y `matriz_jurisprudencial.tex` | Crear tablas LaTeX al redactar Cap. II | Pendiente — Fase 4 |

---

## SR-7. Conclusión

**La tesis está lista para avanzar a la redacción del Capítulo III.**

El Capítulo I está redactado con coherencia interna alta: no contiene las confusiones prohibidas por CLAUDE.md, mantiene alcance nacional declarado, reproduce textualmente el problema, la formulación, la sistematización, los objetivos y la premisa, e incorpora las advertencias metodológicas obligatorias sobre la Ley de Fortalecimiento 2026 y el vacío de la CPLI.

Las matrices que sustentan el Capítulo III están completas: `matriz_cdiu.md` (35 dimensiones, 9 categorías), `matriz_normativa.md` (10 instrumentos), `matriz_jurisprudencial.md` (3 sentencias vinculantes), `matriz_reformas_legislativas.md`, `matriz_institucional.md` (5 documentos), `matriz_internacional.md` (3 fuentes) y `matriz_prensa_contextual.md` (16 fuentes). El `referencias.bib` está poblado con 25 entradas verificadas.

El problema más urgente para los capítulos siguientes es SR-3.3: redactar directamente con `\parencite{}` y `\textcite{}`, sin replicar el modo transitorio del Cap. I.

**Próximo comando recomendado:** `/project:redactar-capitulo capitulo_3_metodologia`

---

## Archivos revisados para elaborar el segundo reporte

- `CLAUDE.md`
- `00_instrucciones/anteproyecto.md`
- `00_instrucciones/estructura_capitulos.md`
- `04_matrices/estado_del_proyecto.md`
- `04_matrices/reporte_revision_citas.md`
- `04_matrices/reporte_compilacion_latex.md`
- `04_matrices/matriz_cdiu.md`
- `04_matrices/matriz_compatibilidad_constitucional_ambiental.md`
- `04_matrices/matriz_normativa.md`
- `05_capitulos/preliminares.tex`
- `05_capitulos/capitulo_1_problema.tex`
- `05_capitulos/capitulo_2_marco_referencial.tex`
- `05_capitulos/capitulo_3_metodologia.tex`
- `05_capitulos/capitulo_4_propuesta.tex`
- `05_capitulos/conclusiones.tex`
- `05_capitulos/recomendaciones.tex`
- `06_tablas/tabla_cdiu.tex`

---

---

# Tercera revisión de coherencia metodológica y jurídica
## Tesis: "Análisis de derecho ambiental ecuatoriano: Revisión crítica de proyectos de ley de apertura al sector minero privado."

**Fecha:** 24 de junio de 2026
**Agente:** consistency-reviewer
**Contexto:** Capítulos I (209 líneas) y III (251 líneas) redactados. `referencias.bib` con 25 entradas. PDF compilado: 54 páginas. `tabla_cdiu.tex` (93 líneas) y `tabla_analisis_documental.tex` (107 líneas) creadas y compilando. Capítulos II, IV, Conclusiones, Recomendaciones e Introducción: esqueletos vacíos. Segunda revisión de citas completada (2 correcciones aplicadas). Próximo paso: redacción del Capítulo II.

---

## TR-0. Resumen comparativo de las tres revisiones

| Problema | Revisión 1 | Revisión 2 | Revisión 3 |
|---|---|---|---|
| P-1: Discrepancia columnas CDIU | Identificado | Resuelto parcialmente | ✅ Resuelto: `tabla_cdiu.tex` usa versión de 5 columnas con justificación en Cap. I |
| P-2: Pillajo (2024) delimitación provincial | Identificado | Persistente | ⚠️ Persistente — advertencia vigente para Cap. II |
| P-3: Estado procesal Ley 2026 ante CCE | Identificado | Resuelto en Cap. I; pendiente Caps. III y IV | ✅ Resuelto en Caps. I y III. Pendiente en Caps. IV, Conclusiones, Recomendaciones |
| P-4: Vacío CPLI en planteamiento | Identificado | Resuelto en Cap. I | ✅ Confirmado resuelto en Cap. I sec. 1.1 y Cap. III sec. 3.7 pregunta 3 |
| P-5: Expediente legislativo incompleto | Identificado | Persistente | ⚠️ Persistente — declaración explícita en secciones 3.5.6, 3.6 y 3.8.3 del Cap. III. Limitación gestionada |
| P-6: Tablas LaTeX vacías | Identificado | Parcialmente resuelto | ⚠️ Parcialmente resuelto: `tabla_cdiu.tex` y `tabla_analisis_documental.tex` creadas. Pendientes: `matriz_compatibilidad.tex`, `matriz_normativa.tex`, `matriz_jurisprudencial.tex` |
| P-7: Reportes vacíos | Identificado | Resuelto | ✅ Confirmado resuelto |
| P-8: Control fuentes de prensa | Identificado | Persistente | ⚠️ Parcialmente resuelto en Cap. III sec. 3.8.4. Pendiente en Cap. II |
| P-9: Título sin punto final en `preliminares.tex` | Identificado | Persistente | ⚠️ Persistente — corregir antes de compilación final |
| P-10: Cap. III debe declarar limitación legislativa | Identificado | Persistente | ✅ Resuelto — secciones 3.5.6, 3.6 y 3.8.3 lo declaran explícitamente |
| P-11: Comunicado CCE mal usado | Identificado | Resuelto en Cap. I | ✅ Confirmado resuelto en Cap. I nota al pie 1 y Cap. III sec. 3.4.3 |
| P-12: Trujillo Cárdenas (2021) sin ficha | Identificado | Resuelto | ✅ Confirmado resuelto |
| SR-3.1: Holding Sent. 32-17-IN/21 potencialmente ampliado | Nuevo en R2 | Identificado | ⚠️ Persistente — Cap. III reitera la formulación ampliada del Cap. I. Verificar en Fase 5 |
| SR-3.3: Citas Cap. I en texto plano | Nuevo en R2 | Identificado | ✅ Resuelto en Cap. III: usa `\parencite{}` y `\textcite{}` consistentemente. Convertir Cap. I en Fase 5 |
| SR-3.4: "35 dimensiones" vs. "35 filas" en Cap. I | Nuevo en R2 | Identificado | ⚠️ Persistente — corrección diferida a Fase 5 |
| SR-3.5: Reporte compilación desactualizado | Nuevo en R2 | Identificado | ✅ Resuelto — reporte compilación actualizado a 54 páginas (sexta verificación) |

---

## TR-1. Estado de los problemas anteriores confirmado en esta revisión

### TR-1.1 — Patrón de citación en Cap. III: resuelto satisfactoriamente

El Capítulo III usa `\parencite{}` y `\textcite{}` de manera consistente en todas sus secciones. No existe mezcla de texto hardcoded con comandos BibTeX. Las 22 claves BibTeX utilizadas son consistentes con `referencias.bib`. Problema SR-3.3 resuelto en Cap. III.

### TR-1.2 — Advertencia Ley 2026 en Cap. III: resuelto satisfactoriamente

La sección 3.8.3 contiene advertencia metodológica completa. Diferencia correctamente vigencia formal (R.O. 234-5S) y cuestionamiento constitucional activo (11+ demandas al 5-abr-2026). No prejuzga el resultado de los procesos. Problema P-3 resuelto en Cap. III.

### TR-1.3 — Limitación documental legislativa en Cap. III: resuelto satisfactoriamente

Las secciones 3.5.6 y 3.8.3 del Cap. III declaran explícitamente la limitación. La sección 3.6 documenta la restricción en el análisis posterior de la Tabla 2. Problema P-10 resuelto.

### TR-1.4 — Declaración de inaplicación de entrevistas: coherente

La sección 3.8.5 del Cap. III declara que las entrevistas no han sido aplicadas, describe las condiciones de su eventual aplicación y establece que su ausencia no compromete la validez del diseño. Metodológicamente sólido conforme a `estructura_capitulos.md`.

---

## TR-2. Nuevos problemas identificados en la tercera revisión

### TR-2.1 — "Veinticuatro entradas" en sec. 3.6 no aclara que la fila 23 agrupa 16 fuentes

- **Gravedad:** baja
- **Archivo:** `05_capitulos/capitulo_3_metodologia.tex`, sección 3.6
- **Descripción:** El texto describe "veinticuatro entradas" pero la fila 23 agrupa las 16 fuentes de prensa como un bloque. El corpus total del repositorio es 53. Un lector externo podría subestimar el corpus real.
- **Recomendación (Fase 5):** Aclarar: "La Tabla 2 presenta veinticuatro entradas que representan el corpus verificado. La fila 23 agrupa las dieciséis fuentes de prensa contextual como un bloque temático. El corpus total del repositorio comprende cincuenta y tres fuentes individuales."
- **Prioridad:** baja — corrección de precisión en Fase 5

### TR-2.2 — Sentencia 22-18-IN/21: presentar los tres holdings al redactar Cap. II

- **Gravedad:** media
- **Archivo:** `05_capitulos/capitulo_3_metodologia.tex`, sección 3.4.3 (referencia); por anticipación: `05_capitulos/capitulo_2_marco_referencial.tex`, secciones 2.1.5 y 2.5.8
- **Descripción:** La sección 3.4.3 del Cap. III describe la Sentencia 22-18-IN/21 exclusivamente desde la dimensión de CPLI e inconstitucionalidad de arts. 462–463 RCOAM. La sentencia también desarrolla derechos de la naturaleza en ecosistemas de manglares y condiciona la constitucionalidad del art. 184 COAM.
- **Recomendación:** Al redactar las secciones 2.1.5 y 2.5.8 del Cap. II, presentar la Sentencia 22-18-IN/21 con sus tres holdings: (a) derechos de la naturaleza en ecosistemas de manglares; (b) distinción entre consulta ambiental (art. 398 CRE) y CPLI (art. 57.7 CRE); (c) inconstitucionalidad de los arts. 462 y 463 RCOAM.
- **Prioridad:** media — antes de redactar el Cap. II

### TR-2.3 — "Seis documentos" en sec. 3.5.3 no coincide con la enumeración de cinco

- **Gravedad:** media
- **Archivo:** `05_capitulos/capitulo_3_metodologia.tex`, sección 3.5.3
- **Descripción:** La sección indica "seis documentos jurisprudenciales" pero la enumeración detalla exactamente cinco: las tres sentencias vinculantes, la Guía CEDEC 2023 y el Comunicado CCE agosto 2025. El archivo `cce_consulta_ambiental.md` es un análisis complementario de la Sentencia 1149-19-JP/21, no una sentencia autónoma. La Tabla 2 registra solo cuatro entradas jurisprudenciales (filas 9–12).
- **Recomendación (Fase 5):** Ajustar la sección 3.5.3 para indicar "cinco documentos jurisprudenciales". Verificar si el Comunicado debe aparecer como fila en la Tabla 2.
- **Prioridad:** media — corrección de consistencia en Fase 5; recordar al redactar Cap. II

### TR-2.4 — Entrevistas no aplicadas: verificar coherencia con Conclusiones y Recomendaciones

- **Gravedad:** baja
- **Archivo:** `05_capitulos/capitulo_3_metodologia.tex`, secciones 3.4.4 y 3.8.5
- **Descripción:** La sección 3.8.5 declara que las entrevistas no han sido aplicadas. Si tampoco se aplican antes de redactar Conclusiones y Recomendaciones, esas secciones no deben referenciar resultados de entrevistas.
- **Recomendación:** Al redactar Conclusiones y Recomendaciones, verificar que no se citen resultados de entrevistas si estas no fueron aplicadas.
- **Prioridad:** baja — vigilar al redactar Conclusiones y Recomendaciones

### TR-2.5 — Referencia a "criterio 17" en Matriz de Compatibilidad (solo existen 16 criterios)

- **Gravedad:** media
- **Archivo:** `04_matrices/matriz_compatibilidad_constitucional_ambiental.md`, sección "Fuentes que sustentan la Matriz"
- **Descripción:** La entrada de fuentes internacionales indica "OC-23/17 Corte IDH (criterios 2, 10, 17)." La Matriz tiene solo 16 criterios. El "criterio 17" no existe; probable error tipográfico por "16".
- **Recomendación:** Corregir antes de redactar el Cap. IV: cambiar "criterios 2, 10, 17" por "criterios 2, 10, 16" y verificar que la OC-23/17 efectivamente sustenta el criterio 16.
- **Prioridad:** media — corregir en `matriz_compatibilidad_constitucional_ambiental.md` antes del Cap. IV

### TR-2.6 — Vacío doctrinal en secciones 2.2.17 y 2.2.18 del Cap. II (técnica legislativa)

- **Gravedad:** media
- **Archivo:** `00_instrucciones/estructura_capitulos.md`, secciones 2.2.17 y 2.2.18; `04_matrices/matriz_doctrina.md`
- **Descripción:** La estructura prevé secciones sobre técnica legislativa y análisis de impacto legislativo ambiental. La `matriz_doctrina.md` (12 fuentes) no contiene ninguna fuente que trate específicamente estas materias.
- **Recomendación:** Antes de redactar esas secciones, tomar una decisión: (a) buscar fuente doctrinal verificable con `/project:buscar-fuente tecnica legislativa ambiental Ecuador`; (b) redefinir el alcance de esas secciones sustentándolas con jurisprudencia constitucional vinculante (las tres sentencias establecen criterios de evaluación legislativa) y normativa (arts. 11.8, 82, 395–399 CRE; art. 161 COA). La opción (b) es metodológicamente sólida sin fuentes adicionales.
- **Prioridad:** media — decisión previa antes de redactar el Cap. II

### TR-2.7 — Nombre incorrecto del archivo `reforma_reglamento_general_ley_mineria_2025.md`

- **Gravedad:** baja
- **Archivo:** `02_fuentes_md/normativa/reforma_reglamento_general_ley_mineria_2025.md`; `04_matrices/matriz_normativa.md`, observación N.7
- **Descripción:** El archivo contiene el texto actualizado de la Ley de Minería con reformas hasta agosto de 2025, no una reforma al Reglamento General. Esta discrepancia puede generar confusión al redactar el Cap. II.
- **Recomendación:** Al redactar el Cap. II, identificar el archivo correctamente y usar la clave BibTeX `ley_mineria_2025`.
- **Prioridad:** baja — recordar al citar en Cap. II

---

## TR-3. Aspectos confirmados como coherentes en la tercera revisión (ítems 31–40)

Los ítems 1–30 fueron confirmados en las revisiones anteriores y se mantienen. Se agregan:

31. El Capítulo III no reformula ni abrevia el título de la tesis en ninguna sección.
32. El Capítulo III identifica correctamente la Ley de Fortalecimiento 2026 como ley vigente con R.O. verificado, nunca como proyecto de ley.
33. Las 6 preguntas de entrevista (sección 3.7) están articuladas directamente con los cuatro objetivos específicos y la premisa de la investigación.
34. La Tabla 2 (sección 3.6) diferencia correctamente entre fuentes normativas, jurisprudenciales, internacionales, institucionales, doctrinales, de prensa y legislativas contextuales.
35. El Cap. III declara explícitamente la limitación documental legislativa en tres secciones distintas (3.5.6, 3.6 y 3.8.3), sin que esta limitación invalide el diseño metodológico.
36. La sección 3.8.2 sintetiza correctamente los hallazgos del análisis normativo y jurisprudencial, orientando el análisis comparativo del Cap. IV.
37. El Capítulo III mantiene tono académico, jurídico y crítico, sin afirmaciones absolutas, lenguaje político ni conclusiones no demostradas. Cumple íntegramente `criterios_redaccion.md`.
38. La fila 24 de la Tabla 2 no otorga valor jurídico autónomo a la noticia institucional de la Asamblea Nacional. La nota al pie aclara su carácter contextual.
39. El Capítulo III no introduce fuentes nuevas que no estén en el repositorio. Todas las claves `\parencite{}` corresponden a entradas verificadas de `referencias.bib`.
40. La coherencia entre la CDIU (Cap. I, sec. 1.9), la Tabla 2 (Cap. III, sec. 3.6) y la Matriz de Compatibilidad es alta: los tres instrumentos cubren las mismas categorías jurídicas con niveles de detalle distintos y sin contradicciones sustantivas.

---

## TR-4. Lista consolidada de problemas pendientes al cierre de la tercera revisión

| Identificador | Problema | Prioridad | Estado |
|---|---|---|---|
| P-2 | Fuente Pillajo (2024) con delimitación provincial | Media | ⚠️ Persistente — advertencia vigente para Cap. II |
| P-3 | Ley 2026: advertencia CCE pendiente en Cap. IV, Conclusiones, Recomendaciones | Alta | ⚠️ Pendiente en capítulos aún no redactados |
| P-5 | Expediente legislativo incompleto | Media | ⚠️ Persistente — declaración en Cap. III; gestionar en Cap. II sec. 2.1.4 |
| P-6 | Tablas LaTeX pendientes | Baja | ⚠️ Crear al redactar Caps. II y IV |
| P-8 | Control fuentes de prensa en Cap. II | Media | ⚠️ Persistente — gestionar al redactar Cap. II |
| P-9 / SR-3.2 | Punto final ausente en título en `preliminares.tex` | Baja | ⚠️ Persistente — corrección antes de compilación final |
| SR-3.1 | Alcance del holding de la Sentencia 32-17-IN/21 | Media | ⚠️ Persistente — verificar en Fase 5 |
| SR-3.4 | "35 dimensiones" vs. "35 filas" en Cap. I | Baja | ⚠️ Persistente — corrección en Fase 5 |
| TR-2.1 | Aclaración de "veinticuatro entradas" en sec. 3.6 | Baja | Nuevo en R3 — corrección en Fase 5 |
| TR-2.2 | Sentencia 22-18-IN/21: presentar tres holdings al redactar Cap. II | Media | Nuevo en R3 — considerar al redactar Cap. II |
| TR-2.3 | Inconsistencia "seis documentos" vs. cinco en sec. 3.5.3 | Media | Nuevo en R3 — corrección en Fase 5 |
| TR-2.4 | Entrevistas: verificar coherencia con Conclusiones y Recomendaciones | Baja | Nuevo en R3 — vigilar al redactar Conclusiones |
| TR-2.5 | "Criterio 17" inexistente en Matriz de Compatibilidad | Media | Nuevo en R3 — corregir antes del Cap. IV |
| TR-2.6 | Vacío doctrinal en secciones 2.2.17 y 2.2.18 del Cap. II | Media | Nuevo en R3 — decisión previa antes de redactar Cap. II |
| TR-2.7 | Nombre incorrecto archivo `reforma_reglamento_general_ley_mineria_2025.md` | Baja | Nuevo en R3 — recordar al citar en Cap. II |

---

## TR-5. Observaciones preventivas para la redacción del Capítulo II

1. **Sección 2.1.4** (antecedentes legislativos): declarar explícitamente que el análisis se basa en la ley publicada (R.O. 234-5S) y en la noticia institucional disponible. No inventar el contenido del expediente legislativo.
2. **Sección 2.1.5** (antecedentes jurisprudenciales): presentar la Sentencia 22-18-IN/21 con sus tres holdings (TR-2.2).
3. **Sección 2.2.8** (clasificación jurídica de la minería): diferenciar con rigor entre minería artesanal, pequeña minería, mediana minería, minería a gran escala, minería legal, minería informal y minería ilegal.
4. **Secciones 2.2.17 y 2.2.18** (técnica legislativa): tomar decisión previa sobre fuentes de respaldo (TR-2.6).
5. **Sección 2.4.5** (diferenciación legal / ilegal): apoyarse en COIP (arts. 260-261), Ley de Minería e Informe ARCOM 2024. No usar prensa para afirmar categorías jurídicas.
6. **Sección 2.4.7** (contexto mediático): usar exclusivamente las 16 fuentes de prensa del repositorio.
7. **Sección 2.5.5** (reformas vigentes): si no se han incorporado proyectos de ley adicionales, declarar la limitación explícitamente.
8. **Citación**: redactar íntegra y exclusivamente con `\parencite{}` y `\textcite{}`. No usar texto plano ni `\nocite{}`.
9. **Tablas del Cap. II**: crear simultáneamente `06_tablas/matriz_normativa.tex` y `06_tablas/matriz_jurisprudencial.tex` con número, título, nota y análisis posterior.
10. **Fuentes opcionales**: evaluar antes de cerrar el Cap. II si incorporar Koehn (2022) y Sentencia CCE 1185-20-JP/21 (río Aquepi) mediante el flujo completo del proyecto.

---

## TR-6. Conclusión de la tercera revisión

**La tesis está lista para avanzar a la redacción del Capítulo II.**

Los Capítulos I y III están redactados con coherencia interna alta. El Capítulo III resolvió el problema más urgente de la segunda revisión (SR-3.3): usa `\parencite{}` y `\textcite{}` de manera consistente en toda su extensión. Las advertencias metodológicas sobre la Ley de Fortalecimiento 2026 están implementadas en ambos capítulos redactados. Las limitaciones documentales están declaradas explícitamente en tres secciones distintas del Cap. III.

Los siete nuevos problemas (TR-2.1 a TR-2.7) son de gravedad baja o media. Cuatro son correcciones de precisión diferibles a la Fase 5. El problema de mayor impacto inmediato para el Cap. II es TR-2.6 (vacío doctrinal en secciones 2.2.17 y 2.2.18). El problema que requiere corrección antes del Cap. IV es TR-2.5 (referencia a "criterio 17" inexistente en la Matriz de Compatibilidad).

**Próximo comando recomendado:** `/redactar-capitulo capitulo_2_marco_referencial`

---

---

## Cuarta revisión de coherencia (4a. revisión — 24 de junio de 2026)

**Agente:** consistency-reviewer
**Contexto:** Capítulos I (211 líneas) y III (251 líneas) redactados y compilados. PDF: 54 páginas. Manual de Técnica Legislativa incorporado como fuente N° 54. TR-2.5 corregido. Segunda revisión de citas completada. Corpus: 54 fuentes, 54 fichas. Próximo paso: redacción del Capítulo II.

---

### TR4-0. Tabla de comparación con revisiones anteriores

| Identificador | Problema | Estado en esta revisión |
|---|---|---|
| P-1: Discrepancia columnas CDIU | Resuelto en R2: versión de 5 columnas adoptada en `tabla_cdiu.tex` | Confirmado resuelto |
| P-2: Pillajo (2024) delimitación provincial | Persistente — advertencia vigente para Cap. II | Persiste — sin cambio |
| P-3: Advertencia Ley 2026 ante CCE | Resuelto en Caps. I y III. Pendiente en Caps. IV, Conclusiones, Recomendaciones | Persiste — pendiente en capítulos no redactados |
| P-4: Vacío CPLI en planteamiento del problema | Resuelto en Cap. I sec. 1.1 | Confirmado resuelto |
| P-5: Expediente legislativo incompleto | Declaración explícita en secs. 3.5.6, 3.6 y 3.8.3 del Cap. III. Gestionado | Persiste — sin cambio en la limitación documental |
| P-6: Tablas LaTeX pendientes | `tabla_cdiu.tex` y `tabla_analisis_documental.tex` creadas. Tres tablas siguen vacías | Persiste parcialmente — sin cambio desde R3 |
| P-7: Reportes vacíos | Resuelto en R2 | Confirmado resuelto |
| P-8: Control fuentes de prensa en Cap. II | Pendiente — Cap. II no redactado | Persiste — sin cambio |
| P-9 / SR-3.2: Título sin punto final en `preliminares.tex` | Persistente — corregir antes de compilación final | Persiste — sin cambio |
| P-10: Cap. III declarar limitación legislativa | Resuelto en R3 | Confirmado resuelto |
| P-11: Comunicado CCE mal usado | Resuelto en Cap. I y Cap. III | Confirmado resuelto — ver alerta residual en TR4-4 |
| P-12: Trujillo Cárdenas (2021) sin ficha | Resuelto — no incluida en `referencias.bib` | Confirmado resuelto |
| SR-3.1: Alcance holding Sent. 32-17-IN/21 | Persiste — verificar en Fase 5 | Persiste — sin cambio |
| SR-3.3: Citas Cap. I en texto plano | Resuelto en Cap. III con `\parencite{}` y `\textcite{}` | Confirmado resuelto en Cap. III; conversión de Cap. I diferida a Fase 5 |
| SR-3.4: "35 dimensiones" vs. "35 filas" | Persiste — corrección diferida a Fase 5 | Persiste — sin cambio |
| SR-3.5: Reporte compilación desactualizado | Resuelto en R3 | Confirmado resuelto |
| TR-2.1: "Veinticuatro entradas" en sec. 3.6 | Pendiente — corrección en Fase 5 | Persiste — análisis detallado en TR4-2 |
| TR-2.2: Sentencia 22-18-IN/21 tres holdings en Cap. II | Pendiente — implementar al redactar Cap. II | Persiste — sin cambio |
| TR-2.3: "Seis documentos" vs. cinco en sec. 3.5.3 | Pendiente — corrección en Fase 5 | Persiste — análisis detallado en TR4-3 |
| TR-2.4: Entrevistas: coherencia con Conclusiones | Pendiente — vigilar al redactar Conclusiones | Persiste — sin cambio |
| TR-2.5: "Criterio 17" inexistente en Matriz de Compatibilidad | ✅ Corregido: cambiado a "criterios 2, 10, 16" | Confirmado resuelto |
| TR-2.6: Vacío doctrinal en secs. 2.2.17 y 2.2.18 | ✅ Resuelto: Manual de Técnica Legislativa incorporado como fuente N° 54 | Confirmado resuelto. Análisis de coherencia de la incorporación en TR4-1 |
| TR-2.7: Nombre incorrecto del archivo `reforma_reglamento_general_ley_mineria_2025.md` | Pendiente — recordar al citar en Cap. II | Persiste — sin cambio |

---

### TR4-1. Coherencia entre el Manual de Técnica Legislativa y las secciones 2.2.17 y 2.2.18 del Cap. II

**Tipo:** Coherencia estructural / preventivo
**Gravedad:** Media
**Archivo afectado:** `04_matrices/matriz_institucional.md`; `00_instrucciones/estructura_capitulos.md` secs. 2.2.17 y 2.2.18; `05_capitulos/capitulo_2_marco_referencial.tex` (aún no redactado)
**Descripción:**

El Manual de Técnica Legislativa (AN-UTL, ISBN: 978-9942-07-716-5) fue incorporado para respaldar las secciones 2.2.17 y 2.2.18 del Cap. II. Su contenido es coherente con el alcance de esas secciones: el cuestionario de impacto normativo (nota al pie 2, pp. 31-32) exige evaluar impactos ambientales y sociales; el control constitucional material del art. 84 CRE; la reserva de ley (art. 132 CRE); la unidad de materia (art. 136 CRE); y el Informe No Vinculante de la UTL (art. 56 LOFL). No existe riesgo de expansión temática fuera del alcance de la tesis.

Sin embargo, subsisten tres riesgos para la redacción del Cap. II:

**Riesgo 1.** El año exacto de publicación del Manual no fue identificado en el documento. La `matriz_institucional.md` lo registra como "Dato no identificado en el documento (período referencial: 2014-2017)". La entrada en `referencias.bib` deberá usar "s.f." o el período referencial entre corchetes con nota aclaratoria. No inventar año.

**Riesgo 2.** Las citas textuales del Manual deben verificarse por página en el archivo `02_fuentes_md/institucional/manual_de_tecnica_legislativa.md` antes de incluirlas en el texto. En particular, la nota al pie 2, pp. 31-32, debe verificarse antes de citarse textualmente.

**Riesgo 3.** El Manual es guía institucional de referencia, no norma jurídica vinculante. La proposición jurídica central de las secciones 2.2.17 y 2.2.18 debe sustentarse en el art. 84 CRE y la jurisprudencia constitucional; el Manual puede invocarse como evidencia institucional complementaria, no como fuente normativa autónoma.

**Recomendación:** Al redactar secs. 2.2.17 y 2.2.18, verificar nota al pie 2 pp. 31-32 en el archivo `.md` antes de citar. Construir la cita BibTeX con "s.f." o período inferido con advertencia. Formular la proposición jurídica central desde el art. 84 CRE y la jurisprudencia; usar el Manual como evidencia complementaria.
**Prioridad:** Al redactar el Cap. II.

---

### TR4-2. Impacto de la fuente N° 54 sobre los conteos del Cap. III (problema TR-2.1 ampliado)

**Tipo:** Coherencia metodológica
**Gravedad:** Baja
**Archivo afectado:** `05_capitulos/capitulo_3_metodologia.tex`, secciones 3.6 y 3.8.1
**Descripción:**

La sec. 3.8.1 del Cap. III indica "la revisión bibliográfica abarca cincuenta y tres fuentes". Con la incorporación del Manual de Técnica Legislativa como fuente N° 54, el corpus real es ahora 54 fuentes. El texto del Cap. III no fue modificado. La `tabla_analisis_documental.tex` tiene 24 filas; la fila de fuentes institucionales (fila 18 aproximadamente) agrupa la categoría, pero el repositorio tiene 6 fuentes institucionales. La tabla no es incorrecta metodológicamente, pero la explicación del texto posterior debe ser precisa.

**Recomendación:** En la Fase 5, actualizar la referencia "cincuenta y tres fuentes" a "cincuenta y cuatro fuentes" en la sec. 3.8.1. Ajustar la descripción de la categoría institucional si la tabla se edita para incorporar el Manual como entrada adicional.
**Prioridad:** Fase 5 — corrección de precisión numérica.

---

### TR4-3. Persistencia del problema TR-2.3: "seis documentos" vs. cinco en sec. 3.5.3 del Cap. III

**Tipo:** Coherencia metodológica
**Gravedad:** Media
**Archivo afectado:** `05_capitulos/capitulo_3_metodologia.tex`, secciones 3.5.3 y 3.5.1
**Descripción:**

La sec. 3.5.3 del Cap. III indica "seis documentos jurisprudenciales" pero solo enumera cinco: las tres sentencias vinculantes, la Guía CEDEC 2023 y el Comunicado CCE agosto 2025. El sexto archivo es `cce_consulta_ambiental.md`, que es una ficha complementaria de la Sentencia 1149-19-JP/21 con énfasis en consulta ambiental (fuente N° 12 en `matriz_fuentes.md`), no un documento jurídico autónomo. La sec. 3.5.1 indica "cincuenta y tres fichas documentales" (ahora desactualizado a 54).

La forma más precisa de resolver la discrepancia es indicar "seis archivos del corpus jurisprudencial: las tres sentencias vinculantes con texto completo, la Guía CEDEC 2023, el Comunicado CCE agosto 2025 y un archivo complementario de la Sentencia 1149-19-JP/21 con énfasis en los estándares de consulta ambiental del art. 398 CRE."

**Recomendación:** En la Fase 5, corregir la sec. 3.5.3 con la formulación precisa y actualizar simultáneamente la cifra de "cincuenta y tres fichas" a "cincuenta y cuatro".
**Prioridad:** Fase 5 — antes de compilación final.

---

### TR4-4. Alerta residual sobre el Comunicado CCE agosto 2025 en la Matriz de Compatibilidad

**Tipo:** Coherencia jurídica / preventivo
**Gravedad:** Media
**Archivo afectado:** `04_matrices/matriz_compatibilidad_constitucional_ambiental.md`, nota metodológica
**Descripción:**

La coherencia entre el Cap. I, el Cap. III y la Matriz de Compatibilidad sobre el tratamiento de la Ley de Fortalecimiento 2026 es alta. El Cap. I (nota al pie 1) y el Cap. III (sec. 3.8.3) identifican correctamente la ley como vigente por R.O. verificado, con al menos 11 demandas de inconstitucionalidad al 5-abr-2026 según prensa contextual (`primicias_demandas_2026`).

Sin embargo, la nota metodológica de la `matriz_compatibilidad_constitucional_ambiental.md` menciona el Comunicado CCE agosto 2025 como referencia de estado procesal sin aclarar que ese Comunicado trata de leyes ajenas al sector minero (Integridad Pública, Inteligencia, Solidaridad Nacional). El problema P-11 fue declarado resuelto en R2 porque el Cap. I lo aclara, pero la Matriz de Compatibilidad no incluye esa aclaración. Si al redactar el Cap. IV se toma la nota de la Matriz sin verificar P-11, podría reutilizarse el Comunicado como evidencia de procesos contra la Ley Minera.

**Recomendación:** Antes de redactar el Cap. IV, agregar en la nota metodológica de `04_matrices/matriz_compatibilidad_constitucional_ambiental.md` una aclaración breve: el Comunicado CCE agosto 2025 ilustra el mecanismo procesal de suspensión provisional de normas pero se refiere a leyes ajenas al sector minero; no existe auto de admisión de la CCE sobre la Ley de Fortalecimiento 2026 incorporado al repositorio.
**Prioridad:** Antes de redactar el Cap. IV.

---

### TR4-5. Discrepancia en el conteo de fichas en el encabezado de `matriz_fuentes.md`

**Tipo:** Coherencia documental
**Gravedad:** Baja
**Archivo afectado:** `04_matrices/matriz_fuentes.md`, encabezado (nota metodológica)
**Descripción:**

El encabezado de `matriz_fuentes.md` indica "Total de fuentes registradas: 54" pero la nota dice "Total de fichas asociadas: 38 (estimado; incluye las dos fichas diferenciadas de la Sentencia 1149-19-JP/21)". Este número es notoriamente inferior a las 54 fichas que el `estado_del_proyecto.md` reporta como completadas. La discrepancia se explica porque la nota no fue actualizada cuando se sumaron sucesivas fichas. El `estado_del_proyecto.md` tiene el dato correcto: "Fichas completadas: 54 / Fuentes sin ficha: 0".

**Recomendación:** En la Fase 5, actualizar la nota de `matriz_fuentes.md` para indicar "Total de fichas asociadas: 54 (incluyendo la ficha complementaria de la Sentencia 1149-19-JP/21 con énfasis en consulta ambiental y la ficha del Manual de Técnica Legislativa)".
**Prioridad:** Fase 5 — corrección documental de baja urgencia.

---

### TR4-6. Preparación del Cap. II: cobertura de fuentes por apartado

**Tipo:** Preventivo / coherencia anticipatoria
**Gravedad:** Media
**Archivo afectado:** `00_instrucciones/estructura_capitulos.md` (estructura del Cap. II); matrices disponibles
**Descripción:**

La revisión de las matrices disponibles permite identificar los siguientes riesgos de cobertura para el Cap. II:

**Apartados con cobertura sólida:** secs. 2.2.1-2.2.7, 2.2.9-2.2.16 (corpus normativo, jurisprudencial y doctrinal); secs. 2.2.17-2.2.18 (Manual de Técnica Legislativa); secs. 2.5.1-2.5.4 (corpus normativo); sec. 2.5.8 (tres sentencias vinculantes); sec. 2.5.9 (Acuerdo de Escazú y OC-23/17).

**Apartados con cobertura parcial o riesgo identificado:**

- **Sec. 2.1.4** (antecedentes legislativos): solo la ley publicada (R.O. 234-5S) y la noticia institucional de 24 feb. 2026. El expediente legislativo no está en el repositorio. Declarar limitación explícita conforme al Cap. III.

- **Sec. 2.1.5** (antecedentes jurisprudenciales): debe incluir los tres holdings de la Sentencia 22-18-IN/21 (TR-2.2, pendiente). La Sentencia 1185-20-JP/21 está disponible solo a través de la Guía CEDEC 2023 — ver TR4-8.

- **Sec. 2.2.8** (clasificación jurídica de la minería): la distinción entre "minería informal" y "minería ilegal" tiene soporte limitado. El Plan Nacional Sector Minero 2020-2030 usa ambos términos con cierta ambigüedad. El redactor debe aclarar que el ordenamiento jurídico ecuatoriano reconoce la categoría en términos programáticos pero no la define expresamente en la Ley de Minería.

- **Sec. 2.4.3** (inversión, seguridad jurídica y control estatal): Bustamante (2012) es de valor histórico; el COIP de 2014 resolvió el "vacío legal" que esa fuente señalaba como problema. Indicar esto explícitamente.

- **Sec. 2.5.5** (reformas vigentes y proyectos de ley verificables): declarar limitación sobre el expediente legislativo. Solo disponible la Ley publicada y la noticia institucional.

**Fuentes opcionales a evaluar antes de cerrar Cap. II** (según `estado_del_proyecto.md`):
- Koehn (2022), "La reserva de ley y la seguridad jurídica" — *Andares*, UASB: no incorporada. Podría reforzar secs. 2.2.9 y el análisis de la Sent. 32-17-IN/21. Si no se incorpora, esas secciones pueden sustentarse con Villacís Calvas (2022) y la Sent. 32-17-IN/21.
- Sentencia CCE 1185-20-JP/21 (río Aquepi): texto completo no incorporado; disponible solo a través de Guía CEDEC 2023.

**Recomendación:** Al redactar la sec. 2.2.8, definir "minería informal" desde el Plan Nacional Sector Minero 2020-2030 con aclaración de que no existe categoría legal precisa en la Ley de Minería. Evaluar incorporación de Koehn (2022) mediante el flujo `/project:buscar-fuente` si se considera necesaria antes de redactar secs. 2.2.9 y 2.4.3.
**Prioridad:** Al redactar el Cap. II.

---

### TR4-7. Verificación de coherencia interna de la Matriz de Compatibilidad tras TR-2.5

**Tipo:** Coherencia jurídica
**Gravedad:** Baja
**Archivo afectado:** `04_matrices/matriz_compatibilidad_constitucional_ambiental.md`
**Descripción:**

La corrección de TR-2.5 ("criterio 17" → "criterio 16") fue verificada. Los 16 criterios son internamente coherentes: no se detectan contradicciones ni redundancias. El criterio 6 (consulta ambiental) y el criterio 7 (CPLI) están diferenciados correctamente, reproduciendo la distinción de la Sentencia 22-18-IN/21. La OC-23/17 respalda correctamente los criterios 2, 10 y 16 (párrafos 127-174 y 142 de la Opinión). La estructura de la Matriz (tabla principal de 16 criterios, tabla de ponderación y tabla ilustrativa) es apta para convertirse en `06_tablas/matriz_compatibilidad.tex`. Por la extensión de la tabla principal (9 columnas y 16 filas de contenido extenso) se recomienda `longtable` con `\small` o `\footnotesize` y posiblemente `\begin{landscape}`.

**Recomendación:** Agregar la aclaración del Comunicado CCE (TR4-4) antes de redactar el Cap. IV. No se requiere ninguna otra corrección sobre la Matriz.
**Prioridad:** Antes de redactar el Cap. IV.

---

### TR4-8. Riesgo de inconsistencia entre lo que el Cap. I adelanta sobre la Sentencia 1185-20-JP/21 y lo que el Cap. II podrá desarrollar

**Tipo:** Coherencia estructural anticipatoria
**Gravedad:** Media
**Archivo afectado:** `05_capitulos/capitulo_1_problema.tex` sec. 1.6; `05_capitulos/capitulo_2_marco_referencial.tex` (aún no redactado)
**Descripción:**

El Cap. I menciona el "caso del río Aquepi" como "precedente constitucional de alcance nacional" en la sec. 1.6. La Sentencia 1185-20-JP/21 no tiene texto completo incorporado al repositorio; está disponible únicamente a través de la Guía CEDEC 2023 (sistematización). Si el Cap. II desarrolla esta sentencia en la sec. 2.1.5 sin texto propio, debe hacerlo a través de la Guía CEDEC con la aclaración metodológica correspondiente. Si el Cap. II la omite, genera una inconsistencia con lo que el Cap. I presentó como "precedente constitucional".

**Recomendación:** Al redactar el Cap. II, sec. 2.1.5, mencionar la Sentencia 1185-20-JP/21 a través de la Guía CEDEC 2023 con la aclaración de que el texto completo no fue incorporado al repositorio y que el análisis se basa en la sistematización institucional. Esta opción mantiene coherencia con el Cap. I sin inventar fuentes. Alternativamente, incorporar el texto completo mediante el flujo `/project:buscar-fuente` antes de redactar el Cap. II.
**Prioridad:** Al redactar el Cap. II.

---

### TR4-9. Aspectos verificados y coherentes en la cuarta revisión

Los siguientes aspectos fueron verificados y no requieren corrección ni acción adicional:

1. El título exacto de la tesis aparece sin reformulación en todos los archivos revisados.
2. El alcance nacional está correctamente declarado en sec. 1.6 del Cap. I; no se delimita a provincia, ciudad ni cantón.
3. La formulación del problema, la sistematización, el objetivo general y los cuatro objetivos específicos son textualmente idénticos en `CLAUDE.md`, en `00_instrucciones/estructura_capitulos.md` y en el Cap. I.
4. La premisa de la investigación es idéntica en `CLAUDE.md` (sec. 25), en la estructura de capítulos (sec. 1.8) y en el Cap. I.
5. No hay confusión entre minería privada legal y minería ilegal en ningún documento revisado.
6. No hay confusión entre proyecto de ley y ley vigente. La Ley de Fortalecimiento 2026 está identificada como ley publicada con R.O. verificado en todos los documentos revisados.
7. Los 16 criterios de la Matriz de Compatibilidad son coherentes entre sí y con el marco jurídico verificado. Ninguno carece de fundamento verificable en el repositorio.
8. El Cap. III usa `\parencite{}` y `\textcite{}` de manera consistente. No existe mezcla con texto plano en el Cap. III.
9. La `tabla_cdiu.tex` (9 filas, 5 columnas) es coherente con la `matriz_cdiu.md` y con la descripción del Cap. I (9 categorías).
10. La Matriz de Compatibilidad articula correctamente con los cuatro objetivos específicos y con la propuesta del Cap. IV. El criterio 16 no se confunde con los efectos jurídicos ambientales.
11. Las fuentes de prensa referenciadas explícitamente en Caps. I y III tienen ficha documental verificada.
12. El corpus de 54 fuentes está completo según `estado_del_proyecto.md` (undécima actualización). No hay fuente sin ficha.
13. Las 25 entradas de `referencias.bib` corresponden a fuentes con ficha verificada. El Manual de Técnica Legislativa aún no tiene entrada en `referencias.bib`; deberá agregarse al redactar las secs. 2.2.17 y 2.2.18 del Cap. II.
14. El enfoque cualitativo, documental y jurídico-crítico es coherente entre `CLAUDE.md`, la estructura de capítulos y el Cap. III redactado.

---

### Conclusión de la cuarta revisión

**La tesis está lista para avanzar a la redacción del Capítulo II.**

Los Capítulos I y III están redactados con coherencia interna alta. Los problemas previos están en su mayoría resueltos o correctamente gestionados. Los nueve hallazgos de esta cuarta revisión son de gravedad baja o media y no impiden el inicio del Cap. II.

La incorporación del Manual de Técnica Legislativa (fuente N° 54) resuelve el vacío de TR-2.6, con la condición de que las citas textuales sean verificadas por página antes de su uso y que la entrada en `referencias.bib` identifique correctamente el año como no determinado. La corrección de TR-2.5 fue verificada y confirma que los 16 criterios de la Matriz son coherentes.

Los problemas de mayor impacto para la redacción del Cap. II son: (1) presentar los tres holdings de la Sentencia 22-18-IN/21 en secs. 2.1.5 y 2.5.8 (TR-2.2, pendiente); (2) decidir cómo citar la Sentencia 1185-20-JP/21 sin texto completo en el repositorio (TR4-8, nuevo); y (3) definir "minería informal" como categoría de análisis sin definición legal precisa en la Ley de Minería (TR4-6, nuevo). Los tres son manejables sin incorporar nuevas fuentes.

Los problemas de Fase 5 (TR-2.1, TR-2.3, SR-3.1, SR-3.4, TR4-2, TR4-3, TR4-5) son correcciones de precisión numérica y terminológica que no afectan la coherencia jurídica del análisis.

**Acción inmediata recomendada antes de iniciar el Cap. II:** agregar en la nota metodológica de `04_matrices/matriz_compatibilidad_constitucional_ambiental.md` la aclaración sobre el Comunicado CCE agosto 2025 identificada en TR4-4.

**Próximo comando recomendado:** `/redactar-capitulo capitulo_2_marco_referencial`

---

**Archivos revisados en la cuarta revisión:**

- `CLAUDE.md`
- `00_instrucciones/estructura_capitulos.md`
- `04_matrices/estado_del_proyecto.md`
- `04_matrices/reporte_coherencia_metodologica.md` (tres revisiones anteriores)
- `04_matrices/matriz_cdiu.md`
- `04_matrices/matriz_compatibilidad_constitucional_ambiental.md`
- `04_matrices/matriz_institucional.md`
- `04_matrices/matriz_fuentes.md`
- `05_capitulos/capitulo_1_problema.tex`
- `05_capitulos/capitulo_3_metodologia.tex`
- `06_tablas/tabla_cdiu.tex`
- `06_tablas/tabla_analisis_documental.tex`

---

## Archivos revisados en la tercera revisión

- `CLAUDE.md`
- `00_instrucciones/estructura_capitulos.md`
- `00_instrucciones/criterios_redaccion.md`
- `00_instrucciones/criterios_reformas_legislativas.md`
- `04_matrices/reporte_coherencia_metodologica.md` (revisiones anteriores)
- `04_matrices/estado_del_proyecto.md`
- `04_matrices/matriz_cdiu.md`
- `04_matrices/matriz_compatibilidad_constitucional_ambiental.md`
- `04_matrices/matriz_normativa.md`
- `05_capitulos/capitulo_1_problema.tex`
- `05_capitulos/capitulo_3_metodologia.tex`
- `06_tablas/tabla_cdiu.tex`
- `06_tablas/tabla_analisis_documental.tex`
