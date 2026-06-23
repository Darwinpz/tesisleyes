# Criterios LaTeX

## Regla general

La tesis final se redacta en LaTeX.

No crear documento Word.

No escribir capítulos completos dentro de `main.tex`.

Cada capítulo debe estar en su archivo correspondiente dentro de `05_capitulos/`.

---

# 1. Archivos principales

Archivo principal:

```text
main.tex
```

Bibliografía:

```text
referencias.bib
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
06_tablas/
```

Anexos:

```text
07_anexos/
```

Salida de compilación:

```text
08_build/
```

---

# 2. Comandos de estructura

Usar:

```latex
\chapter{}
\section{}
\subsection{}
\subsubsection{}
```

No usar títulos manuales en negrita si corresponde una sección LaTeX.

---

# 3. Tablas

Toda tabla debe tener:

```latex
\caption{}
\label{}
```

Además debe tener nota y análisis posterior.

Para tablas cortas:

```latex
\begin{table}[H]
\centering
\caption{Título de la tabla}
\label{tab:etiqueta}
\begin{tabular}{...}
...
\end{tabular}
\end{table}
```

Para tablas largas:

```latex
\begin{longtable}{...}
...
\end{longtable}
```

Para tablas horizontales:

```latex
\begin{landscape}
...
\end{landscape}
```

---

# 4. Bibliografía

Usar `biblatex` y `biber`.

Las referencias deben estar en:

```text
referencias.bib
```

No agregar referencias no verificadas.

No agregar entradas BibTeX inventadas.

---

# 5. Citas

Usar comandos compatibles con `biblatex-apa`, según configuración del proyecto.

Ejemplos:

```latex
\parencite{clave}
\textcite{clave}
```

Si la cita no se puede resolver, dejar comentario temporal:

```latex
% CITA PENDIENTE: verificar fuente y página.
```

No inventar claves BibTeX.

---

# 6. Comentarios útiles

Para pendientes:

```latex
% TODO: verificar artículo.
% TODO: agregar cita.
% TODO: revisar coherencia con objetivo específico 2.
```

No dejar comentarios finales sin revisar en versión definitiva.

---

# 7. Compilación

Compilar con:

```powershell
scripts/compilar_latex.ps1
```

O con:

```bash
latexmk -pdf -interaction=nonstopmode -outdir=08_build main.tex
```

Si hay errores:

1. revisar archivo;
2. ubicar línea;
3. corregir sintaxis;
4. no modificar contenido jurídico sin autorización;
5. compilar nuevamente.

---

# 8. Prohibiciones

No hacer lo siguiente:

- escribir todo en `main.tex`;
- mezclar capítulos en un solo archivo;
- insertar tablas enormes dentro de capítulos si deben ir en `06_tablas/`;
- borrar contenido jurídico para resolver error de compilación;
- cambiar títulos de capítulos sin autorización;
- eliminar citas para compilar;
- inventar referencias para eliminar errores de bibliografía.
