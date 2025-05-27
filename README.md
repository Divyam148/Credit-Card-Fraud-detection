# Credit Card Fraud Detection using Isolation Forest

## 📌 Overview

Credit card fraud is a significant concern in today's digital world. This project uses **Unsupervised Machine Learning**—specifically the **Isolation Forest** algorithm—to detect fraudulent transactions in a credit card dataset. Since fraudulent transactions are rare, the data is highly imbalanced, making unsupervised anomaly detection a suitable approach.

## 🧠 Algorithm Used

- **Isolation Forest**: An anomaly detection method that isolates outliers instead of profiling normal data points. It works well with high-dimensional datasets and is efficient even on large datasets.

## 📂 Dataset

- **Source**: [Kaggle - Credit Card Fraud Detection Dataset](https://www.kaggle.com/mlg-ulb/creditcardfraud)
- The dataset contains:
  - 284,807 transactions
  - 492 fraudulent transactions
  - Features are numerical values obtained through PCA
  - "Time", "Amount", and "Class" (0 = legitimate, 1 = fraud)

## 🛠️ Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/credit-card-fraud-detection.git
   cd credit-card-fraud-detection
