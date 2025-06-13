# Análisis de Rotación de Clientes de Telecomunicaciones

Este proyecto analiza un conjunto de datos de clientes de una empresa de telecomunicaciones para entender los factores que influyen en la rotación de clientes (churn).

## Descripción

El análisis se enfoca en identificar patrones y características que puedan predecir cuándo un cliente es propenso a abandonar los servicios de la empresa. Utilizamos técnicas de análisis exploratorio de datos y visualización para extraer insights valiosos.

## Conjunto de datos

El conjunto de datos utilizado (`WA_Fn-UseC_-Telco-Customer-Churn.csv`) contiene información sobre:

- Datos demográficos de clientes (género, si tienen pareja o dependientes)
- Servicios contratados (telefonía, internet, seguridad online, etc.)
- Información de cuenta (duración del contrato, método de pago, facturación)
- Métricas financieras (cargos mensuales, cargos totales)
- Estado de rotación (si el cliente abandonó la empresa)

## Funcionalidades implementadas

- Limpieza y preparación de datos
  - Eliminación de duplicados
  - Corrección de tipos de datos
  - Normalización de valores categóricos
  - Tratamiento de valores faltantes

- Análisis exploratorio
  - Visualización univariada (distribución de variables individuales)
  - Visualización multivariada (relaciones entre variables)
  - Análisis de correlación

## Tecnologías utilizadas

- Python
- Pandas para manipulación de datos
- NumPy para operaciones numéricas
- Matplotlib y Seaborn para visualizaciones

## Resultados preliminares

El análisis muestra que factores como la duración del contrato (tenure) tienen una fuerte relación con la probabilidad de rotación de los clientes.

## Próximos pasos

- Implementar modelos predictivos de machine learning
- Realizar análisis de segmentación de clientes
- Generar recomendaciones para reducir la tasa de rotación

## Cómo ejecutar

El análisis completo se encuentra en el notebook `rotacion_clientes_telecom.ipynb`. Para ejecutarlo:

1. Asegúrate de tener todas las dependencias instaladas
2. Coloca el archivo de datos en el mismo directorio
3. Ejecuta el notebook en Jupyter o VS Code

