# Fraud-Detection-in-Credit-Card-Transactions-
This project focuses on detecting fraudulent credit card transactions using machine learning. It involves data analysis, preprocessing, and applying classification models to distinguish between legitimate and fraudulent transactions.

---

# 💳 Fraud Detection in Credit Card Transactions

This project focuses on detecting fraudulent credit card transactions using machine learning. It involves data analysis, preprocessing, and applying classification models to distinguish between legitimate and fraudulent transactions.

---

## 🎯 Objective

To develop a machine learning model that accurately detects credit card fraud and helps minimize financial loss by identifying suspicious transactions in real time.


---

## 🛠️ Tools and Technologies

- Python 3.x  
- Pandas, NumPy – data processing  
- Seaborn, Matplotlib – visualization  
- Scikit-learn – machine learning  
- Imbalanced-learn – handling class imbalance (SMOTE)  
- (Optional) XGBoost or LightGBM – advanced classifiers

---

## 🔑 Project Steps

1. **Data Loading & Exploration**
   - Understand class imbalance
   - Explore feature distribution

2. **Data Preprocessing**
   - Normalize `Amount` and `Time`
   - Handle imbalance using SMOTE or undersampling
   - Train-test split

3. **Model Building**
   - Try models: Logistic Regression, Random Forest, XGBoost
   - Use stratified k-fold cross-validation

4. **Model Evaluation**
   - Confusion Matrix, Precision, Recall, F1-Score
   - ROC-AUC Curve
   - Compare models for best performance

5. **Insights**
   - Analyze model effectiveness
   - Suggest how to reduce false positives

---

## 📈 Sample Visuals

- Fraud vs Non-Fraud 
- Correlation heatmap
- ROC Curve
- Feature importance plot

---

## ⚠️ Challenges

- Highly imbalanced data (fraud is ~0.17%)
- Cost of false negatives is high (missed frauds)
- Need for precision in real-time predictions

---

## 👨‍💻 Author

**Manoj Kumar**  
_Data Enthusiast | Passionate about fraud analytics and security_  

---

## 📃 License

This project is licensed under the **MIT License**.  
You are free to use, modify, and share this project with proper credit.
