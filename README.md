# Análisis de Fuga de Clientes - Proyecto de Grado II

## Descripción del Proyecto

Este proyecto implementa un análisis avanzado de fuga de clientes utilizando técnicas de machine learning y análisis de variables fantasma (Ghost Variables). El objetivo es identificar y predecir qué clientes tienen mayor probabilidad de abandonar los servicios de una entidad financiera.

## Características Principales

- **Análisis de Variables Fantasma**: Implementación de técnicas avanzadas para evaluar la relevancia de variables
- **Machine Learning**: Uso de Random Forest y otros algoritmos para predicción
- **Análisis Exploratorio de Datos (EDA)**: Visualizaciones y análisis estadísticos completos
- **Preprocesamiento de Datos**: Pipeline completo de limpieza y transformación de datos
- **Evaluación de Modelos**: Métricas y validaciones exhaustivas

## Estructura del Proyecto

```
fuga-clientes-bc-v2-ghost-v/
├── Data/                           # Datos originales y procesados
│   ├── Base_Fuga_24.xlsx
│   ├── Base_Fuga_24.xlsx (Converted - 2025-04-22 09_32).xlsx
│   └── Base_Fuga_24.xlsx (Converted - 2025-04-22 09_32)(1).xlsx
├── Images/                         # Visualizaciones generadas
│   ├── Categorical_correlation.png
│   ├── Complete_correlation.png
│   ├── Continuous_correlation.png
│   └── target_correlation.png
├── cat_importances/                # Importancias de variables categóricas
│   └── cat_importances_rf_eda.pkl
├── num_importances/                # Importancias de variables numéricas
│   └── num_importances_rf_eda.pkl
├── ghost_analysis_data/            # Resultados del análisis de variables fantasma
│   └── ghost_variable_analysis_results.pkl
├── proyecto-grado-fuga-clientes-bc-gv-analitics.ipynb    # Notebook principal de análisis
├── proyecto-grado-fuga-clientes-bc-gv-code-base.ipynb    # Base de código
└── proyecto-grado-II-fuga-clientes-bc.ipynb              # Notebook inicial
```

## Notebooks Principales

### 1. `proyecto-grado-fuga-clientes-bc-gv-analitics.ipynb`
Notebook principal que contiene:
- Análisis exploratorio de datos (EDA)
- Implementación de variables fantasma
- Comparación de modelos (Random Forest vs Ghost Variables)
- Visualizaciones avanzadas
- Análisis de correlaciones y relevancia de variables

### 2. `proyecto-grado-fuga-clientes-bc-gv-code-base.ipynb`
Base de código con:
- Clases y transformadores personalizados
- Pipeline de preprocesamiento
- Funciones de utilidad

### 3. `proyecto-grado-II-fuga-clientes-bc.ipynb`
Notebook inicial con:
- Carga y exploración inicial de datos
- Primeros análisis estadísticos

## Datos Incluidos

El repositorio incluye todos los archivos de datos necesarios para reproducir el análisis:

- **Datos originales**: `Data/Base_Fuga_24.xlsx` y versiones convertidas
- **Resultados de análisis**: Archivos pickle con importancias de variables y resultados de variables fantasma
- **Visualizaciones**: Gráficos de correlaciones y análisis

## Tecnologías Utilizadas

- **Python 3.x**
- **Pandas**: Manipulación y análisis de datos
- **NumPy**: Computación numérica
- **Scikit-learn**: Machine learning y preprocesamiento
- **Matplotlib/Seaborn**: Visualizaciones
- **XGBoost**: Algoritmos de boosting
- **Joblib**: Serialización de modelos

## Instalación y Uso

### Requisitos Previos
```bash
pip install -r requirements.txt
```

### Ejecución
1. Clona este repositorio
2. Navega al directorio del proyecto
3. Instala las dependencias: `pip install -r requirements.txt`
4. Abre los notebooks en Jupyter o Google Colab
5. Ejecuta las celdas en orden

## Resultados Principales

El proyecto genera:
- **Análisis de correlaciones** entre variables
- **Importancia de variables** según diferentes métodos
- **Comparación de modelos** de predicción
- **Visualizaciones** de patrones de fuga
- **Recomendaciones** para retención de clientes

## Contribuciones

Este es un proyecto académico desarrollado como parte del Proyecto de Grado II en la Maestría en Ciencia de Datos.

## Licencia

Este proyecto es de uso académico y educativo.

## Contacto

Para más información sobre este proyecto, contacta a los desarrolladores del proyecto de grado. 