# Criterios para uso de fuentes

## Regla general

Las fuentes deben ser reales, verificables y preferiblemente oficiales, académicas o institucionales.

No usar conversaciones de IA como fuente académica.

No inventar fuentes, autores, enlaces, páginas, sentencias, artículos, proyectos de ley, informes ni datos.

---

# 1. Prioridad de fuentes locales

Antes de consultar fuentes externas, Claude debe revisar:

1. `04_matrices/`
2. `03_fichas/`
3. `02_fuentes_md/`
4. `01_fuentes_pdf_originales/`

No redactar capítulos extensos sin revisar fichas y matrices.

No releer documentos completos si ya existen fichas y matrices actualizadas, salvo que sea necesario verificar una cita, artículo, página, párrafo o dato específico.

---

# 2. Estado actual de fuentes locales

El repositorio contiene fuentes locales en:

```text
02_fuentes_md/normativa/
02_fuentes_md/jurisprudencia/
02_fuentes_md/doctrina/
02_fuentes_md/institucional/
02_fuentes_md/internacional/
```

Puede incorporarse posteriormente:

```text
02_fuentes_md/prensa/
```

---

# 3. Fuentes permitidas

Priorizar:

* normativa vigente;
* reformas publicadas;
* Registro Oficial;
* Corte Constitucional del Ecuador;
* jurisprudencia constitucional;
* Ministerio del Ambiente, Agua y Transición Ecológica;
* Ministerio de Energía y Minas;
* organismos de regulación y control minero;
* documentos institucionales;
* repositorios universitarios;
* revistas académicas;
* artículos científicos;
* tesis de grado o posgrado;
* organismos internacionales oficiales;
* Asamblea Nacional del Ecuador, cuando se localicen documentos oficiales verificables;
* medios de comunicación ecuatorianos, únicamente como fuentes contextuales.

---

# 4. Fuentes a verificar

Verificar, cuando corresponda:

* Constitución de la República del Ecuador de 2008.
* Código Orgánico del Ambiente.
* Reglamento al Código Orgánico del Ambiente.
* Ley de Minería vigente.
* Reglamento General a la Ley de Minería.
* Reformas vigentes a la Ley de Minería.
* Instructivos relacionados con exploración, explotación y concesiones mineras.
* Código Orgánico Integral Penal, únicamente cuando se analicen delitos ambientales o minería ilegal.
* Sentencia No. 1149-19-JP/21, caso Los Cedros.
* Jurisprudencia sobre derechos de la naturaleza.
* Jurisprudencia sobre consulta ambiental.
* Jurisprudencia sobre consulta previa.
* Jurisprudencia sobre principio de precaución.
* Jurisprudencia sobre reparación integral.
* Documentos del Ministerio del Ambiente, Agua y Transición Ecológica.
* Documentos del Ministerio de Energía y Minas.
* Plan Nacional de Desarrollo del Sector Minero 2020-2030.
* Política minera del Ecuador.
* Documentos de organismos de control minero.
* Acuerdo de Escazú.
* Opinión Consultiva OC-23/17 de la Corte Interamericana de Derechos Humanos.
* Documentos de CEPAL sobre implementación del Acuerdo de Escazú.
* Doctrina académica desde 2021, salvo fuentes anteriores indispensables.
* Noticias ecuatorianas, solo si aportan contexto y no sustituyen fuentes oficiales.

---

# 5. Fuentes externas

Si una información no está en el repositorio, Claude puede buscar externamente para localizar documentos:

* oficiales;
* académicos;
* institucionales;
* jurisprudenciales;
* legislativos;
* periodísticos ecuatorianos, solo para contexto.

No usar la fuente externa para redactar hasta que:

1. se identifique;
2. se verifique;
3. se descargue o guarde;
4. se convierta a `.md`, si corresponde;
5. se incorpore al repositorio;
6. se cree ficha;
7. se incorpore en matriz.

---

# 6. Qué reportar cuando se encuentre una fuente externa

Claude debe reportar:

* título exacto;
* institución, autor o medio;
* año o fecha;
* enlace;
* tipo de documento;
* resumen breve;
* utilidad para la tesis;
* capítulo donde podría usarse;
* advertencia de uso;
* recomendación de descarga o incorporación;
* si es fuente jurídica principal o fuente contextual.

---

# 7. Prensa ecuatoriana

Los medios de comunicación ecuatorianos pueden usarse para contextualizar:

* debates públicos;
* conflictividad socioambiental;
* minería ilegal;
* reformas recientes;
* posiciones institucionales;
* declaraciones de autoridades;
* impactos sociales;
* discusión pública sobre minería.

Las noticias no deben reemplazar:

* normas;
* sentencias;
* doctrina académica;
* documentos institucionales;
* Registro Oficial;
* proyectos de ley oficiales;
* informes legislativos.

Si una noticia menciona una reforma, proyecto de ley, sentencia o dato oficial, Claude debe buscar la fuente primaria antes de usarla como respaldo jurídico.

Las noticias deben guardarse, si se incorporan, en:

```text
01_fuentes_pdf_originales/prensa/
02_fuentes_md/prensa/
03_fichas/fichas_prensa/
04_matrices/matriz_prensa_contextual.md
```

---

# 8. Fuentes no recomendadas como fuente principal

No usar como fuente principal:

* blogs;
* opiniones sin respaldo;
* notas periodísticas no verificadas;
* páginas sin institución identificable;
* respuestas de IA;
* resúmenes sin documento original;
* archivos sin autor o entidad;
* enlaces rotos;
* fuentes que no se hayan leído;
* publicaciones de redes sociales;
* notas de prensa sin documento oficial cuando se trate de reformas, leyes o sentencias.

Pueden usarse solo como orientación para encontrar la fuente primaria.

---

# 9. Regla para afirmaciones jurídicas

Toda afirmación jurídica relevante debe basarse en:

* norma;
* sentencia;
* reforma publicada;
* proyecto de ley verificable;
* informe legislativo;
* documento institucional;
* doctrina académica;
* matriz;
* ficha.

Si no existe respaldo, escribir:

```text
Pendiente de verificación documental.
```

---

# 10. Diferenciaciones obligatorias

Diferenciar siempre:

* minería privada legal;
* minería ilegal;
* minería artesanal;
* pequeña minería;
* mediana minería;
* minería a gran escala;
* actividad informal;
* concesión minera;
* autorización administrativa;
* licenciamiento ambiental;
* consulta ambiental;
* consulta previa;
* proyecto de ley;
* reforma legal;
* norma vigente;
* Registro Oficial;
* noticia de prensa;
* doctrina académica;
* informe institucional.

---

# 11. Regla de no invención

Si falta información, escribir:

```text
Dato no identificado en el documento.
```

No completar vacíos con suposiciones.

No convertir una hipótesis en hecho probado.

No convertir una noticia en fuente jurídica principal.

No convertir un proyecto de ley en ley vigente.

---

# 12. Regla final de uso

La tesis debe sostenerse principalmente en:

* normativa vigente;
* jurisprudencia constitucional;
* doctrina académica;
* documentos institucionales;
* fuentes internacionales.

La prensa ecuatoriana puede usarse solo como contexto.

Las fuentes legislativas externas pueden incorporarse si son actuales, verificables y útiles para la investigación.
