
# 🔗 Proyecto Sprint 12: Métodos Numéricos aplicados al precio de vehículos

Este proyecto se centra en construir un modelo de machine learning capaz de **estimar el valor de mercado de vehículos de segunda mano**, apoyando al cliente en la toma de decisiones al vender su auto. Para lograrlo, se hace un procesamiento y limpieza intensiva del dataset, seguido del entrenamiento de múltiples modelos con énfasis en métodos de **potenciación de gradiente** como **CatBoost, LightGBM y XGBoost**.

## Skills 🛠:
- 🤖 ML avanzado  
- 📈 Modelos de regresión  
- 🧠 Redes Neuronales (opcional)  

---

## Descripción del proyecto

**Rusty Bargain**, una empresa dedicada a la venta de coches de segunda mano, está desarrollando una app que permita a los clientes **conocer rápidamente el valor real de su vehículo**. Tienes acceso a un dataset con historial, características técnicas y precios de miles de coches, y tu tarea es crear el mejor modelo predictivo posible.

El enfoque incluye comparar diferentes algoritmos con respecto a:

- Calidad de predicción (RECM)  
- Velocidad de predicción  
- Tiempo de entrenamiento  

---

## Instrucciones del proyecto

1. Cargar y explorar los datos desde: `/datasets/car_data.csv`
2. Realizar limpieza de datos y transformación de variables categóricas
3. Entrenar múltiples modelos:
   - Regresión lineal (prueba de cordura)
   - Árbol de decisión
   - Bosque aleatorio
   - LightGBM (con ajuste de hiperparámetros)
   - CatBoost y XGBoost (opcional)
4. Medir y comparar:
   - RECM
   - Tiempo de entrenamiento
   - Tiempo de predicción
5. Analizar resultados y seleccionar el mejor modelo

---

## Descripción de los datos

**Archivo:** `/datasets/car_data.csv`  
Cada fila contiene datos del perfil de un vehículo listado en la plataforma.

**Características principales:**

- `DateCrawled`: fecha de recolección del perfil  
- `VehicleType`: tipo de carrocería  
- `RegistrationYear`: año de matriculación  
- `Gearbox`: tipo de transmisión  
- `Power`: potencia del motor (CV)  
- `Model`: modelo del vehículo  
- `Mileage`: kilometraje en km  
- `RegistrationMonth`: mes de matriculación  
- `FuelType`: tipo de combustible  
- `Brand`: marca del vehículo  
- `NotRepaired`: indica si el coche fue reparado  
- `DateCreated`: fecha de publicación  
- `NumberOfPictures`: cantidad de fotos del vehículo  
- `PostalCode`: código postal del propietario  
- `LastSeen`: última vez que el perfil estuvo activo

**Variable objetivo:**

- `Price`: precio del vehículo en euros
