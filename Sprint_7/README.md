# 🔗 Proyecto Sprint 7: Recopilación y almacenamiento de datos (SQL)

"Analizar datos de competidores y probar una hipótesis sobre el impacto de factores externos para una compañía para compartir vehículos."

Este proyecto combina múltiples pasos y tecnologías:

- Web scraping a una página dummy para obtener información.
- Consultas en SQL para filtrar los datos requeridos.
- Análisis exploratorio y estadístico con Python.

## Skills 🛠:
🧹 Procesamiento de datos  |  🐘 SQL  |  🐍 Python  |  📊 Análisis estadístico

---

### 📝 Descripción del proyecto

Como analista en Zuber, una nueva empresa de viajes compartidos en Chicago, tu objetivo es encontrar patrones relevantes en la información disponible. Se busca comprender las preferencias de los usuarios y el impacto de factores externos, como el clima, sobre la frecuencia de los viajes.

Para esto, analizas los datos de los competidores y pruebas una hipótesis sobre el impacto de los sábados lluviosos en la duración de los viajes desde el Loop hasta el Aeropuerto O'Hare.

---

### 📚 Descripción de los datos

La base de datos se compone de 4 tablas principales:

- **neighborhoods**: nombre y código de barrios de Chicago.
- **cabs**: información de los taxis (código, empresa, ID de vehículo).
- **trips**: detalles de cada viaje (origen, destino, duración, distancia, fechas).
- **weather_records**: condiciones climáticas (temperatura y descripción por hora).

---

### Instrucciones del proyecto

#### Paso 1: Web scraping
- Recolectar datos climáticos de noviembre 2017 desde: `https://practicum-content.s3.us-west-1.amazonaws.com/data-analyst-eng/moved_chicago_weather_2017.html`

#### Paso 2: Consultas SQL
- Consultas para analizar viajes por empresa y fechas específicas.
- Agrupaciones por empresas populares (e.g. Flash Cab) y otras.
- Agrupar por condiciones meteorológicas con CASE.

#### Paso 3: Datos de viajes relevantes
- Filtrar viajes desde el Loop hasta O'Hare (IDs: 50 → 63) en sábados.
- Vincular datos meteorológicos para pruebas estadísticas.

#### Paso 4: Análisis con Python
- Cargar y explorar archivos `project_sql_result_01.csv` y `project_sql_result_04.csv`.
- Visualizaciones: empresas vs. viajes, barrios más populares.
- Conclusiones de cada gráfico generado.

#### Paso 5: Prueba de hipótesis
- Usar `project_sql_result_07.csv` con viajes y condiciones climáticas.
- Hipótesis:
  - **H₀**: No hay diferencia en duración de viajes según clima.
  - **H₁**: Hay diferencia significativa en duración en sábados lluviosos.
- Establecer valor de α.
- Justificar elección de prueba estadística.

---
