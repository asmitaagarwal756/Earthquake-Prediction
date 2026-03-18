# Earthquake Impact Prediction

This project applies **machine learning algorithms** to predict the impact significance of earthquakes using features such as magnitude, depth, geographical location, and time.  

## Dataset  
- **Source:** Kaggle Earthquake dataset  
- **Features:** Magnitude, depth, location, time-related attributes  
- **Target:** Impact significance (Low, Moderate, High)  

## Experiments  

### 1. Exploratory Data Analysis (EDA)  
- Visualized earthquake data using **Matplotlib** (line plots, bar charts, scatter plots, histograms).  
- Identified trends, anomalies, and distributions to guide model selection.  

### 2. Regression Models  
- **Linear Regression**: Baseline model for continuous prediction.  
- **Polynomial Regression**: Modeled non-linear relationships.  
- **Logistic Regression**: Binary classification of earthquake impact.  
- **Results:**  
  - Polynomial Regression achieved **R² = 0.9453**  
  - Logistic Regression achieved **Accuracy = 99.76%**, **ROC-AUC = 0.9997**  

### 3. Classification Models  
- **K-Nearest Neighbors (KNN)**  
  - Accuracy up to **99.50%** (50-50 split).  
- **Random Forest**  
  - Accuracy ~**99.71%**, strong robustness against overfitting.  
- **Naive Bayes**  
  - Accuracy ~**99.29%**, efficient for probabilistic classification.  
- **Decision Tree**  
  - Accuracy ~**99.88%**, interpretable model with clear decision rules.  

## Evaluation Metrics  
- Accuracy, Precision, Recall, F1 Score  
- Confusion Matrix  
- ROC-AUC  
- Mean Squared Error (for regression tasks)  

## Tech Stack  
- **Python** (Google Colab)  
- **Libraries:** NumPy, Pandas, Scikit-learn, Matplotlib  

## Results  
- High accuracy across models, with **Logistic Regression and Random Forest** performing exceptionally well.  
- Visualizations and metrics confirm reliable predictions for earthquake impact classification.  

---

