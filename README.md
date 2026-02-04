# Optimización del Gran Premio de Fórmula 1 de Madrid 🏎️

![Modelo óptimo de estrategia F1 Madrid](images/madrid-gp-f1.png)

---

## Descripción del proyecto
Este trabajo desarrolla un modelo de **Investigación Operativa** aplicado a la
optimización de la estrategia de carrera en Fórmula 1, tomando como caso de estudio
el **Gran Premio de Madrid**.

Se formula un modelo de **Programación No Lineal Entera Mixta (MINLP)** que integra
decisiones estratégicas discretas y variables continuas asociadas al rendimiento
del monoplaza y la degradación de neumáticos.

---

## Contenido
 **Trabajo completo (notebook renderizado):**  
[Ver README.ipynb](./README.ipynb)

---

## Metodología
- Variables binarias: paradas en boxes, compuestos, modos de carrera  
- Variables continuas: tiempos de stint, degradación, duración  
- Función objetivo: minimización del tiempo total de carrera  
- Restricciones técnicas, reglamentarias y estratégicas  
- Análisis de sensibilidad de los parámetros clave
