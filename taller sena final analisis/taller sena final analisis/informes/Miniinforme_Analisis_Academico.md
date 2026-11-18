# Miniinforme: factores asociados al resultado académico

## Introducción

Se analizó el conjunto de datos académico indicado en la guía, compuesto por 4,424 registros de estudiantes y 38 variables. La columna Target identifica tres resultados: Graduate, Dropout y Enrolled. El trabajo utiliza Pandas para organizar y agrupar la información, NumPy para los cálculos estadísticos y Matplotlib para las visualizaciones.

## Indicadores principales por resultado

| Target   |   estudiantes |   edad_promedio |   nota_semestre_1 |   nota_semestre_2 |   aprobadas_semestre_1 |   aprobadas_semestre_2 |
|:---------|--------------:|----------------:|------------------:|------------------:|-----------------------:|-----------------------:|
| Dropout  |          1421 |           26.07 |              7.26 |              5.9  |                   2.55 |                   1.94 |
| Enrolled |           794 |           22.37 |             11.13 |             11.12 |                   4.32 |                   4.06 |
| Graduate |          2209 |           21.78 |             12.64 |             12.7  |                   6.23 |                   6.18 |


## Correlación entre las notas semestrales

La correlación calculada con NumPy entre las notas del primer y segundo semestre es **0.8372**. Esta medida describe asociación lineal y no demuestra causalidad.

## Cinco hallazgos

1. El resultado más frecuente es Graduate, con 2209 estudiantes (49.93%).

2. Dropout representa 32.12% del total de estudiantes.

3. El grupo con mayor edad promedio es Dropout, con 26.07 años.

4. El promedio de nota del primer semestre es 10.64 y el del segundo semestre es 10.23.

5. La correlación entre las notas del primer y segundo semestre es 0.8372; indica asociación lineal, no causalidad.

## Dos recomendaciones

1. Revisar periódicamente las notas y las asignaturas aprobadas de ambos semestres para identificar grupos que puedan necesitar acompañamiento académico.

2. Ampliar el análisis con información de nuevas cohortes y variables institucionales antes de tomar decisiones o atribuir causas a la deserción.

## Nota metodológica

Los resultados describen únicamente el archivo analizado. Las asociaciones observadas no permiten establecer causas de deserción ni generalizar automáticamente a otras instituciones o cohortes.
