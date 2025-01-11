 **Anti-Money Laundering (AML)**

## **Machine Learning Algorithm for Anti-Money Laundering Software**

This repository contains a machine learning algorithm designed for Anti-Money Laundering (AML) purposes. The project leverages data science techniques to detect suspicious financial transactions and prevent illicit activities.

---

## **Overview**

The **AML Machine Learning Algorithm** focuses on enhancing the detection of money laundering activities within financial systems. By applying advanced machine learning models, the algorithm identifies patterns and anomalies in transaction data to improve accuracy, reduce false positives, and ensure compliance with financial regulations.

---

## **Features**

- **Data Preprocessing**:
  - Handling missing values using **median imputation**.
  - Outlier treatment with **Winsorization**.
  - Scaling numerical features using **MinMaxScaler**.
  - Encoding categorical features with **One-Hot Encoding**.

- **Model Training**:
  - Evaluated multiple classifiers including:
    - **Random Forest Classifier**
    - **Gradient Boosting Classifier**
    - **K-Nearest Neighbors**
    - **Support Vector Machines**
  - Optimized the **Random Forest Classifier**, achieving **95.2% accuracy**.

- **Model Saving**:
  - Saved the trained model using **Pickle** for future use.

- **Evaluation Metrics**:
  - Accuracy, recall, and confusion matrix analysis.
  - Focused on minimizing false negatives.

---

## **Dataset**

The dataset was sourced from **Kaggle**, containing financial transaction data relevant to detecting money laundering activities.

---

## **Technologies Used**

- **Platform**: Google Colab
- **Libraries**:
  - **Pandas**, **NumPy**: Data manipulation and analysis
  - **Scikit-learn**: Machine learning models and preprocessing
  - **Matplotlib**, **Seaborn**: Data visualization
  - **Pickle**: Model saving and loading

---

## **Results**

The **Random Forest Classifier** outperformed other models with the following metrics:
- **Accuracy**: 95.2%
- **Recall**: 97% (minimizing false negatives)

These results make the model effective at detecting fraudulent financial activities.

---

## **Conclusion**

This machine learning algorithm is a robust tool for identifying and preventing money laundering activities. By leveraging data science and machine learning, it enhances the financial system's ability to combat illicit transactions.

---
