# proyecto-sarlaft-ml
Modelo SARLAFT con Machine Learning: Random Forest, XGBoost, GridSearchCV y SHAP para detección de operaciones financieras de alto riesgo.
# 🧠 Proyecto SARLAFT – Modelo de Detección de Operaciones de Alto Riesgo  
**Machine Learning | Random Forest | XGBoost | GridSearchCV | SHAP | Interpretabilidad**

Este proyecto implementa un sistema de clasificación para identificar operaciones financieras potencialmente riesgosas siguiendo criterios similares al *Sistema de Administración del Riesgo de Lavado de Activos y Financiación del Terrorismo (SARLAFT)*.

Incluye generación de datos, entrenamiento de modelos, optimización, interpretabilidad y evaluación final del desempeño con métricas avanzadas.

---

## 📂 Contenido del Repositorio

- `sarlaft_modelo.ipynb` → Notebook completo del proyecto con código, gráficas y explicaciones.  
- `sarlaft_modelo.ipynb - Colab.pdf` → Versión exportada en PDF (ideal para revisión externa).  

---

## 🎯 Objetivo del Proyecto

Desarrollar un modelo de *Machine Learning* capaz de clasificar transacciones ficticias como:

- **0 = No Riesgo**  
- **1 = Riesgo**

El enfoque incluye:
- Simulación de dataset financiero  
- Preparación y codificación de variables  
- Entrenamiento con **Random Forest**  
- Optimización con **GridSearchCV**  
- Entrenamiento de **XGBoost**  
- **Explicabilidad del modelo con SHAP**  
- Métricas: Accuracy, F1-score, ROC-AUC  

---

# 🚀 Tecnologías Utilizadas

- **Python 3**
- Pandas, NumPy  
- Scikit-learn  
- XGBoost  
- SHAP  
- Matplotlib / Seaborn  

---

# 📊 Principales Resultados

### 🔸 Random Forest  
- Accuracy: **100%**  
- ROC-AUC: **1.00**  
- Matriz de confusión perfecta  
- Variables más importantes:
  - `monto_transaccion`
  - `tipo_transaccion_deposito`
  - `pais_origen_Colombia`

### 🔸 XGBoost  
- Accuracy: **98.4%**  
- ROC-AUC: **1.00**
- Matriz de confusión con mínimo error  
- SHAP muestra que:
  - El monto de la transacción es el principal factor  
  - Tipo de transacción y país de origen también influyen

---

# 🧩 Interpretabilidad del Modelo (SHAP)

El proyecto incluye:

- **SHAP Summary Plot** (importancia global)  
- **SHAP Force Plot** (importancia local por observación)

Esto garantiza que las decisiones del modelo son transparentes y justificables, alineadas con buenas prácticas SARLAFT.

---

# 📈 Curva ROC

Ambos modelos lograron un AUC de **1.00**, lo que indica una separación perfecta entre clases.

---

# 📦 Cómo Ejecutarlo

1. Clonar el repositorio:
```bash
git clone https://github.com/PAOLAALAPA/proyecto-sarlaft-ml.git


------
🟫 Cómo Ejecutarlo

Clonar el repositorio:
git clone https://github.com/PAOLAALAPA/proyecto-sarlaft-ml.git

Instalar dependencias necesarias
pip install pandas numpy scikit-learn xgboost shap matplotlib seaborn

Ejecutar el notebook
sarlaft_modelo.ipynb

Puedes abrirlo en:
Jupyter Notebook
JupyterLab
Google Colab
VS Code con Jupyter

------

🧠 Autora

Paola Andrea Alarcón Pasos
Científica de Datos orientada a Riesgos, Análisis Estratégico y Modelos Predictivos.

🔗 GitHub: https://github.com/PAOLAALAPA
