# 🔗 Proyecto Sprint 11: Álgebra lineal aplicada a datos y privacidad

**"Aplicar métodos de álgebra lineal y machine learning para mejorar el análisis de datos de clientes y demostrar técnicas de protección de información personal sin comprometer la precisión del modelo."**

Este proyecto utiliza herramientas de álgebra lineal combinadas con algoritmos de machine learning para resolver diversas tareas en el contexto de una aseguradora. Se construyen modelos de clasificación y regresión, se identifican clientes similares, y se aplica una técnica de **ofuscación de datos** mediante multiplicación de matrices, que protege la información sin afectar la precisión de los modelos.

## Skills 🛠:
- 📊 Fundamentos de ML  
- 📈 Modelos de regresión  

---

## 🧾 Descripción del proyecto

La compañía de seguros **Sure Tomorrow** desea aplicar machine learning para resolver cuatro tareas:

1. Encontrar clientes similares para facilitar campañas de marketing (KNN con diferentes métricas y escalado de datos).
2. Predecir si un cliente recibirá beneficios de seguro.
3. Predecir cuántos beneficios podría recibir un nuevo cliente (modelo de regresión lineal).
4. Aplicar una técnica de **ofuscación de datos** que proteja la privacidad sin afectar la calidad del modelo.

Se aplican técnicas como escalado, codificación, validación cruzada, y se analiza el efecto de la transformación lineal mediante multiplicación de matrices aleatorias invertibles.

---

## Instrucciones del proyecto

- Cargar y explorar el dataset `insurance_us.csv`
- Verificar consistencia, tipos de datos y valores atípicos
- Desarrollar cada una de las tareas:
  - KNN con/ sin escalado y métricas variadas
  - Clasificador simple vs modelo entrenado
  - Regresión lineal para predecir beneficios
  - Técnica de enmascaramiento de datos (ofuscación con matriz aleatoria)
- Evaluar precisión, F1, MAE y comportamiento tras la ofuscación
- Analizar cómo se conserva la exactitud tras revertir la transformación con la matriz inversa

---

##  Descripción de los datos

**Archivo:** `/datasets/insurance_us.csv`  
Cada fila contiene información de un cliente asegurado:

**Características:**
- `gender`: género  
- `age`: edad  
- `salary`: salario  
- `family_members`: número de familiares  

**Variable objetivo:**
- `insurance_benefits`: cantidad de beneficios recibidos en los últimos 5 años
