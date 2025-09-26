# Logistic Regression Classifier – Breast Cancer Detection

This project shows how I built a **binary classifier** using **Logistic Regression** on the Breast Cancer Wisconsin dataset.  
The goal is to predict whether a tumor is **Malignant (M)** or **Benign (B)**.

---

## What I Did
- Cleaned the dataset (removed unused columns, encoded target values)  
- Split the data into training and test sets  
- Standardized the features for better model performance  
- Trained a Logistic Regression model with scikit-learn  

---

## How It Performed
- Evaluated using **Confusion Matrix, Precision, Recall, ROC-AUC**  
- Visualized results with heatmaps and ROC curve  
- Played with the **decision threshold** to see how it impacts recall vs precision  

---

## Key Takeaways
- Logistic Regression outputs probabilities using the **sigmoid function**  
- Metrics like **Precision, Recall, ROC-AUC** matter more than raw accuracy in medical tasks  
- Tuning the classification threshold helps balance **false positives vs false negatives**  
