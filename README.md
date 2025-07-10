# Maize Variety Analysis using Machine Learning

This project uses IoT sensor-based agricultural data to predict maize grain yield. The dataset includes information about soil treatment, irrigation, fertilizer, and maize variety. The goal is to help optimize crop production using ML models.

## 🔍 Problem Statement
Accurately predicting maize grain yield (ton/ha) based on experimental and environmental factors, to guide data-driven decisions in agricultural practices.

---

## 📊 Dataset
- Features: Irrigation method, fertilizer type, variety, rainfall, sowing method, and other soil/agro variables
- Target: Total grain yield (ton/ha)
- File used: `maize_dataset.csv` (stored in `adata/` folder)

---

## ⚙️ Models Used
- **Support Vector Regressor (SVR)**
- **Random Forest Regressor**
- Feature selection using `SelectKBest`
- Label encoding for categorical features

---

## 🧪 Evaluation Metrics
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- R² Score

---

## 🧰 Tools & Technologies
- Python, Pandas, NumPy
- Scikit-learn, Joblib
- Matplotlib, Seaborn
- Jupyter Notebook

---

## 📂 Project Structure
