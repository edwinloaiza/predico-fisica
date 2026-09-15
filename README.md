# PREDICO — La solución de problemas en Física como forma de pensar

Notas para estudiantes sobre **PREDICO**, una táctica para entender y resolver problemas de
Física: Parafraseo, Representación, Ecuaciones relevantes, Datos, Incógnitas, Condiciones,
Objetivo — una lista de verificación, no una secuencia obligatoria de pasos.

Cubre los seis tipos de tarea que aparecen en un curso de Física (ejercicio, problema, pregunta
conceptual, análisis experimental, incertidumbre y medición, diseño y síntesis), con ejemplos
resueltos y una ficha de trabajo (plantilla PREDICO) al final.

Autor: Edwin Loaiza Acuña, Departamento de Física, Universidad del Valle.

## Compilar

```bash
pdflatex Solucion_de_Problemas_PREDICO_Estudiante.tex
bibtex Solucion_de_Problemas_PREDICO_Estudiante
pdflatex Solucion_de_Problemas_PREDICO_Estudiante.tex
pdflatex Solucion_de_Problemas_PREDICO_Estudiante.tex
```

El PDF ya compilado (`Solucion_de_Problemas_PREDICO_Estudiante.pdf`) está incluido en el repositorio.

## Estilo

Usa `theme/ELAbook.sty`, el mismo estilo visual (capítulos, colores, entornos) que las Notas de
Física I del autor — capítulo único, sin recortar contenido. Este archivo es una copia vendida
(el original vive en un repositorio privado de estilo compartido); si el estilo cambia ahí, hay
que volver a copiarlo aquí antes de recompilar y publicar.
