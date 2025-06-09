# 📊 TabNet-Based Machine Learning Project

This project demonstrates the use of **TabNet**, a deep learning model designed specifically for tabular data. Built and executed in Google Colab, the notebook walks through data preprocessing, model training, evaluation, and feature interpretability using the `pytorch-tabnet` library.

---

## 📁 Project Contents

- `tabnet_model.ipynb`: The main Google Colab notebook containing the full ML workflow
- `Modified_SQL_Dataset.csv` : Dataset CIC-IDS-Collection
- `requirements.txt`: (Optional) Dependencies for local use
- `README.md`: Project overview and documentation

---

## 🚀 Key Features

- Uses **TabNet** for structured data modeling
- Supports both classification and regression tasks
- End-to-end pipeline: loading, cleaning, training, evaluating
- Visualizations for training loss, accuracy, and feature importance
- Easy to modify for different datasets

---

## 🔗 Open the Notebook

[Open in Google Colab]([https://colab.research.google.com/drive/13-u7de5m9aP1uQn64kOObexqKXYv9OL9?usp=sharing](https://colab.research.google.com/drive/13-u7de5m9aP1uQn64kOObexqKXYv9OL9?usp=sharing))

---

## 🧰 Setup Instructions

To run in Colab:
!pip install pytorch-tabnet

## 💻 To run locally:

git clone https://github.com/Abdalla-Ghanem-MCSD/Sqlinjection.git                                   
cd your-repo                                                            
pip install -r requirements.txt

## ❓ Example Results
✅ Accuracy: 0.9864165588615783
📊 Classification Report:
               precision    recall  f1-score   support

           0       0.98      0.99      0.99      3893
           1       0.99      0.97      0.98      2291

    accuracy                           0.99      6184
   macro avg       0.99      0.98      0.99      6184
weighted avg       0.99      0.99      0.99      6184


## 📦 Requirements
pytorch-tabnet
pandas
numpy
scikit-learn
matplotlib
seaborn
