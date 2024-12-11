# -Beta_Bank_project9
Beta Bank Customer Churn Prediction
Descripción del Proyecto
Beta Bank enfrenta la pérdida progresiva de sus clientes. Para abordar este desafío, hemos desarrollado un modelo predictivo que identifica si un cliente tiene probabilidades de dejar el banco próximamente. Este enfoque ayudará a implementar estrategias proactivas para retener clientes, lo que resulta más rentable que atraer nuevos.

El objetivo principal del proyecto es construir un modelo con un valor F1 de al menos 0.59 para el conjunto de prueba. Además, evaluaremos la métrica AUC-ROC y la compararemos con el valor F1.

Estructura del Proyecto
Preparación de Datos

Carga y análisis del conjunto de datos: /datasets/Churn.csv.
Procesamiento y limpieza de datos, incluyendo tratamiento de valores faltantes, codificación de variables categóricas y normalización.
Análisis del Desequilibrio de Clases

Exploración inicial del conjunto de datos para determinar la distribución de la variable objetivo (Exited).
Entrenamiento preliminar de modelos sin tratar el desequilibrio.
Mejoras del Modelo

Implementación de al menos dos enfoques para manejar el desequilibrio de clases, como:
Sobremuestreo de la clase minoritaria.
Submuestreo de la clase mayoritaria.
Uso de técnicas avanzadas como SMOTE o cambio de ponderaciones en las clases.
Validación de los modelos y optimización de hiperparámetros utilizando técnicas como búsqueda de cuadrícula.
Evaluación Final

Evaluación del modelo con el conjunto de prueba.
Comparación de las métricas F1 y AUC-ROC.
Descripción de los Datos
El conjunto de datos contiene información sobre el comportamiento y las características de los clientes del banco, además de la etiqueta que indica si dejaron el banco.

Características:

RowNumber: índice de datos.
CustomerId: identificador único de cliente.
Surname: apellido del cliente.
CreditScore: puntuación de crédito.
Geography: país de residencia.
Gender: sexo del cliente.
Age: edad.
Tenure: período de depósito a plazo fijo (años).
Balance: saldo de la cuenta.
NumOfProducts: número de productos bancarios utilizados.
HasCrCard: si el cliente tiene tarjeta de crédito (1: sí, 0: no).
IsActiveMember: si el cliente es miembro activo (1: sí, 0: no).
EstimatedSalary: salario estimado.
Objetivo:

Exited: el cliente se ha ido (1: sí, 0: no).
Evaluación del Proyecto
Para evaluar el éxito del proyecto, se consideraron los siguientes aspectos clave:

Preparación adecuada de los datos.
Tratamiento y análisis del desequilibrio de clases.
Entrenamiento de modelos con diferentes estrategias.
Comparación y análisis de métricas clave (F1 y AUC-ROC).
Organización clara y estructura del código.
Resultados Esperados
Un modelo que cumpla o supere el umbral de F1 = 0.59.
Una evaluación detallada del modelo final en términos de métricas clave.
Insights sobre cómo el tratamiento del desequilibrio de clases mejora el rendimiento del modelo.
Herramientas Utilizadas
Lenguaje: Python
Librerías:
Pandas, NumPy (para procesamiento de datos).
Scikit-learn (para entrenamiento y evaluación de modelos).
Matplotlib, Seaborn (para visualización de datos y resultados).