# Estructura del repositorio

El repositorio contiene los siguientes archivos y directorios:

## Archivos principales

| Archivo | Descripción |
|:--------|:------------|
| `Correa_DarwinACD.pdf` | Documento ACD (Actividad Complementaria Dirigida) |
| `Correa_DarinACD03.pdf` | Versión 03 del documento ACD |
| `Correa_DarwinAPE003.pdf` | Documento APE (Actividad Práctica Evaluativa) versión 003 |
| `INVESTIGACIÓN2026_Examen.pdf` | Examen de la asignatura Investigación 2026 |
| `APE6.pdf` | Actividad Práctica Evaluativa 6 |
| `Matriz de Extracción de Artículos Científicos.pdf` | Plantilla de extracción de datos de artículos |
| `Matriz de extracción de Artículos Científicos A...` | Versión complementaria de la matriz |
| `Reporte_Tecnico_Metodologia_Investigacion_C...` | Reporte técnico de metodología de investigación |

## Metodología aplicada en el capítulo

El capítulo "Contribución de las Redes Neuronales Artificiales al Reconocimiento de Patrones en Datos Complejos" se desarrolló siguiendo el proceso documentado en los archivos de metodología del repositorio.

### Proceso de construcción

1. **Extracción de artículos**: Utilizando la `Matriz de Extracción de Artículos Científicos.pdf` como plantilla, se identificaron 37 referencias bibliográficas relevantes desde bases de datos IEEE Xplore, Scopus y Google Scholar.

2. **Redacción del contenido**: El texto del capítulo se organizó en secciones secuenciales: Introducción, Fundamentos Teóricos (Reconocimiento de patrones, Redes neuronales, Funciones de activación, Proceso de aprendizaje, Deep Learning, Variantes), Metodología y Análisis de la Literatura, Aplicaciones, Comparación de estudios, Ventajas, Limitaciones, Métricas, Discusión, Oportunidades futuras y Conclusiones.

3. **Sistema de citación IEEE**: 
   - Cada referencia recibió un número `[1]` a `[37]` según su primera aparición en el texto.
   - La misma referencia reutiliza el mismo número en todas sus apariciones.
   - La última cita del texto es `[37]` (ubicada en la sección Oportunidades futuras).
   - Las Conclusiones no contienen citas.

4. **Archivo de bibliografía**: `export_numerado.bib` contiene las 37 referencias en formato BibTeX.

### Compilación del documento

Para generar el PDF del capítulo:

```bash
pdflatex capitulo25_redes_neuronales.tex
bibtex capitulo25_redes_neuronales
pdflatex capitulo25_redes_neuronales.tex
pdflatex capitulo25_redes_neuronales.tex
