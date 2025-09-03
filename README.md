# 📈 Predicción de Bancarrota Empresarial
### Análisis predictivo basado en indicadores contables de empresas NYSE

---

## 👤 Autores

Sofía Villamizar
Sofía Angulo
Gabriela Zamora
Gilberto Galeana
Nicolas Rich
Juan Sebatian Sierra
Samuel Suárez

---

## 🎯 Descripción del Proyecto

Este proyecto desarrolla y compara modelos de machine learning para **predecir la probabilidad de bancarrota empresarial** utilizando indicadores financieros y contables. A través del análisis de datos históricos de empresas cotizadas en la Bolsa de Nueva York, buscamos identificar patrones que permitan anticipar situaciones de insolvencia financiera.

### ¿Por qué es importante?
- **Para inversores**: Evaluar el riesgo de sus inversiones
- **Para instituciones financieras**: Mejorar la evaluación crediticia
- **Para empresas**: Identificar señales tempranas de problemas financieros
- **Para reguladores**: Monitorear la salud del sistema financiero

---

## 📊 Dataset

### Características principales
- **Fuente**: Empresas cotizadas en NYSE (New York Stock Exchange)
- **Período**: 1999-2011 (12 años de datos históricos)
- **Tamaño**: 78,682
- **Variables**: Indicadores contables y financieros clave
- **Variable objetivo**: Estado de bancarrota (binaria)

### Definición de bancarrota
Seguimos la definición oficial de la **Comisión de Bolsa y Valores (SEC)**: una empresa se considera en bancarrota cuando no puede cumplir con sus obligaciones de deuda, lo que puede resultar en:
- Reorganización empresarial bajo protección legal
- Liquidación total de activos para pago a acreedores

**Fuente de datos**: [Kaggle - American Companies Bankruptcy Prediction Dataset](https://www.kaggle.com/datasets/utkarshx27/american-companies-bankruptcy-prediction-dataset?resource=download)

---

## 🚀 Modelos Implementados

Comparamos el rendimiento de tres algoritmos de clasificación ampliamente utilizados en predicción financiera:

| Modelo | Descripción | Ventajas |
|--------|-------------|----------|
| **Random Forest** | Ensemble de árboles de decisión | Robusto, maneja bien variables correlacionadas |
| **SVM** | Máquinas de soporte vectorial | Efectivo en espacios de alta dimensión |
| **Regresión Logística** | Modelo lineal probabilístico | Interpretable, baseline sólido |

---

## 🔬 Metodología

Cada notebook incluye un flujo de trabajo completo:

1. **📋 Introducción teórica** del algoritmo
2. **🔄 Carga y preprocesamiento** de datos
3. **✂️ División** train/validation/test
4. **⚙️ Optimización de hiperparámetros** (Grid Search/Random Search)
5. **📊 Evaluación** con métricas relevantes:
   - Accuracy, Precision, Recall, F1-Score
   - AUC-ROC y AUC-PR
   - Matriz de confusión
   - Análisis de importancia de características

---

## 🏆 Resultados Principales

| Modelo | Accuracy | Precision | Recall | F1-Score | AUC-ROC |
|--------|----------|-----------|---------|----------|---------|
| Random Forest | - | - | - | - | - |
| SVM | - | - | - | - | - |
| Regresión Logística | - | - | - | - | - |

*Los resultados detallados se encuentran en el notebook de comparación.*

---

## 🛠️ Instalación y Uso

### Prerrequisitos
```bash
Python 3.8+
pip o conda para gestión de paquetes
```

### Instalación
```bash
# Clonar el repositorio
git clone https://github.com/[tu-usuario]/bankruptcy-prediction.git
cd bankruptcy-prediction

# Ejecutar notebooks
jupyter lab
```

---

