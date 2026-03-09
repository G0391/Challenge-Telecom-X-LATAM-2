# Proyecto Challenge Telecom X - Parte 2

## Descripción del Proyecto

Este proyecto forma parte del desafío de **Telecom X**, donde el objetivo principal es predecir la probabilidad de que un cliente cancele sus servicios (*Churn*). Mediante el uso de modelos de Machine Learning, buscamos identificar patrones críticos y proponer estrategias de retención basadas en datos para reducir la pérdida de ingresos de la compañía.

## Objetivos de la Misión

- **Preprocesamiento**: Limpieza de datos, codificación de variables categóricas (One-Hot Encoding) y tratamiento de valores nulos.
- **Balanceo de Clases**: Implementación de la técnica **SMOTE** para equilibrar el dataset y mejorar la detección de la clase minoritaria.
- **Modelado**: Entrenamiento y comparación de **Regresión Logística** y **Random Forest**.
- **Evaluación**: Análisis de métricas de desempeño (Accuracy, Precision, Recall y F1-Score) y matrices de confusión.
- **Insights**: Identificación de las variables con mayor impacto en la cancelación.

## Herramientas Utilizadas

- **Lenguaje**: Python
- **Librerías**: Pandas, NumPy, Scikit-Learn, Imbalanced-learn (SMOTE)
- **Visualización**: Matplotlib, Seaborn
- **Entorno**: Google Colab

## Metodología y Pipeline

1. **EDA & Limpieza**: Eliminación de identificadores únicos y análisis de correlación inicial.
2. **Feature Engineering**: Normalización con **StandardScaler** y encoding de categorías.
3. **Manejo de Desbalanceo**: Aplicación de **SMOTE** para lograr una distribución 50/50 en el set de entrenamiento.
4. **Entrenamiento**:
   - **Regresión Logística**: Modelo base para interpretación de coeficientes.
   - **Random Forest**: Modelo de ensamble para capturar relaciones no lineales.
5. **Evaluación Crítica**: Foco en la métrica **Recall** para minimizar los falsos negativos.

## Resultados y Conclusiones

Tras el análisis, se determinó que el modelo **[Nombre de tu modelo ganador]** fue el más efectivo.

### Factores Críticos Identificados

- **Tenure**: Los clientes con menos de 12 meses de antigüedad presentan el mayor riesgo.
- **Contrato**: Los contratos mes a mes son los principales impulsores de la fuga.
- **Servicios**: Clientes con fibra óptica muestran patrones de abandono que requieren atención técnica o comercial.

## Estrategias de Retención Propuestas

- Incentivar el paso de contratos mensuales a anuales.
- Reforzar el servicio de soporte técnico en clientes de fibra óptica.
- Implementar programas de fidelización durante el primer año de vida del cliente.

Estrategias de Retención Propuestas
Incentivar el paso de contratos mensuales a anuales.

Reforzar el servicio de soporte técnico en clientes de fibra óptica.

Implementar programas de fidelización durante el primer año de vida del cliente.
