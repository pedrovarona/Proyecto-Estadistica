# Proyecto de Estadística: Relación entre Sueño y Rendimiento Académico 💤

**Asignatura:** Estadística  
**Carrera:** GISI  
**Integrantes:** Pedro Varona, Francisco Javier Martínez, Alfredo Martínez y Juan García Obregón  

---

## 🎯 Objetivo  
Evaluar la relación entre las **horas y la calidad del sueño** y el **rendimiento académico (nota media)** de estudiantes GISI, considerando variables como la edad, el sexo y la actividad física.  

---

## 🧩 Metodología  
**Población:** estudiantes matriculados en GISI.  
**Muestra:** ~200 participantes (muestreo por curso).  

**Variables:**  
- **Dependiente:** Nota media del curso anterior (0–10)  
- **Principales:** Horas de sueño (<5h, 5–7h, 7–8h, 8–10h, >10h), Calidad del sueño (1–10)  
- **Covariables:** Actividad física (1–10), Edad y Sexo  

---

## 📊 Análisis Estadístico  
El análisis se realizó en **RStudio** con [`Análisis Estadístico.Rmd`](./An%C3%A1lisis%20Estad%C3%ADstico.Rmd).  

**Técnicas utilizadas:**  
- Gráficos descriptivos y exploratorios  
- Correlaciones de Pearson  
- ANOVA y modelo de regresión lineal (α = 0.05)  

**Resultados principales:**  
- Correlación positiva y significativa entre **calidad del sueño** y **nota media** (r = 0.465, p < 0.001)  
- Dormir **7–10 horas** se asocia con una **mejor nota media** (~+1.2 puntos, p < 0.001)  
- **Actividad física:** relación leve (r = 0.178, p = 0.017)  
- **Edad y sexo:** sin influencia significativa  

---

## ⚠️ Limitaciones  
- Algunas encuestas incompletas  
- Variables subjetivas (calidad del sueño, actividad física)  
- Muestra limitada a una carrera (no generalizable)  
- Correlación ≠ causalidad  

---
