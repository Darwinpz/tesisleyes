# Criterios APA séptima edición

## Regla general

Aplicar correctamente normas APA séptima edición en citas, tablas, figuras y bibliografía.

No citar fuentes que no hayan sido consultadas, descargadas, verificadas e incorporadas al proyecto.

No inventar autores, años, páginas, enlaces, sentencias, proyectos de ley, artículos académicos ni datos editoriales.

---

# 1. Citas textuales cortas

Una cita textual corta es menor de 40 palabras.

Debe ir:

- entre comillas dobles;
- con autor o institución;
- año;
- página o párrafo;
- seguida de análisis propio.

Ejemplo:

```text
“texto citado” (Autor, año, p. 15).
```

Después de la cita, explicar:

- qué significa;
- por qué es relevante;
- cómo se relaciona con el problema de investigación;
- qué aporta al argumento jurídico.

No dejar citas sueltas.

---

# 2. Citas textuales largas

Una cita textual larga tiene 40 palabras o más.

Debe ir:

- en bloque independiente;
- sin comillas dobles;
- con sangría izquierda;
- con autor o institución;
- año;
- página o párrafo;
- seguida de análisis propio.

No abusar de citas textuales largas.

Priorizar paráfrasis académica y análisis propio.

---

# 3. Paráfrasis

Cuando se reformule una idea de una fuente, no usar comillas.

Debe incluir:

- autor o institución;
- año;
- página o artículo si corresponde y si la idea es específica.

Ejemplo:

```text
Según la Corte Constitucional del Ecuador (2021), ...
```

o

```text
La normativa ambiental ecuatoriana reconoce obligaciones de prevención y reparación frente al daño ambiental (Asamblea Nacional del Ecuador, 2017).
```

---

# 4. Fuentes jurídicas

## 4.1. Normas

En normas jurídicas, identificar:

- institución emisora;
- año;
- nombre completo de la norma;
- Registro Oficial, si corresponde;
- artículo cuando sea necesario.

Ejemplo de uso en texto:

```text
El Código Orgánico del Ambiente establece...
```

Si se cita un artículo específico:

```text
De acuerdo con el artículo X del Código Orgánico del Ambiente...
```

No inventar números de artículos.

Si no se identifica el artículo, escribir:

```text
Artículo no identificado en el documento.
```

## 4.2. Sentencias

En sentencias, identificar:

- Corte;
- número de sentencia;
- año;
- nombre del caso si existe;
- párrafo o sección si se cita textualmente.

Ejemplo:

```text
Corte Constitucional del Ecuador, Sentencia No. 1149-19-JP/21, caso Los Cedros.
```

## 4.3. Proyectos de ley

En proyectos de ley, identificar:

- Asamblea Nacional;
- año;
- título exacto del proyecto;
- código legislativo;
- proponente, si es relevante;
- comisión;
- estado del trámite;
- documento revisado: proyecto, informe técnico, primer debate, segundo debate, texto aprobado, objeción, Registro Oficial, etc.

No tratar un proyecto de ley como ley vigente salvo que exista Registro Oficial.

---

# 5. Bibliografía

La bibliografía debe:

- estar en formato APA séptima edición;
- ir en orden alfabético;
- tener sangría francesa en el documento final;
- incluir solo fuentes citadas;
- excluir fuentes no usadas;
- excluir fuentes no verificadas;
- excluir conversaciones de IA;
- excluir enlaces inventados.

---

# 6. Reglas para BibTeX

El archivo `referencias.bib` debe contener únicamente fuentes verificadas.

No agregar entradas BibTeX si no existe una fuente real.

No agregar entradas de fuentes externas que no estén incorporadas al repositorio.

Para proyectos de ley, si BibTeX no refleja bien la fuente, usar `@misc` con nota detallada.

Ejemplo:

```bibtex
@misc{asamblea_an_2020_1922,
  author = {{Asamblea Nacional del Ecuador}},
  title = {Proyecto de Ley Reformatoria a la Ley de Minería, Código AN-2020-1922},
  year = {2020},
  note = {Revisión en Comisión para Segundo Debate}
}
```

Para sentencias, usar `@misc` o `@jurisdiction` si el estilo lo permite.

---

# 7. Prohibiciones

No hacer lo siguiente:

- inventar páginas;
- inventar DOI;
- inventar enlaces;
- inventar autores;
- inventar editoriales;
- inventar Registro Oficial;
- inventar estado de trámite legislativo;
- citar una fuente solo porque aparece mencionada en otra;
- incluir bibliografía que no haya sido citada;
- usar una referencia de IA como fuente académica.

---

# 8. Revisión final

Antes de entregar capítulos o compilar la tesis, ejecutar:

```text
/project:revisar-citas
```

El agente `citation-auditor` debe revisar:

- citas en texto;
- citas textuales;
- paráfrasis;
- bibliografía;
- BibTeX;
- normas jurídicas;
- proyectos de ley;
- sentencias;
- tablas;
- notas de tabla.
