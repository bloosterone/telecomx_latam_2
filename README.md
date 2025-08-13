📊 Predicción de Cancelación de Clientes (Churn) – Versión 2

Este proyecto busca predecir qué clientes de Telecom X tienen mayor probabilidad de cancelar su servicio, utilizando técnicas de machine learning y análisis de variables relevantes.
🔍 Objetivo

Desarrollar modelos predictivos que permitan anticipar la cancelación de clientes y generar estrategias efectivas de retención basadas en datos.
🧹 Pasos realizados

    Preprocesamiento de datos: limpieza, codificación de variables categóricas y manejo de valores faltantes

    Verificación y balanceo de clases (churn)

    Análisis exploratorio y correlación de variables

    Modelado predictivo utilizando:

        Regresión Logística (con normalización)

        Random Forest (sin normalización)

    Evaluación de modelos con métricas: exactitud, precision, recall, F1-score, ROC-AUC

    Análisis de importancia de variables para identificar los factores que más influyen en la cancelación

    Generación de insights y recomendaciones estratégicas

📁 Contenido

    TelecomX_LATAM(2).ipynb: análisis completo paso a paso

    README.md: este archivo

🚀 Herramientas

    Python

    Pandas

    Scikit-learn

    Matplotlib / Seaborn

🧠 Conclusión

    El modelo Random Forest mostró el mejor desempeño, con ROC-AUC de 0.80 y un equilibrio adecuado entre precisión y recall.

    Las variables más importantes que influyen en la cancelación son: tenure, tipo de contract, charges.total, techsupport, onlinesecurity, entre otras.

    Estrategias recomendadas incluyen promover contratos largos, incentivar servicios de valor agregado, y generar campañas personalizadas para clientes con menor gasto o con contratos recientes.
