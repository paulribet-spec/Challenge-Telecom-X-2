# Challenge-Telecom-X-2: Predicción de Cancelación de Clientes (Churn)

Proyecto de machine learning para predecir la cancelación de clientes en la empresa Telecom X, utilizando datos demográficos, de servicios y contractuales.

## Dataset
- **Registros:** 7.043 clientes y 22 variables
- **Variable objetivo:** `Churn` (Si el cliente canceló o no)

## Flujo del Proyecto
1. Exploración y limpieza de datos
2. Codificación de variables categóricas (Label Encoding + One-Hot Encoding)
3. Análisis de desbalance de clases
4. Análisis exploratorio y matriz de correlación
5. División train/test (80/20 con stratify)
6. Entrenamiento y evaluación de modelos (Decision Tree, Random Forest, XGBoost)
7. Optimización y ajuste fino del modelo final

## Modelo Final
**XGBoost con Ajuste Fino** — ROC-AUC: 0.848 | Recall: 0.80

## Tecnologías
- Python 3, Google Colab
- pandas, numpy, scikit-learn, xgboost, matplotlib, seaborn

## Archivos
- `proyecto_churn.ipynb` — Notebook principal con el análisis completo
- `datos_tratados.csv` — Dataset utilizado

---

##  Autor

Paul Ribet Salort
