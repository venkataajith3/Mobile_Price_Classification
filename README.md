# 📱 Mobile Price Range Prediction

This project is focused on predicting the price range of mobile phones using various classification algorithms. It uses a dataset from Kaggle and demonstrates step-by-step implementation, training, tuning, and evaluation of multiple machine learning models.

---

## 📂 Project Structure

- `mobile_price_class.ipynb` – Main Jupyter Notebook containing the complete end-to-end code for data exploration, preprocessing, model building, hyperparameter tuning, and evaluation.

---

## 📊 Dataset

The dataset is sourced from Kaggle:  
🔗 [Mobile Price Classification Dataset](https://www.kaggle.com/datasets/iabhishekofficial/mobile-price-classification/data)

### 📌 Dataset Description

The dataset contains **mobile phone specifications** like battery power, RAM, number of cores, camera specs, screen size, etc., and the target variable `price_range` with four categories:

- `0` → Low  
- `1` → Medium  
- `2` → High  
- `3` → Very High  

Each row represents a different mobile phone with 20 features and a label indicating its price range.

---

## 🤖 Algorithms Implemented

The following classification models were trained and evaluated:

1. **Logistic Regression**
2. **K-Nearest Neighbors (KNN)**
3. **Decision Tree**
4. **Support Vector Machine (SVM)**
5. **Random Forest**
6. **AdaBoost**
7. **XGBoost**

Each model was:
- Trained on 80% of the dataset
- Evaluated on 20% validation data
- Tuned using **GridSearchCV** for optimal performance
- Measured using Accuracy, Classification Report, and Confusion Matrix

---

## 🏆 Best Performing Model

- **Model:** Logistic Regression  
- **Validation Accuracy:** **97.75%**

Logistic Regression outperformed more complex models in this case, showcasing the power of simpler models when features are scaled and well-engineered.

---

## 📌 Requirements

- Python 3.x
- scikit-learn
- xgboost
- pandas
- seaborn
- matplotlib
