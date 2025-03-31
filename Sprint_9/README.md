# 🔗 Proyecto Sprint 9: Aprendizaje Supervisado

**"Predecir si un cliente o una clienta abandonará en poco tiempo el banco para ayudar al negocio a retener a la clientela existente."**

Este proyecto se enfoca en profundizar en modelos de clasificación. Se aplicó un modelo de **árbol de clasificación**, logrando un puntaje **F1 de 0.90**. También se exploraron las curvas **Precision-Recall**, **ROC-AUC**, y diferentes métodos para corregir el **desbalance de clases**, mejorando la precisión y sensibilidad del modelo.

## Skills 🛠:
- 🐍 Python  
- 🔍 Procesamiento de datos  
- 🧠 Modelos de clasificación  
- 🗄 SQL  

---

## Descripción del proyecto

Beta Bank está enfrentando la pérdida gradual de clientes. Dado que retener a un cliente existente es más rentable que adquirir uno nuevo, el objetivo es **predecir con antelación qué clientes podrían abandonar el banco**, basándose en su comportamiento histórico.

Para ello, se entrenaron y compararon diferentes modelos, evaluando su desempeño con métricas como **F1-score** y **AUC-ROC**, y aplicando técnicas para balancear las clases.

---

## Instrucciones del proyecto

- Descargar y preparar los datos desde: `/datasets/Churn.csv`
- Analizar el desbalance de clases
- Entrenar modelos sin y con técnicas de balanceo (submuestreo, sobremuestreo, etc.)
- Ajustar hiperparámetros y evaluar modelos usando validación cruzada
- Escoger el mejor modelo y validar su rendimiento con el conjunto de prueba
- Comparar métricas F1 vs AUC-ROC y justificar la elección final

---

## 🗂️ Descripción de los datos

Cada fila representa información sobre un cliente y su historial en el banco. Las variables incluidas son:

- `RowNumber`: índice de fila  
- `CustomerId`: identificador único del cliente  
- `Surname`: apellido  
- `CreditScore`: puntaje de crédito  
- `Geography`: país de residencia  
- `Gender`: género  
- `Age`: edad  
- `Tenure`: años como cliente  
- `Balance`: saldo de cuenta  
- `NumOfProducts`: número de productos contratados  
- `HasCrCard`: tiene tarjeta de crédito (1 = sí, 0 = no)  
- `IsActiveMember`: es miembro activo (1 = sí, 0 = no)  
- `EstimatedSalary`: salario estimado  

**Variable objetivo:**

- `Exited`: indica si el cliente abandonó el banco (1 = sí, 0 = no)
