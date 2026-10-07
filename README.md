# Customer Segmentation using K-Means Clustering

## 📌 Project Overview

This project is a **Customer Segmentation Machine Learning application** developed during my internship.

The project uses **K-Means Clustering**, an unsupervised machine learning algorithm, to group customers into different segments based on their demographic and purchasing behavior.

A **Streamlit web application** is also developed to allow users to enter customer information and predict the corresponding customer segment.

---

## 🎯 Objective

The main objective of this project is to identify different customer groups based on their:

* Age
* Income
* Total Spending
* Number of Web Purchases
* Number of Store Purchases
* Number of Web Visits per Month
* Recency

The trained K-Means model predicts the customer segment based on these inputs.

---

## 🛠️ Technologies Used

* **Python**
* **Pandas**
* **NumPy**
* **Scikit-learn**
* **K-Means Clustering**
* **Joblib**
* **Streamlit**

---

## 📂 Project Structure

```text
Customer-Segmentation/
│
├── Analysis_model.ipynb       # Data analysis and model development
├── segmentation.py            # Streamlit application
├── customer_segmentation.csv  # Customer dataset
├── kmeans_model.pkl           # Trained K-Means model
├── scaler.pkl                 # Feature scaling model
└── README.md                  # Project documentation
```

---

## 🔍 Features

### 1. Customer Data Input

The Streamlit application allows users to enter:

```text
Age
Income
Total Spending
Number of Web Purchases
Number of Store Purchases
Number of Web Visits per Month
Recency
```

### 2. Feature Scaling

The input data is transformed using the saved scaler before being passed to the machine learning model.

### 3. Customer Segment Prediction

The trained K-Means model predicts the customer's cluster and displays the result in the application.

Example:

```text
Predicted Segment: Cluster 2
```

The application loads the trained model and scaler using Joblib.

---

## 🤖 Machine Learning Approach

The project uses **K-Means Clustering** for customer segmentation.

The workflow is:

```text
Customer Dataset
       ↓
Data Analysis
       ↓
Feature Selection
       ↓
Feature Scaling
       ↓
K-Means Clustering
       ↓
Trained Model
       ↓
Save Model & Scaler
       ↓
Streamlit Application
       ↓
Customer Segment Prediction
```

---

## 🌐 Streamlit Application

The application provides an interactive interface where users can enter customer information.

After clicking the **"Predict Segment"** button, the application processes the input and predicts the corresponding cluster.

---

## 🚀 How to Run the Project

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR-USERNAME/customer-segmentation.git
```

### 2. Navigate to the Project Folder

```bash
cd customer-segmentation
```

### 3. Install Required Libraries

```bash
pip install pandas numpy scikit-learn joblib streamlit
```

### 4. Run the Streamlit Application

```bash
streamlit run segmentation.py
```

### 5. Open the Application

Streamlit will provide a local URL, usually:

```text
http://localhost:8501
```

Open the URL in your browser.

---

## 📊 Input Features

| Feature           | Description                             |
| ----------------- | --------------------------------------- |
| Age               | Customer's age                          |
| Income            | Customer income                         |
| Total Spending    | Total amount spent by the customer      |
| NumWebPurchases   | Number of web purchases                 |
| NumStorePurchases | Number of store purchases               |
| NumWebVisitsMonth | Number of web visits per month          |
| Recency           | Days since the customer's last purchase |

These are the same customer inputs used by the Streamlit application.

---

## 📦 Model Files

The repository contains two saved machine learning components:

* `kmeans_model.pkl` — trained K-Means clustering model
* `scaler.pkl` — trained feature scaler

The application loads both files before making predictions.

---

## 💡 Key Learning Outcomes

Through this project, I gained practical experience in:

* Data preprocessing
* Exploratory data analysis
* Unsupervised Machine Learning
* K-Means clustering
* Feature scaling
* Model serialization using Joblib
* Building interactive ML applications with Streamlit
* Deploying a Machine Learning workflow into an application

---

## 👨‍💻 Internship Project

This project was developed as part of my **Machine Learning / Data Science internship** to gain hands-on experience in applying machine learning techniques to a practical customer analytics problem.

---

## 🔗 Links

**GitHub Repository:**
https://github.com/YOUR-USERNAME/customer-segmentation

**Live Demo:**
Add your Streamlit deployment link here.

---

## ⭐ If you found this project useful

Feel free to ⭐ star the repository and explore the project!

#MachineLearning #Python #DataScience #CustomerSegmentation #KMeans #Streamlit #DataAnalytics
