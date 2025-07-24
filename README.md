"# Random-forest-regression-model" 
# 🧠 Machine Learning Project – Random Forest Regression

This project demonstrates the use of a **Random Forest Regressor** to predict target values using a given dataset. The model is trained, evaluated, and visualized using Python and Jupyter Notebook.

---

## 📂 Project Files

- `ML_second_project.ipynb` – Main Jupyter Notebook with data loading, preprocessing, training, and evaluation.
- `README.md` – Project overview and instructions.

---

## ⚙️ Technologies Used

- Python
- Scikit-learn
- Pandas
- Matplotlib / Seaborn (if plotting included)
- Jupyter Notebook

---

## 📊 Model Evaluation

The model is evaluated using:

- **Mean Squared Error (MSE)**
- **R-squared (R²) Score**

```python
from sklearn.metrics import mean_squared_error, r2_score

# Training Set Evaluation
rf_train_mse = mean_squared_error(y_train, y_rf_train_pred)
rf_train_r2 = r2_score(y_train, y_rf_train_pred)

# Testing Set Evaluation
rf_test_mse = mean_squared_error(y_test, y_rf_test_pred)
rf_test_r2 = r2_score(y_test, y_rf_test_pred)
