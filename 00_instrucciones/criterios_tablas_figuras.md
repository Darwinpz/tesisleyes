# Criterios para tablas, cuadros, matrices y figuras

## Regla general

Toda tabla, cuadro, matriz o figura debe estar vinculada con el análisis de la tesis.

No incluir tablas o matrices sin explicación previa ni análisis posterior.

---

# 1. Tablas

Toda tabla debe contener:

1. Número.
2. Título claro.
3. Cuerpo de la tabla.
4. Nota explicativa.
5. Fuente o indicación de elaboración propia.
6. Análisis posterior.

Ejemplo de título:

```text
Tabla 1
Matriz de análisis legislativo de proyectos de reforma a la Ley de Minería
```

Ejemplo de nota:

```text
Nota. Elaboración propia con base en la revisión documental de proyectos legislativos de la Asamblea Nacional.
```

Si se adapta de una fuente:

```text
Nota. Adaptado de Autor o Institución (año).
```

---

# 2. Ubicación de tablas en LaTeX

Las tablas cortas pueden incluirse directamente en el capítulo.

Las tablas largas deben ubicarse en:

```text
06_tablas/
```

Y luego enlazarse desde el capítulo correspondiente con:

```latex
\input{06_tablas/nombre_tabla.tex}
```

---

# 3. Tablas largas

Para matrices largas usar:

```latex
\begin{longtable}{...}
...
\end{longtable}
```

Si la tabla es muy ancha, usar orientación horizontal con `pdflscape`.

Ejemplo:

```latex
\begin{landscape}
\begin{longtable}{...}
...
\end{longtable}
\end{landscape}
```

---

# 4. Tablas obligatorias o recomendadas

El proyecto puede incluir:

- Tabla CDIU.
- Matriz de fuentes.
- Matriz normativa.
- Matriz jurisprudencial.
- Matriz legislativa de Asamblea Nacional.
- Matriz de compatibilidad constitucional y ambiental.
- Matriz de análisis documental.
- Matriz de resultados.
- Cuadro de lineamientos jurídicos.

---

# 5. Matriz legislativa

La matriz legislativa debe incluir, según disponibilidad de fuentes:

- código del proyecto;
- fecha;
- nombre del proyecto;
- proponente;
- comisión;
- estado del trámite;
- documentos revisados;
- artículos o reformas propuestas;
- finalidad declarada;
- relación con apertura minera privada;
- relación con seguridad jurídica;
- relación con derechos de la naturaleza;
- efecto sobre licenciamiento ambiental;
- efecto sobre fiscalización estatal;
- posible riesgo de regresividad;
- incidencia en el sector minero privado;
- observación crítica;
- fuente verificable.

---

# 6. Matriz de compatibilidad constitucional y ambiental

La matriz de compatibilidad debe evaluar:

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
- reparación integral;
- transparencia;
- seguridad jurídica;
- incidencia en el sector minero privado.

---

# 7. Figuras

Toda figura debe contener:

- número;
- título;
- fuente;
- nota si corresponde;
- análisis posterior.

No incluir figuras decorativas.

Las figuras deben aportar a la explicación del tema.

---

# 8. Análisis posterior obligatorio

Después de cada tabla, cuadro, matriz o figura, redactar un párrafo que explique:

- qué muestra;
- por qué es relevante;
- cómo se relaciona con los objetivos;
- qué hallazgo permite identificar;
- cómo aporta al capítulo.

No dejar tablas sin comentario.
