# 🔗 Proyecto Sprint 4: Análisis estadístico de datos

**Objetivo del proyecto:**  
Comparar los dos planes de prepago de un operador de telecomunicaciones para determinar cuál genera más beneficios.  
Este proyecto utiliza estadística para diferenciar poblaciones a través de pruebas T y generar conclusiones basadas en datos reales.

## Skills 🛠:
- 📉 Análisis estadístico  
- 🐍 Python

---

## Descripción del proyecto

Vas a realizar un análisis preliminar de las tarifas basado en una selección de clientes relativamente pequeña. Tendrás los datos de 500 clientes de Megaline: quiénes son los clientes, de dónde son, qué tarifa usan, así como la cantidad de llamadas que hicieron y los mensajes de texto que enviaron en 2018. Tu trabajo es analizar el comportamiento de los clientes y determinar qué tarifa de prepago genera más ingresos. Más adelante, encontrarás en las instrucciones del proyecto cuáles son exactamente los aspectos del comportamiento de los clientes que debes analizar. Determinar qué plan, en promedio, aporta más ingresos es una cuestión que se abordará mediante pruebas estadísticas.   
---

## 💵 Descripción de las tarifas

**Surf**  
- $20 USD mensuales  
- 500 min, 50 SMS, 15 GB  
- Excesos: 3¢/min, 3¢/SMS, $10/GB  

**Ultimate**  
- $70 USD mensuales  
- 3000 min, 1000 SMS, 30 GB  
- Excesos: 1¢/min, 1¢/SMS, $7/GB  

---

## 📁 Diccionario de Datos

**users**  
- `user_id`, `first_name`, `last_name`, `age`, `reg_date`, `churn_date`, `city`, `plan`

**calls**  
- `id`, `call_date`, `duration`, `user_id`

**messages**  
- `id`, `message_date`, `user_id`

**internet**  
- `id`, `mb_used`, `session_date`, `user_id`

**plans**  
- `plan_name`, `usd_monthly_fee`, `minutes_included`, `messages_included`, `mb_per_month_included`, `usd_per_minute`, `usd_per_message`, `usd_per_gb`

---

##  Instrucciones para completar el proyecto

### Paso 1: Explora los datos
Carga los datasets desde la carpeta `/datasets/` y examina su estructura general.

### Paso 2: Prepara los datos
- Corrige tipos de datos  
- Encuentra y corrige errores  
- Calcula por usuario:
  - Minutos y llamadas por mes  
  - SMS por mes  
  - Datos mensuales  
  - Ingresos mensuales

### Paso 3: Analiza los datos
- Describe comportamiento por tarifa  
- Calcula media, varianza, desviación estándar  
- Grafica histogramas  
- Describe las distribuciones

### Paso 4: Prueba de hipótesis
- Compara ingresos entre tarifas Surf y Ultimate  
- Compara ingresos entre Nueva York-Nueva Jersey y otras regiones  
- Define hipótesis nula y alternativa  
- Explica criterios y nivel de significancia

### Paso 5: Conclusión
Resume el análisis y explica las recomendaciones para el área comercial de Megaline.

