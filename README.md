# 📊 Customer Churn Prediction in Telecom

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)
[![Published](https://img.shields.io/badge/Published-IEEE-orange.svg)](https://ieeexplore.ieee.org/)

This repository contains the implementation of our research paper titled:

**"A Novel Approach to Customer Churn Prediction in Telecom"**

Published by **IEEE** at the **2024 International Conference on Advances in Computing, Communication, and Applied Informatics (ACCAI)**.

---

## 📌 Overview

This project explores the prediction of customer churn in the telecom sector using various machine learning models. The study highlights the superior performance of the **Histogram-based Gradient Boosting (HistGB)** model and an ensemble approach that boosts overall prediction accuracy.

---

## 🏆 Key Highlights

- Uses multiple machine learning models including:
  - Logistic Regression
  - Decision Tree
  - Random Forest
  - XGBoost
  - Histogram-based Gradient Boosting
- Ensemble model achieves **96.39%** accuracy.
- HistGB model achieves a **ROC AUC of 99.49%**.

---

## 🗂️ Project Contents

churn-prediction/
├── data/ # Sample/preprocessed dataset (not included here)
├── models/ # Trained model files
├── src/ # Core training and utility scripts
├── churn_prediction.ipynb # Jupyter notebook with complete workflow
├── requirements.txt # Dependencies
├── README.md # Project documentation
└── LICENSE # MIT License

yaml
Copy
Edit

---

## 🚀 Getting Started

### 1. Clone this repository

```bash
git clone https://github.com/<your-username>/churn-prediction.git
cd churn-prediction
2. Install dependencies
bash
Copy
Edit
pip install -r requirements.txt
3. Run the Jupyter Notebook
bash
Copy
Edit
jupyter notebook churn_prediction.ipynb
📊 Results
Model	Accuracy	ROC AUC
Logistic Regression	✓	✓
Decision Tree	✓	✓
Random Forest	✓	✓
HistGradientBoosting	96.14%	99.49%
Ensemble Model	96.39%	97.88%

📚 Citation
If you use this code or research in your work, please cite our paper:

bibtex
Copy
Edit
@inproceedings{vineesh2024churn,
  title={A Novel Approach to Customer Churn Prediction in Telecom},
  author={Vineesh and Senthilselvi, A. and Kanishk, V. and Praveen Raj, A.},
  booktitle={2024 International Conference on Advances in Computing, Communication, and Applied Informatics (ACCAI)},
  year={2024},
  organization={IEEE}
}
📬 Contact
For any queries, feel free to contact me via GitHub or email.

🧾 License
This project is licensed under the MIT License.
