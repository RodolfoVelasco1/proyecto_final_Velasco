# 🏠 Predicción de Precios de Viviendas en California

**Alumno:** Rodolfo Velasco

Proyecto de Machine Learning para la predicción automatizada de valores inmobiliarios utilizando el dataset California Housing.

---

## 📋 Descripción del Proyecto

Este proyecto desarrolla un modelo de machine learning capaz de predecir el valor medio de viviendas en California basándose en características observables del distrito. El modelo automatiza el proceso de tasación inmobiliaria, tradicionalmente manual y costoso, proporcionando valoraciones rápidas, objetivas y basadas en datos.

### Problema de Negocio

La valoración de propiedades inmobiliarias es un proceso complejo que requiere:

- Tiempo considerable de análisis
- Experiencia especializada de tasadores
- Costos operativos elevados

Este proyecto ofrece una **solución automatizada** que estima valores de mercado con alta precisión, sirviendo como herramienta de apoyo para profesionales del sector inmobiliario.

---

## 🎯 Objetivos

- **Construir un modelo predictivo** de alto rendimiento para estimar el `median_house_value`
- **Identificar los factores clave** que determinan el precio de las viviendas
- **Proporcionar una herramienta práctica** para stakeholders del sector inmobiliario

---

## 📊 Dataset

**Fuente:** California Housing Dataset (Censo 1990)

**Dataset bajado de Kaggle:** https://www.kaggle.com/datasets/camnugent/california-housing-prices

### Variables Principales

| Variable | Descripción |
|----------|-------------|
| `longitude` / `latitude` | Coordenadas geográficas del distrito |
| `housing_median_age` | Antigüedad media de las viviendas |
| `total_rooms` / `total_bedrooms` | Total de habitaciones/dormitorios en el distrito |
| `population` / `households` | Población y número de hogares |
| `median_income` | Ingreso medio del distrito (en decenas de miles) |
| `ocean_proximity` | Proximidad al océano (categórica) |
| `median_house_value` | **Variable objetivo** - Valor medio de la vivienda |

### Calidad de Datos

- **Tamaño:** 20,640 registros
- **Valores faltantes:** 207 registros (~1%) en `total_bedrooms` - imputados con la mediana
- **Limitación identificada:** Cap artificial en $500,001 para valores altos

---

## 💼 Aplicaciones Prácticas

### Stakeholders

- **Empresas de inversión inmobiliaria** - Identificación de oportunidades
- **Bancos y entidades hipotecarias** - Gestión de riesgo crediticio
- **Desarrolladores inmobiliarios** - Decisiones de construcción

### Casos de Uso

1. **Tasación automatizada** - Primera valoración o segunda opinión
2. **Análisis de mercado** - Identificación de propiedades subvaloradas/sobrevaloradas
3. **Estrategia de inversión** - Detección de zonas con alto potencial
4. **Asesoramiento inmobiliario** - Herramienta de apoyo para agentes

---

## 📁 Estructura del Repositorio

```
├── notebook.ipynb                 # Análisis completo y modelado
├── Informe Ejecutivo.pdf          # Documento técnico detallado
├── data/
│   ├── housing.csv                # Dataset original
│   └── processed/                 # Datos procesados
├── models/
│   └── random_forest_model.pkl    # Modelo entrenado
├── visualizations/                # Gráficos del análisis exploratorio
└── README.md                      # Este archivo
```

---

## 🛠️ Tecnologías Utilizadas

- **Python 3.x**
- **Pandas** - Manipulación de datos
- **NumPy** - Operaciones numéricas
- **Scikit-learn** - Modelado y evaluación
- **Matplotlib / Seaborn** - Visualización

---

## 🔍 Notebook

Accede al notebook completo en Google Colab:

**https://colab.research.google.com/drive/1E-TXn4wMLzILJzsZ0KPAvOrwjYTitTAb?usp=sharing**

---

## 👤 Autor

**Rodolfo Nicolás Velasco Fessler**