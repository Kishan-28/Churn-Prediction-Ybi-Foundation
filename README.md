#  Churn Prediction for ConnectSphere Telecom

This project was developed as part of the **AI & Generative AI Internship by YBI Foundation**. The goal is to build a predictive model using an **Artificial Neural Network (ANN)** to determine which telecom customers are likely to churn, based on historical data.

---

##  Problem Statement

ConnectSphere Telecom aims to reduce customer churn by proactively identifying users at risk of leaving the service. This project helps by analyzing customer demographics, usage patterns, and contract details using deep learning.

---

##  What is Churn?

**Customer Churn (or Attrition)** refers to customers who stop using a company's service during a given time period.

### In Telecom:
A customer is said to have **churned** if they:
- Cancel their subscription
- Switch to another telecom provider
- Stop renewing their plan

**Churn prediction** helps telecom providers:
- Reduce revenue loss
- Improve customer retention
- Personalize offers or interventions

---

##  Solution Overview

We used a **Binary Classification** approach with a deep learning model (ANN) to classify customers as likely to churn or not.

---

##  Tech Stack

- **Python**  
- **Google Colab**  
- **Pandas, NumPy, Matplotlib, Seaborn**  
- **Scikit-learn**  
- **TensorFlow / Keras**

---

##  Dataset

-  Source: [YBI Foundation GitHub Dataset](https://raw.githubusercontent.com/YBIFoundation/Dataset/refs/heads/main/TelecomCustomerChurn.csv)
- The dataset includes:
  - Demographics (gender, age, etc.)
  - Usage behavior (call charges, internet usage, etc.)
  - Subscription and contract details
  - Churn label (target variable)

---

##  Project Workflow

1. **Data Loading**  
2. **Exploratory Data Analysis (EDA)**  
3. **Preprocessing**
   - Label encoding for categorical data
   - Feature scaling
4. **Model Building**
   - 3-layer ANN using Keras Sequential API
5. **Model Training**
   - 50 epochs with validation split
6. **Model Evaluation**
   - Accuracy, F1-score, classification report
7. **Visualization**
   - Accuracy trends over epochs

---

##  Model Performance

-  **Accuracy**: _~85%_ (may vary)
-  **F1 Score**: Balanced performance on churn vs non-churn classes

---

##  How to Use

```bash
git clone https://github.com/Kishan-28/Churn-Prediction-Ybi-Foundation
```

Or open the notebook directly on Google Colab.

---

##  Future Improvements

- Hyperparameter tuning
- Use of advanced embeddings for categorical data
- Incorporating customer feedback or sentiment analysis

---

##  Acknowledgements

- **YBI Foundation** for the internship opportunity
- **Google Colab** for the computing platform
- **TensorFlow** for documentation and guides
