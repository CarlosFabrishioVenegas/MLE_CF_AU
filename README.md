# **🧠 Machine Learning Engineering | MLOps | Data Automation**
Este repositorio reúne distintos proyectos, notebooks y utilidades desarrolladas en el contexto de Machine Learning Engineering (MLE), automatización de procesos y análisis de datos aplicados al negocio.
El foco está en construir soluciones reproducibles, escalables y explicables, que cubren todo el ciclo de vida del modelo: desde la exploración de datos hasta el despliegue y monitoreo en producción.
-----
El contenido está organizado según las principales fases de trabajo en MLE:

Data Understanding & Feature Engineering
- Limpieza, codificación y transformación de datos con pandas y NumPy.
- Creación de variables derivadas, categorizaciones y manejo de desbalanceo con SMOTE.
- Análisis de correlación, multicolinealidad y selección automática de features.

Modelado Predictivo

- Entrenamiento de modelos de clasificación y regresión (Logistic, Ridge, Random Forest, XGBoost, etc.).
- Evaluación con métricas técnicas (AUC, Recall, KS, Precision) y métricas de negocio.
- Optimización de umbrales para reducir pérdidas financieras o mejorar retención.

Interpretabilidad & Explainability

- Análisis con SHAP Values para explicar decisiones de modelos lineales y no lineales.
- Identificación de factores que influyen en el churn o deserción de clientes, incluso en segmentos de alto valor.

MLOps & Entornos reproducibles

- Configuración de entornos virtuales (venv, conda) y Dockerfiles para portabilidad.
- Control de versiones con Git y seguimiento de modelos mediante MLflow.
- Integración de pruebas unitarias y validaciones de datos (pytest, great_expectations).

Despliegue y Automatización

- Exposición de modelos mediante FastAPI.
- Automatización de flujos ETL con Airflow o Power Automate.
- Integración con dashboards analíticos en Power BI, Streamlit o Dash.
