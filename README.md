# Challenge-TelecomX
# Análisis de Evasión de Clientes: Telecom X

Este proyecto analiza los datos de la empresa **Telecom X** para identificar los factores que influyen en la cancelación de servicios (*Churn*). Es parte de la formacion **Aprendiendo a hacer ETL** El objetivo es transformar datos crudos provenientes de una API en información estratégica para reducir la pérdida de clientes.

## Desafío del Proyecto
Telecom X enfrenta una alta tasa de cancelaciones. Como analista, mi labor fue realizar un proceso **ETL** completo:
1. **Extracción:** Obtención de datos en formato JSON desde una API.
2. **Transformación:** Limpieza de valores nulos, eliminación de duplicados y corrección de tipos de datos.
3. **Carga y Análisis:** Creación de visualizaciones para detectar patrones de abandono.

## Tecnologías Utilizadas
* **Python 3.x**
* **Pandas:** Para la manipulación de DataFrames.
* **Requests:** Para el consumo de la API.
* **Matplotlib & Seaborn:** Para el análisis exploratorio visual.

##  Hallazgos Principales (Insights)
Tras el análisis exploratorio (EDA), se identificaron los siguientes patrones críticos:
* **Tipo de Contrato:** Los clientes con contrato **mes a mes** tienen la tasa de evasión más alta.
* **Cargos Mensuales:** Existe una correlación entre cargos mensuales elevados y la decisión de cancelar el servicio.
* **Servicios de Internet:** Ciertos tipos de conexión presentan mayor inestabilidad percibida por el usuario.
   ```bash
   pip install pandas requests matplotlib seaborn
