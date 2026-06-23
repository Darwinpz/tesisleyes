Analiza el lote indicado: $ARGUMENTS

Ejemplos válidos:

- normativa
- jurisprudencia
- doctrina
- institucional
- internacional
- prensa
- reformas_legislativas

Lee obligatoriamente:

1. `CLAUDE.md`
2. `00_instrucciones/criterios_fuentes.md`
3. `00_instrucciones/flujo_trabajo.md`

Si el lote es `reformas_legislativas`, lee también:

- `00_instrucciones/criterios_reformas_legislativas.md`

No redactes capítulos todavía.

---

# 1. Regla general

Antes de analizar documentos completos, revisa si ya existen fichas o matrices relacionadas:

1. `04_matrices/`
2. `03_fichas/`
3. `02_fuentes_md/`

Usa las fichas y matrices para reducir lectura repetida y ahorrar contexto.

Si no existen fichas o matrices, créalas.

No inventes información.

Si falta un dato, escribe:

```text
Dato no identificado en el documento.
```

---

# 2. Rutas por lote

## 2.1. Lote normativa

Si el lote es `normativa`, analiza:

```text
02_fuentes_md/normativa/
```

Usa el agente:

```text
normativa-analyst
```

Crea fichas en:

```text
03_fichas/fichas_normativas/
```

Actualiza:

```text
04_matrices/matriz_normativa.md
04_matrices/matriz_fuentes.md
```

Identifica:

1. nombre de la norma;
2. institución emisora;
3. año;
4. estado jurídico;
5. artículos relevantes;
6. relación con derecho ambiental;
7. relación con minería privada;
8. relación con derechos de la naturaleza;
9. relación con licenciamiento ambiental;
10. relación con control estatal;
11. relación con seguridad jurídica;
12. uso sugerido en capítulos.

---

## 2.2. Lote jurisprudencia

Si el lote es `jurisprudencia`, analiza:

```text
02_fuentes_md/jurisprudencia/
```

Usa el agente:

```text
jurisprudence-analyst
```

Crea fichas en:

```text
03_fichas/fichas_jurisprudenciales/
```

Actualiza:

```text
04_matrices/matriz_jurisprudencial.md
04_matrices/matriz_fuentes.md
```

Identifica:

1. Corte o tribunal;
2. número de sentencia u opinión consultiva;
3. año;
4. caso o denominación;
5. tema central;
6. derechos o principios analizados;
7. relación con minería, ambiente, consulta, precaución, reparación o derechos de la naturaleza;
8. utilidad para capítulos;
9. advertencias de uso.

---

## 2.3. Lote doctrina

Si el lote es `doctrina`, analiza:

```text
02_fuentes_md/doctrina/
```

Usa el agente:

```text
doctrine-analyst
```

Crea fichas en:

```text
03_fichas/fichas_doctrina/
```

Actualiza:

```text
04_matrices/matriz_doctrina.md
04_matrices/matriz_fuentes.md
```

Clasifica cada fuente como:

1. tesis;
2. artículo científico;
3. artículo de revista académica;
4. libro;
5. capítulo de libro;
6. estudio académico;
7. otra fuente doctrinal verificable.

Identifica:

1. autor;
2. año;
3. título;
4. institución, revista, editorial o repositorio;
5. tema central;
6. metodología si consta;
7. ideas útiles;
8. relación con derecho ambiental, minería, derechos de la naturaleza, seguridad jurídica o control estatal;
9. utilidad para capítulos;
10. advertencias de uso.

---

## 2.4. Lote institucional

Si el lote es `institucional`, analiza:

```text
02_fuentes_md/institucional/
```

Usa el agente:

```text
source-ingestor
```

Crea fichas en:

```text
03_fichas/fichas_institucionales/
```

Actualiza:

```text
04_matrices/matriz_fuentes.md
```

Si el análisis lo requiere, también puedes crear o actualizar:

```text
04_matrices/matriz_institucional.md
```

Identifica:

1. institución;
2. año;
3. tipo de documento;
4. finalidad;
5. datos o criterios relevantes;
6. relación con política minera;
7. relación con control estatal;
8. relación con licenciamiento ambiental;
9. relación con fiscalización;
10. utilidad para capítulos;
11. advertencias de uso.

---

## 2.5. Lote internacional

Si el lote es `internacional`, analiza:

```text
02_fuentes_md/internacional/
```

Usa el agente:

```text
source-ingestor
```

Crea fichas en:

```text
03_fichas/fichas_internacionales/
```

Si la carpeta no existe, créala.

Actualiza:

```text
04_matrices/matriz_fuentes.md
```

Si el análisis lo requiere, también puedes crear o actualizar:

```text
04_matrices/matriz_internacional.md
```

Identifica:

1. instrumento, organismo o tribunal;
2. año;
3. tipo de fuente;
4. tema central;
5. relación con ambiente;
6. relación con participación, acceso a información, justicia ambiental o consulta;
7. relación con derechos humanos y ambiente;
8. utilidad para capítulos;
9. advertencias de uso.

---

## 2.6. Lote prensa

Si el lote es `prensa`, analiza:

```text
02_fuentes_md/prensa/
```

Usa el agente:

```text
source-ingestor
```

Las noticias o notas periodísticas deben clasificarse como fuentes contextuales, no como fuentes jurídicas principales.

Crea fichas en:

```text
03_fichas/fichas_prensa/
```

Actualiza:

```text
04_matrices/matriz_prensa_contextual.md
04_matrices/matriz_fuentes.md
```

Por cada noticia, extrae:

1. medio de comunicación;
2. fecha;
3. autor, si consta;
4. título;
5. URL, si consta;
6. tema central;
7. hecho reportado;
8. relación con minería privada;
9. relación con minería ilegal, si corresponde;
10. relación con control estatal;
11. relación con conflictividad socioambiental;
12. relación con reformas mineras, si corresponde;
13. fuente primaria mencionada, si existe;
14. utilidad para la tesis;
15. capítulo donde podría usarse;
16. advertencia de uso.

Reglas especiales:

- No usar noticias como fuente jurídica principal.
- No usar noticias para reemplazar normas, sentencias, doctrina académica, proyectos de ley oficiales ni informes institucionales.
- Si una noticia menciona una reforma, sentencia, proyecto de ley o dato oficial, recomendar buscar la fuente primaria.
- Usar prensa solo para contexto, debate público o hechos recientes.

---

## 2.7. Lote reformas legislativas

Si el lote es `reformas_legislativas`, analiza:

```text
02_fuentes_md/reformas_legislativas/
```

Usa el agente:

```text
legislative-analyst
```

Crea fichas en:

```text
03_fichas/fichas_reformas_legislativas/
```

Actualiza:

```text
04_matrices/matriz_reformas_legislativas.md
04_matrices/matriz_fuentes.md
```

Por cada documento, identifica si corresponde a:

1. proyecto de ley;
2. informe legislativo;
3. texto aprobado;
4. objeción del Ejecutivo;
5. respuesta de Corte Constitucional;
6. Registro Oficial;
7. ley reformatoria;
8. reforma vigente;
9. noticia sobre reforma;
10. otro documento legislativo.

Criterios de análisis:

1. código del proyecto, si existe;
2. fecha;
3. institución emisora;
4. proponente, si consta;
5. comisión, si consta;
6. estado del trámite;
7. etapa legislativa;
8. finalidad declarada;
9. artículos o reformas propuestas;
10. relación con apertura minera privada;
11. relación con concesiones;
12. relación con seguridad jurídica;
13. relación con control estatal;
14. relación con licenciamiento ambiental;
15. relación con consulta ambiental;
16. relación con derechos de la naturaleza;
17. posible riesgo de regresividad;
18. incidencia en el sector minero privado;
19. utilidad para capítulos;
20. advertencias.

Reglas especiales:

- No tratar proyectos de ley como leyes vigentes.
- No tratar noticias como textos oficiales.
- Si no existe Registro Oficial, advertir que no es norma vigente.
- Si no existe la carpeta `02_fuentes_md/reformas_legislativas/` o está vacía, no reportes error crítico. Indica que no existen fuentes legislativas locales incorporadas y recomienda usar `/project:buscar-fuente`.

---

# 4. Entrega del resultado

Al finalizar, informa:

1. lote analizado;
2. agente utilizado;
3. documentos encontrados;
4. fichas creadas o actualizadas;
5. matrices actualizadas;
6. fuentes con datos faltantes;
7. fuentes que requieren verificación;
8. fuentes útiles para cada capítulo;
9. advertencias de uso;
10. siguiente lote recomendado.

No redactes capítulos.
No inventes información.
No agregues bibliografía no verificada.
