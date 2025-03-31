# 🔗 Proyecto Sprint 13: Series Temporales – Predicción de demanda en taxis

Este proyecto tiene como objetivo **predecir la cantidad de pedidos de taxi en la siguiente hora**, permitiendo a la empresa Sweet Lift Taxi optimizar la distribución de conductores durante las horas pico. Se aplican técnicas específicas de análisis de series temporales y modelos de machine learning adaptados a datos con componente temporal.

## Skills 🛠:
- 🤖 ML avanzado  
- ⏱️ Análisis de series temporales  

---

## Descripción del proyecto

La compañía **Sweet Lift Taxi** busca anticipar la cantidad de pedidos por hora en los aeropuertos para organizar con mayor eficiencia sus recursos. Para lograrlo, se parte de un dataset con una **etiqueta temporal y número de órdenes por unidad de tiempo**, y se desarrollan pasos clave como:

- Limpieza y re-muestreo de los datos a intervalos de una hora  
- Análisis de tendencias, estacionalidad y residuo  
- Generación de características con variables retrasadas  
- Entrenamiento de distintos modelos con hiperparámetros ajustados  
- Evaluación de la calidad del modelo con la métrica **RECM**, con el objetivo de mantenerla **por debajo de 48**

---

## Instrucciones del proyecto

1. Cargar los datos desde: `/datasets/taxi.csv`
2. Re-muestrear los datos a intervalos de 1 hora
3. Realizar análisis exploratorio:
   - Visualizar series
   - Calcular medias móviles
   - Descomposición en componentes: tendencia, estacionalidad, residuo
4. Crear características usando retrasos (lags) y estacionalidad
5. Dividir el dataset (90% entrenamiento, 10% prueba)
6. Entrenar y evaluar múltiples modelos de predicción
7. Presentar conclusiones y métricas obtenidas

---

## Descripción de los datos

**Archivo:** `/datasets/taxi.csv`  
El dataset contiene datos históricos con marcas de tiempo y pedidos por unidad de tiempo.

**Columnas:**
- `datetime`: marca temporal del registro  
- `num_orders`: número de pedidos de taxi

---
