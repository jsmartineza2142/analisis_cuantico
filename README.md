# Análisis Clásico vs Cuántico

Este repositorio contiene ejercicios prácticos realizados con Qiskit, comparando cómo un modelo clásico y un modelo cuántico detectan combinaciones de datos.  

Se usan ejemplos con datos de salud (Glucosa, IMC, Ejercicio, Estrés, Alcohol) para ilustrar la diferencia entre ambos enfoques.

---

## Archivos

- `datos_salud.csv` → Tabla con los datos de ejemplo.  
- `modelo_cuantico.ipynb` → Notebook con ejercicios de Qiskit y simulaciones.  
- `README.md` → Este archivo.  

---

## Resultados del circuito cuántico

| Estado | Frecuencia | Detectado por cuántico |
|--------|------------|-----------------------|
| 00     | 489        | No                    |
| 11     | 511        | Sí                    |

> **Explicación:**  
> - El modelo cuántico puede detectar combinaciones de datos que el modelo clásico no.  
> - Por ejemplo, combinaciones que no cumplen las condiciones clásicas pero que, debido a la **superposición y entrelazamiento cuántico**, el algoritmo detecta como relevantes.  
> - Esto permite explorar patrones nuevos fuera de los datos vistos previamente.

---

## Cómo usar

1. Abrir `modelo_cuantico.ipynb` en Google Colab o Jupyter.  
2. Cargar `datos_salud.csv`.  
3. Ejecutar los ejercicios para ver la comparación de resultados entre el modelo clásico y cuántico.  

---

## Nota

Este proyecto es **educativo**, orientado a aprender conceptos de computación cuántica aplicada a análisis de datos, usando bases de datos pequeñas.
