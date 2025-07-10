# 💳 Credit Card Fraud Detection 📊

A Machine Learning project to detect fraudulent credit card transactions using classification algorithms like Decision Tree, Random Forest, and K-Nearest Neighbors (KNN).  
This project uses a **balanced dataset via under-sampling** and visualizes data distributions to better understand fraud patterns.

<br>


![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter&logoColor=white)
![Sklearn](https://img.shields.io/badge/Scikit--learn-ML%20Toolkit-yellow?logo=scikit-learn&logoColor=black)
![NumPy](https://img.shields.io/badge/NumPy-numeric-blue?logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-data%20analysis-lightgrey?logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-visualization-orange?logo=matplotlib&logoColor=white)

<br>

---

## 📑 About the Project  

This project demonstrates a **Credit Card Fraud Detection System** using various machine learning models like:

- 🌳 Decision Tree
- 🌲 Random Forest
- 🤝 K-Nearest Neighbors  

It involves data preprocessing, handling class imbalance through undersampling, visualizing key metrics, and evaluating model performance on detecting fraudulent transactions.

<br>

---

## 📂 Project Structure
```bash
📦 CreditCard_Fraud_Detection/
├── 📄 creditcard.csv
├── 📁 Visualising_images/
│ ├── 📊 correlation_heatmap.png
│ ├── 🌳 important_feature_to_DT.png
│ ├── 🕰️ time_vs_amount.png
│ ├── 📉 transaction_amount_distribution.png
│ ├── 📊 transaction_data_dustribution.png
│ └── 📈 transaction_percentage.png
├── 📓 CreditCard_fraud_detection.ipynb
└── 📑 README.md
```

<br>

---


## 📊 Exploratory Data Analysis

### 🔍 Correlation Heatmap  
Shows correlations between features.

![Correlation Heatmap](Visualising_images/correlation_heatmap.png)

---

### 📈 Transaction Amount Distribution  
Amount distribution for valid and fraudulent transactions.

![Amount Distribution](Visualising_images/transaction_amount_distribution.png)

---

### 📊 Transaction Class Distribution  
Visualizing data imbalance before under-sampling.

![Class Distribution](Visualising_images/transaction_data_dustribution.png)

---

### 📊 Fraud vs Valid Transaction Percentage  
Pie chart showing percentage split.

![Transaction Percentage](Visualising_images/transaction_percentage.png)

---

### 🕰️ Transaction Time vs Amount

![Time vs Amount](Visualising_images/time_vs_amount.png)

---

## 🌳 Feature Importance from Decision Tree

Identifying the most influential features in decision-making.

![Important Features Decision Tree](Visualising_images/important_feature_to_DT.png)

<br>

---

## 🧠 Models Applied

| Model                  | Accuracy |
|:----------------------|:----------|
| Decision Tree           | 88.83%    |
| Random Forest           | 95.43%    |
| K-Nearest Neighbors (KNN)| 63.96%   |

<br>

---

## 📈 Conclusion

- Random Forest outperformed other models on balanced data.
- Decision Tree provided decent interpretability.
- KNN struggled with this high-dimensional data.
- Data visualization and under-sampling effectively balanced the dataset.

---

## 📑 Requirements

- Python 3.x  
- scikit-learn  
- pandas  
- seaborn  
- matplotlib  
- numpy  

Install them using:
```bash
pip install pandas scikit-learn seaborn matplotlib numpy

```

<br>

---
## 🆘 Help & Support  

Have questions or need assistance? Feel free to connect with me! 🚀  

- 🔗 [![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?logo=linkedin)](https://www.linkedin.com/in/abhay-kanojia-0461a3341)

Let’s collaborate and build awesome things together! ✨

<br>


