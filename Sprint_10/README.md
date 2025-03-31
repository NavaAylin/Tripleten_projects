# 🔗 Proyecto Sprint 10: Aprendizaje automático en negocios

**"Crear un modelo para predecir el volumen de reservas en los nuevos pozos y aportar recomendaciones para una compañía minera."**

Tras haber explorado las métricas de negocios, este proyecto busca relacionar los resultados de un modelo de regresión lineal con dichas métricas, permitiendo identificar las mejores estrategias para una compañía minera. Se aplican técnicas de simulación de riesgos con bootstrapping y se consideran restricciones reales del negocio.

## Skills 🛠:
- 🐍 Procesamiento de datos  
- 📊 Análisis exploratorio  
- 🤖 Fundamentos de ML  
- 📈 Modelos de regresión  

---

## Descripción del proyecto

Trabajas para la compañía de extracción de petróleo **OilyGiant**. El objetivo es encontrar los mejores lugares para abrir **200 nuevos pozos petroleros**, predecir el volumen de reservas y evaluar la rentabilidad esperada.

Se utilizan modelos de **regresión lineal**, simulaciones con **bootstrapping** y métricas financieras como **ganancia esperada** y **riesgo de pérdida**, todo en base a los datos de exploración geológica en tres regiones diferentes.

---

## Instrucciones del proyecto

1. **Descargar y preparar los datos**  
   - Archivos: `geo_data_0.csv`, `geo_data_1.csv`, `geo_data_2.csv`  
   - Limpiar y dividir los datos en entrenamiento (75%) y validación (25%)

2. **Entrenamiento de modelos por región**  
   - Usar regresión lineal  
   - Evaluar con RMSE y volumen promedio de reservas

3. **Simulación de ganancias**  
   - Calcular ganancias para los 200 pozos con mejores predicciones  
   - Comparar contra el umbral mínimo ($500,000 por pozo)

4. **Estimación de riesgo y ganancia**  
   - Usar `bootstrapping` con 1000 muestras  
   - Calcular beneficio medio, intervalo de confianza del 95% y riesgo de pérdida

5. **Recomendaciones**  
   - Seleccionar la mejor región basándose en los beneficios esperados y bajo riesgo (<2.5%)

---

## 🗂️ Descripción de los datos

Cada archivo (`geo_data_0.csv`, `geo_data_1.csv`, `geo_data_2.csv`) contiene información geológica de una región:

- `id`: identificador del pozo  
- `f0`, `f1`, `f2`: características del punto de extracción  
- `product`: volumen de reservas (en miles de barriles) — variable objetivo
