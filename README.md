# 🍽️ NutriClass: Food Classification Using Nutritional Data

A machine learning project that classifies food items based on their nutritional attributes such as calories, protein, fat, carbs, sugar, fiber, sodium, and more.  
The model predicts the **Food Type** category using macronutrient dominance:

- **High Protein**
- **High Carb**
- **High Fat**
- **Balanced**

---

## 📌 Project Overview

This project builds a complete ML pipeline to classify foods into meaningful nutritional categories.  
It includes:

- Exploratory Data Analysis (EDA)
- Feature Engineering
- Data Preprocessing
- Model Training & Evaluation
- Visualization of Results
- Final Comparative Analysis

---

## 🧠 Approach

1. Loaded and explored the nutritional dataset  
2. Performed EDA using histograms, boxplots, scatterplots, and correlation heatmaps  
3. Cleaned and preprocessed data:
   - Removed duplicates
   - Encoded categorical variables
   - Scaled numerical features  
4. Created a new target variable **Food_Type**  
5. Trained multiple ML models:
   - Logistic Regression
   - SVM
   - KNN
   - Decision Tree
   - Random Forest
   - Gradient Boosting
   - XGBoost
6. Evaluated models using:
   - Accuracy
   - Precision, Recall, F1-score
   - Confusion Matrix
7. Compared performance & selected the best model

---

## 📊 Data Visualization (EDA)

The project includes visualizations like:

- Feature distributions (histograms)
- Outlier detection (boxplots)
- Correlation heatmap
- Scatterplots for feature relationships
- Bar charts for category summaries
- Train vs Test model accuracy comparison

---

## 🛠️ Feature Engineering

Created a meaningful target variable:
Food_Type:

- High Protein
- High Fat
- High Carb
- Balanced

---

## ⚙️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost

---

## 🤖 Model Performance

Best accuracy achieved:

| Model | Test Accuracy |
|-------|---------------|
| **Logistic Regression** | **99.76%** |
| SVM | 98.97% |
| XGBoost | 98.91% |
| Random Forest | 98.17% |
| Gradient Boosting | 98.16% |
| Decision Tree | 97.85% |
| KNN | 92.56% |

**Logistic Regression** provided the highest and most stable performance.

---
📌 Results

Food classification achieved 98–99% accuracy

Strong patterns observed between nutrition values and food type

Linear models performed exceptionally well after scaling

Tree models captured non-linear trends effectively
