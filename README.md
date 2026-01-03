# Big Data Analytics – Chicago Crime Incidents

Proyecto académico de **Analítica Big Data y Modelamiento Predictivo** desarrollado en Apache Spark, aplicado a un dataset real de incidentes criminales de la ciudad de Chicago (2001–Presente), con más de **8.4 millones de registros**.

## 🧠 Contexto
Las instituciones públicas enfrentan grandes desafíos al analizar volúmenes masivos de datos históricos.  
Este proyecto aborda un escenario de **seguridad pública**, donde se requiere transformar registros criminales en información útil para la toma de decisiones, planificación de recursos y focalización territorial.

## 🎯 Objetivos del proyecto
- Construir una **vista minable** eficiente y escalable.
- Implementar un flujo completo de **Big Data con Apache Spark**.
- Aplicar modelos de:
  - Clasificación
  - Regresión
  - Clustering
- Evaluar resultados con métricas estándar y enfoque institucional.

## 📊 Dataset
- Fuente: Chicago Crime Incidents (Kaggle)
- Volumen: +8.4 millones de registros
- Periodo: 2001 – Presente
- Variables temporales, geográficas y administrativas

## ⚙️ Tecnologías utilizadas
- Apache Spark (PySpark)
- Google Colab
- Spark MLlib
- Parquet (almacenamiento columnar)
- Python

## 🔄 Pipeline Big Data
1. Limpieza y estandarización de columnas
2. Conversión robusta de fechas
3. Creación de variables temporales (año, mes, hora, día)
4. Deduplicación de registros
5. Persistencia en Parquet particionado por año

## 🤖 Modelos implementados

### 1. Clasificación – Regresión Logística
- Objetivo: Estimar la probabilidad de arresto
- Métricas destacadas:
  - AUC ≈ 0.90
  - F1-Score ≈ 0.87

### 2. Regresión – GBTRegressor
- Objetivo: Estimar volumen de incidentes por distrito y mes
- Uso: Planificación de recursos

### 3. Clustering – K-Means
- Segmentación espacio-temporal
- Coeficiente de silueta > 0.56

## 📄 Documentación
- Informe completo en PDF disponible en la carpeta `docs/`
- Notebook reproducible en `notebook/`

## ⚠️ Consideraciones éticas
Los modelos desarrollados sirven como **apoyo analítico** y no como automatización de decisiones legales o policiales. Los resultados reflejan patrones históricos que pueden contener sesgos institucionales.

## 👤 Autor
**Matías Madrid Rojas**  
Ingeniería en Informática – Big Data & Desarrollo de Sistemas
