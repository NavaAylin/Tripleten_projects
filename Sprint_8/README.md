# 🔗 Proyecto Sprint 8: Introducción al Machine Learning

**"Crear un modelo de clasificación que escogerá el plan adecuado para la clientela de un operador de telefonía móvil."**

Este es mi primer acercamiento formal al *Machine Learning*, usando distintos tipos de modelos y ajustando sus hiperparámetros de forma estructurada para encontrar aquel que funcione de la mejor manera. El mejor modelo para esta tarea fue un **Bosque Aleatorio de Clasificación**.

## Skills 🛠:
- 📊 Procesamiento de datos  
- 🤖 Fundamentos de ML  
- 🧠 Modelos de clasificación

---

## Descripción del proyecto

La compañía móvil **Megaline** no está satisfecha con ver que muchos de sus clientes utilizan planes heredados. Para resolver esto, desean desarrollar un modelo que analice el comportamiento de los usuarios y recomiende uno de los nuevos planes: **Smart** o **Ultra**.

Para esta tarea de clasificación, se utilizó un dataset de suscriptores que ya se han cambiado a estos planes. El objetivo es crear un modelo con una **exactitud mínima de 0.75**, capaz de recomendar el plan más adecuado.

---

## Instrucciones del proyecto

- Abrir y examinar el archivo: `/datasets/users_behavior.csv`
- Dividir los datos en: conjunto de **entrenamiento**, **validación** y **prueba**
- Probar diferentes modelos (como árbol de decisión, random forest, regresión logística) y ajustar hiperparámetros
- Evaluar el mejor modelo usando el conjunto de prueba
- _(Extra)_ Realizar una prueba de cordura para verificar el comportamiento del modelo con datos aleatorios

---

## 🗂️ Descripción de datos

Cada fila del dataset representa el comportamiento mensual de un usuario e incluye las siguientes variables:

- `calls`: número de llamadas realizadas  
- `minutes`: duración total de las llamadas (en minutos)  
- `messages`: número de mensajes enviados  
- `mb_used`: tráfico de Internet utilizado (en MB)  
- `is_ultra`: variable objetivo (1 = Ultra, 0 = Smart)
