"# Random-forest-regression-model" 
# 🧪 Solubility Prediction Using Machine Learning

This project demonstrates how to build and evaluate regression models to predict the solubility (`logS`) of chemical compounds based on molecular descriptors. The dataset is sourced from [Data Professor's GitHub repository](https://github.com/dataprofessor/data), and the models are built using Scikit-learn in Python.

---

## 📁 Dataset

**Source**: [Delaney solubility dataset](https://github.com/dataprofessor/data/blob/master/delaney_solubility_with_descriptors.csv)  
- **Target**: `logS` (log solubility)
- **Features**: Molecular descriptors

---

## ⚙️ Technologies Used

- Python
- Pandas
- Scikit-learn
- Jupyter Notebook
- Matplotlib (optional for plots)

---

## 🧠 Machine Learning Models

1. **Linear Regression**
2. **Random Forest Regressor**

Each model is trained using an 80-20 train-test split, and evaluated using:

- Mean Squared Error (MSE)
- R-squared (R²)

---

## 📊 Model Evaluation

### 📌 Evaluation Metrics Used
```python
from sklearn.metrics import mean_squared_error, r2_score
