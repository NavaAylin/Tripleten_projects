# 🔗 Proyecto Sprint 14: Aprendizaje automático para textos – Clasificación de reseñas de IMDB

Este proyecto se centra en el procesamiento de lenguaje natural (NLP) para **entrenar un modelo capaz de clasificar automáticamente reseñas de películas como positivas o negativas**. A través de herramientas como `SpaCy`, `NLTK`, `TF-IDF` se exploran diferentes enfoques para vectorizar texto y alimentar modelos de clasificación con un objetivo mínimo de F1-score ≥ 0.85.

## Skills 🛠:
- 🤖 Fundamentos de ML  
- 🧠 ML avanzado  
- 🧾 Modelos de clasificación  
- 🗣️ Procesamiento de lenguaje natural (NLP)

---

## Descripción del proyecto

La comunidad **Film Junky Union** está desarrollando un sistema que permita **clasificar automáticamente reseñas de películas**. Utilizando un conjunto de reseñas de IMDB con etiquetado binario, se busca entrenar modelos que logren detectar críticas negativas con alta precisión, facilitando la moderación de contenido.

Las tareas principales incluyen:

- Limpieza, normalización y análisis exploratorio de texto
- Creación del corpus de reseñas y preprocesamiento lingüístico
- Vectorización mediante diferentes técnicas
- Entrenamiento y evaluación de múltiples modelos
- Comparación de métricas y ajuste de hiperparámetros para alcanzar un F1 ≥ 0.85

---

## Instrucciones del proyecto

1. Cargar los datos desde: `/datasets/imdb_reviews.tsv`
2. Realizar limpieza y corrección del texto
3. Analizar distribución y longitud de las reseñas
4. Procesar el texto con herramientas NLP (SpaCy, NLTK)
5. Aplicar vectorización
6. Entrenar y comparar al menos 11 modelos de clasificación:
   - Regresión logística, SVM, Árboles, Bosques, Gradient Boosting, etc.
7. Evaluar con F1-score, matriz de confusión y curva ROC
8. Seleccionar el modelo con mejor rendimiento (mínimo F1 ≥ 0.85)

---

## 🗂️ Descripción de los datos

**Archivo:** `/datasets/imdb_reviews.tsv`

Conjunto de datos etiquetado con reseñas de películas provenientes de IMDB. Incluye:

- `review`: texto de la reseña  
- `pos`: etiqueta de sentimiento (0 = negativo, 1 = positivo)  
- `ds_part`: indica si la observación es parte del conjunto de entrenamiento o prueba

---
