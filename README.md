# 🧠 Early Prediction of Alzheimer’s Disease Using Supervised Machine Learning Models

## 📌 Project Description
This project aims to develop a **supervised Machine Learning model** capable of supporting the **early detection of Alzheimer’s disease**, using clinical and demographic patient data.

The main objective is to build an **interpretable, clear, and socially impactful model**, suitable for a **basic–intermediate level course**, while showcasing the full workflow of a data science project applied to healthcare.

---

## 🎯 Problem Statement
Alzheimer’s disease is a neurodegenerative condition that is often diagnosed at advanced stages, when cognitive decline is already significant.

This project seeks to:
- Support **early screening**
- Identify **risk patterns**
- Provide a **decision-support tool for healthcare professionals**
- Reduce false negatives by prioritizing **sensitivity (Recall)**

---

## 📊 Dataset
A public, tabular dataset related to Alzheimer’s disease was used, containing clinical, functional, and cognitive patient information.

**Dataset characteristics:**
- Over 2,000 instances
- 35 clinical and demographic features
- Target variable: `Diagnosis`
  - `0` → No Alzheimer’s  
  - `1` → Alzheimer’s

---

## 🧪 Most Relevant Features
After the feature selection process, the model identified the following variables as the most influential:

- **MMSE (Mini-Mental State Examination)**
- **ADL (Activities of Daily Living)**
- **Functional Assessment**
- Family history of Alzheimer’s
- Depression
- Hypertension
- Difficulty completing tasks
- Confusion and disorientation

These features represent key dimensions of Alzheimer’s disease:
- Cognition
- Functional capacity
- Independence
- Behavioral symptoms

---

## ⚙️ Methodology
The project follows a complete Machine Learning pipeline:

1. Exploratory Data Analysis (EDA)
2. Data cleaning and preprocessing
3. Correlation analysis
4. Feature selection
5. Class imbalance handling
6. Train/Test split
7. Standardization of numerical variables
8. Model training
9. Model evaluation using clinical metrics
10. Development of a graphical user interface

---

## 🤖 Models Evaluated
Several supervised classification algorithms were tested:

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)
- Gaussian Naive Bayes
- **XGBoost (final selected model)**

📌 **XGBoost** achieved the best overall performance, particularly in **Recall**, which was the prioritized metric due to its clinical relevance.

---

## 📈 Evaluation Metrics
The following evaluation metrics were used:

- Accuracy
- Precision
- Recall (**primary metric**)
- F1-Score
- Confusion Matrix
- ROC-AUC

The final model achieved a **Recall above 90%**, significantly reducing false negatives, which is crucial for early Alzheimer’s detection.

---

## 🖥️ Graphical User Interface
An interactive **graphical user interface (GUI)** was developed using **Streamlit**, allowing users to:

- Input clinical patient data
- Obtain real-time predictions
- Visualize results in a clear and intuitive way

This transforms the model into an **accessible and user-friendly tool** for non-technical users.

---

## 🚀 Technologies Used
- Python
- Pandas, NumPy
- Scikit-learn
- XGBoost
- Matplotlib, Seaborn
- Streamlit
- Google Colab
- GitHub

---

## 📂 Repository Structure

├── notebooks/
│ └── Alzheimer_Analysis.ipynb
├── app.py
├── alzheimer_model.pkl
├── requirements.txt
└── README.md


---

## ⚠️ Ethical Considerations
- The project uses **public and anonymized data**
- The model **does not replace medical diagnosis**
- Its use is strictly educational and supportive
- Predictions must be interpreted by healthcare professionals

---

## 👥 Authors
- **Santiago Santamaría**
- **Emanuel**

Academic project — Machine Learning applied to healthcare 🧠

---

## 📌 Conclusion
This project demonstrates how Machine Learning can provide valuable support in high-impact social problems such as Alzheimer’s disease, while maintaining a responsible, interpretable, and clinically relevant approach.
