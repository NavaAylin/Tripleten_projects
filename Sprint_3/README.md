# 🔗 Proyecto del Sprint 3: Manipulación de Datos (Data Wrangling)

**Objetivo del proyecto:**  
Preparar un informe con visualizaciones que brinden información sobre los hábitos de compra de los clientes de una plataforma de entrega de comestibles.

Este proyecto pone a prueba las capacidades de manipulación de `DataFrames` para obtener datos más relevantes para el análisis.

---
## Skills 🛠:
- 🧹 Preprocesamiento de datos  
- 📊 Análisis exploratorio  
- 📈 Explicación e interpretación de datos  
- 📉 Análisis estadístico  

---

## Diccionario de Datos

### 📦 instacart_orders.csv  
Pedidos en la app Instacart  
- `order_id`: ID del pedido  
- `user_id`: ID del cliente  
- `order_number`: Número de pedido del cliente  
- `order_dow`: Día de la semana (0 = domingo)  
- `order_hour_of_day`: Hora del pedido  
- `days_since_prior_order`: Días desde el último pedido

### 🛒 products.csv  
- `product_id`: ID del producto  
- `product_name`: Nombre del producto  
- `aisle_id`: ID del pasillo  
- `department_id`: ID del departamento

### 📑 order_products.csv  
Artículos por pedido  
- `order_id`: ID del pedido  
- `product_id`: ID del producto  
- `add_to_cart_order`: Orden en que se añadió al carrito  
- `reordered`: 0 = nuevo, 1 = repetido

### 🧾 aisles.csv  
- `aisle_id`: ID del pasillo  
- `aisle`: Nombre del pasillo

### 🗂 departments.csv  
- `department_id`: ID del departamento  
- `department`: Nombre del departamento

---

## 📋 Instrucciones para completar el proyecto

### Paso 1: Exploración Inicial  
- Revisa los CSV con `pd.read_csv()` ajustando argumentos necesarios.  
- Usa `info(show_counts=True)` para ver los nulos si hay muchas filas.

### Paso 2: Preprocesamiento  
- Corrige tipos de datos  
- Detecta y completa valores ausentes  
- Elimina duplicados y justifica las decisiones

### Paso 3: Análisis

#### [A]  
- Verifica rangos de `order_hour_of_day` (0–23) y `order_dow` (0–6)  
- Gráfico de pedidos por hora  
- Gráfico de compras por día de la semana  
- Distribución del tiempo entre pedidos

#### [B]  
- Comparación de horas de pedido entre miércoles y sábado  
- Distribución del número de pedidos por cliente  
- Top 20 productos más pedidos

#### [C]  
- Artículos promedio por pedido  
- Top 20 productos más reordenados  
- Tabla con proporción de reordenado por producto  
- Proporción de reordenado por cliente  
- Top 20 productos añadidos primero al carrito

