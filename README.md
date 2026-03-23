# 🌌 Predicting Stars, Galaxies & Quasars with Machine Learning

## 📖 Overview
This project uses Machine Learning techniques to classify celestial objects into:
- ⭐ Stars
- 🌌 Galaxies
- ✨ Quasars

The dataset is obtained from the **Sloan Digital Sky Survey (SDSS)** and contains 10,000 observations with multiple astronomical features.

---

## 🎯 Objective
To build and evaluate machine learning models that can accurately classify astronomical objects based on their observed features.

---

## 📊 Dataset
- Source: SDSS (via Kaggle)
- Total Observations: 10,000
- Features: 17 input features + 1 target column (`class`)
- Target Classes:
  - 0 → Galaxy
  - 1 → Quasar
  - 2 → Star

### 🔍 Feature Examples
- `ra`, `dec` → Spatial coordinates
- `u, g, r, i, z` → Photometric filters (ultraviolet to infrared)
- `redshift` → Object distance indicator

---

## ⚙️ Workflow

1. **Dataset Introduction**
2. **Importing Libraries**
3. **Exploratory Data Analysis (EDA)**
4. **Data Preprocessing**
   - Dropping irrelevant columns
   - Label Encoding
5. **Feature Scaling**
   - StandardScaler
6. **Model Building & Evaluation**

---

## 🧠 Machine Learning Models Used

- 🌳 Decision Tree Classifier
- 📈 Logistic Regression
- 📍 K-Nearest Neighbors (KNN)

---

## 📈 Model Performance

| Model                | Accuracy |
|---------------------|----------|
| Decision Tree       | ~99%     |
| Logistic Regression | ~98%     |
| KNN                 | ~91%     |

### 🏆 Best Model:
**Decision Tree Classifier** performed the best with highest accuracy.

---

## 🛠️ Technologies Used

- Python 🐍
- NumPy
- Pandas
- Matplotlib & Seaborn
- Scikit-learn
- TensorFlow (imported but not heavily used)
