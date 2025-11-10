# Credit_Card_Fraud_Detection_Using_LogisticRegression
Machine learning project for fraud detection using Logistic Regression, undersampling, and evaluation metrics (ROC, F1-score).
![Project Banner]


Detecting fraudulent credit card transactions using **Logistic Regression**.  
The dataset is **highly imbalanced**, so **undersampling** was used to balance it.  
Model achieved **93% accuracy** and **97% recall** on fraud detection.

---

##  Overview
- **Dataset:** [Kaggle Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- **Rows:** 284,807  
- **Columns:** 31  
- **Target:** `Class` → 0 = Legit, 1 = Fraud  

---

##  Steps Followed
1. Data loading and cleaning  
2. Exploratory Data Analysis (EDA)  
3. Balancing data using **undersampling**  
4. Feature scaling using **StandardScaler**  
5. Model building using **Logistic Regression**  
6. Model evaluation using **Precision**, **Recall**, **F1-score**, and **ROC–AUC**

---

## Model Performance
| Metric | Score |
|--------|--------|
| Accuracy | 93% |
| Precision (Fraud) | 0.91 |
| Recall (Fraud) | 0.97 |
| ROC–AUC | 0.97 |

✅ The model successfully detected ~90% of fraudulent transactions.

---

## Key Visuals
- Class Distribution Plot  
- Confusion Matrix  
- ROC Curve  

---

##  Tools Used
- **Python**
- **Pandas**, **NumPy**
- **Scikit-learn**
- **Matplotlib**, **Seaborn**

---

## Files Included
- `credit_card_fraud.ipynb` — Jupyter Notebook  
- `report_credit_card_fraud.pdf` — Project Report  


---

## Author
**Vani Moka**  
November 2025  
*LinkedIn:* [linkedin.com/in/vani-moka](https://linkedin.com/in/vani-moka)

---

⭐ *If you found this project useful, please give it a star on GitHub!*  

