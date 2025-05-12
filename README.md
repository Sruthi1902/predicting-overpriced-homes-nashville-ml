# 🏠 Predicting Overpriced Homes – Supervised ML on Nashville Housing Data

This project analyzes real estate transaction data from Nashville (2013–2016) to predict whether a home is **overpriced** based on its attributes. It showcases a complete machine learning pipeline using six models, including a final ensemble classifier that achieved **95.1% accuracy**.

---

## 🧠 Business Relevance

This project reflects how machine learning can transform business decision-making:

- 📊 Built to address **real-world pricing challenges** in the housing market  
- 🔄 Covers the **entire ML pipeline**: from raw data to model deployment decisions  
- 🧩 Demonstrates skills applicable to **pricing optimization**, **risk evaluation**, and **predictive modeling** across industries like real estate, finance, retail, and operations

---

## 🛠️ Tools & Tech

- **Languages**: Python  
- **Libraries**: pandas, scikit-learn, matplotlib, seaborn, imbalanced-learn  
- **ML Techniques**: Feature engineering, SMOTE, one-hot encoding, scaling  
- **Models Used**: Logistic Regression, Decision Tree, Random Forest, Gradient Boosting, Neural Network, Voting Ensemble

---

## 🔍 ML Pipeline Overview

1. **Data Cleaning** – Removed nulls, duplicates, and irrelevant columns  
2. **Feature Engineering** – Encoded categorical features, standardized numeric columns  
3. **Balancing** – Used SMOTE to resolve class imbalance  
4. **Modeling** – Trained and compared six supervised models  
5. **Evaluation** – Assessed using accuracy, precision, recall, F1-score, and ROC-AUC  
6. **Result** – Final Voting Classifier achieved the best overall performance

---

## 🧪 Model Performance Comparison

| Model                    | Accuracy  | Precision | Recall   | F1-Score |
|--------------------------|-----------|-----------|----------|----------|
| Logistic Regression      | 0.8996    | 0.9364    | 0.9274   | 0.9319   |
| Decision Tree            | 0.9008    | 0.9412    | 0.9238   | 0.9324   |
| Random Forest            | 0.8564    | 0.8732    | 0.9430   | 0.9068   |
| Gradient Boosting        | 0.9479    | 0.9572    | 0.9732   | 0.9651   |
| Neural Network (MLP)     | 0.9447    | 0.9621    | 0.9632   | 0.9627   |
| **Voting Ensemble** ✅     | **0.9507** | **0.9583** | **0.9759** | **0.9670** |

---

## 📂 Files in this Repo

- `Nashville_Housing_Classification.ipynb` – Full code notebook
- `nashville_housing.csv` – Housing dataset used for training/testing
- `README.md` – Project summary and insights

---

## 📬 Author

**Sruthi Kondra**  
🎓 Master’s in Analytics | Northeastern University  
📊 Data Analyst | Python, SQL, Tableau, Predictive Modeling  
🔗 [LinkedIn](https://www.linkedin.com/in/sruthi-kondra-5773981a1)

---

## 📜 License

Licensed under the **MIT License** – free to use, modify, and distribute with attribution.
