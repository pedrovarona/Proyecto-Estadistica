Proyecto de Estadística: Relación Horas de Sueño vs Nota media

Asignatura: Estadística
Carrera: GISI
Integrantes: Pedro Varona, Francisco Javier Martínez, Alfredo Martínez y Juan García Obregón

🎯 Objetivo
Evaluar la relación entre las horas y la calidad del sueño y el rendimiento académico (nota media) de estudiantes GISI, considerando edad, sexo y actividad física.

🧩 Metodología
Población: estudiantes matriculados en GISI.
Muestra: ~200 participantes, muestreo por curso.

Variables:
Dependiente: Nota media del curso anterior (0–10).
Principales: Horas de sueño (rangos: <5h, 5–7h, 7–8h, 8–10h, >10h), Calidad del sueño (1–10).
Covariables: Actividad física (1–10), Edad, Sexo.
Recogida de datos: encuestas online, entrevistas presenciales y formularios en papel.
Datos: Datos Estadística.xlsx

📊 Análisis Estadístico
Trabajo realizado en RStudio con Análisis Estadístico.Rmd: gráficos descriptivos, correlaciones de Pearson, ANOVA y regresión lineal (α = 0.05).
Resumen de resultados:
Calidad del sueño se asocia positivamente con la nota media (p < 0.001; r ≈ 0.47).
Dormir 7–10 horas se relaciona con una mejor media que otros rangos (p < 0.001).
Actividad física muestra relación débil; edad y sexo no son significativos.
Informe completo: Estudio Estadística-Analisis Estadístico.pdf

⚠️ Limitaciones
Respuestas incompletas en algunas encuestas.
Variables subjetivas (calidad del sueño, actividad física).
Muestra de una sola carrera → generalización limitada.
La correlación no implica causalidad.

🗂️ Estructura del repositorio

Proyecto-Estadistica
├─ Datos Estadística.xlsx
├─ Análisis Estadístico.Rmd
├─ Estudio Estádistico-Metodologia.pdf
├─ Estudio Estadística-Analisis Estadístico.pdf
└─ README.md
